---
layout: page
title: Docker in Production - Reality, Not Hype
footer: false
---

<a href="http://www.meetup.com/devops/events/220204583/">DevOps Chicago Meetup</a><br>
Chicago, Illinois<br>
2015-03-09<br>

<br>

At <a href="http://www.dramafever.com">DramaFever</a>, the largest streaming video site for international content, we've been running Docker in production since October 2013 (well before it even went 1.0). Cutting (maybe bleeding) edge? Sounds fun! But important technology stack decisions are not made by running a Markov text generator against the front page of Hacker News. So, why are we using Docker? Simply put, it makes our development more consistent and our deployment more repeatable.
<p>
<br>
Because all the developers are developing locally using the same containers, integration is much easier when their code moves on to their EC2-based personal dev environment, the shared dev environment, QA, staging, and production. (Our previous Vagrant-based process didn't keep us consistently all using the same environment, as production wasn't under config management, and setting up local copies of the MySQL database with all the fixtures took just this side of eternity.) Because a production instance is serving code from a container, every new autoscaled instance that has any code at all is going to have the correct code. (And our previous "check out code from GitHub and bake an AMI" deployment process was not what you’d call speedy.)
<p>
<br>
Docker provides just enough in the way of training wheels for Linux containers that everyone can use it (for rapidly increasing values of everyone). In this talk, I detail how DramaFever implemented Docker for our entire development pipeline from laptops to production, covering the pain points and failure scenarios we've encountered and how we've worked through them.

<br>
<br>
<p>

My <a href="http://sysadvent.blogspot.com/2014/12/day-1-docker-in-production-reality-not.html">SysAdvent post for 2014</a> covers this topic in more detail.

<br>
<p>
<iframe src="//www.slideshare.net/slideshow/embed_code/45674173" width="425" height="355" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/bridgetkromhout/docker-in-production-reality-not-hype-devops-chicago" title="Docker in Production: Reality, Not Hype - DevOps Chicago" target="_blank">Docker in Production: Reality, Not Hype - DevOps Chicago</a> </strong> from <strong><a href="//www.slideshare.net/bridgetkromhout" target="_blank">bridgetkromhout</a></strong> </div>
<p>
<br>

<iframe src="https://player.vimeo.com/video/122583164" width="500" height="281" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe> <p><a href="https://vimeo.com/122583164">Bridget Kromhout</a> from <a href="https://vimeo.com/orbitzideas">Orbitz IDEAS</a> on <a href="https://vimeo.com">Vimeo</a>.</p>
<br>


<pre>
Headed to the @DevOpsChicago Meetup to hear @bridgetkromhout talk about Docker! http://t.co/EFt24ayhvC

— Shannon Smith Page (@shannonlly) March 9, 2015
</pre>
{{< tweet 575073888016678912 >}}
{{< tweet 575092636870012928 >}}
{{< tweet 575102476505890816 >}}
{{< tweet 575105549420855296 >}}
{{< tweet 575126928581128193 >}}
{{< tweet 575166970061959168 >}}
{{< tweet 575277382904455169 >}}
