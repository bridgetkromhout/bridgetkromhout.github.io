---
layout: page
title: Lights, Camera, Docker - Streaming Video at DramaFever
footer: false
---

<a href="http://container.camp/">Container Camp</a><br>
San Francisco, California<br>
2015-04-17<br>

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
<iframe src="https://www.slideshare.net/slideshow/embed_code/key/HzPVTorgZVC3hU" width="476" height="400" frameborder="0" marginwidth="0" marginheight="0" scrolling="no"></iframe>
<p>

<br>
<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/IAsQYYmlinU" frameborder="0" allowfullscreen></iframe>
<br>
<br>

My <a href="http://sysadvent.blogspot.com/2014/12/day-1-docker-in-production-reality-not.html">SysAdvent post for 2014</a> covers this topic in more detail.

<br>
<p>
<p>


{{< tweet 589193102113406976 >}}
{{< tweet 589197033648459777 >}}
{{< tweet 589198889468567552 >}}
{{< tweet 589199927726575616 >}}
{{< tweet 589199225835028481 >}}
{{< tweet 589199413316190208 >}}
{{< tweet 589199655990210560 >}}
{{< tweet 589200628074745856 >}}
{{< tweet 589202521211609088 >}}
{{< tweet 589200346351685632 >}}
{{< tweet 589200637159550976 >}}
{{< tweet 589200895830700032 >}}
{{< tweet 589201012092612609 >}}
{{< tweet 589202770944663553 >}}
{{< tweet 589201088999337984 >}}
{{< tweet 589201649983303681 >}}
{{< tweet 589201682539552768 >}}
{{< tweet 589201919446388736 >}}
{{< tweet 589201990502076416 >}}
{{< tweet 589201993794588672 >}}
{{< tweet 589202346296549376 >}}
{{< tweet 589203424341721089 >}}
{{< tweet 589204265207525376 >}}
{{< tweet 589204275907010561 >}}
{{< tweet 589204505574518784 >}}
{{< tweet 589204745463541760 >}}
{{< tweet 589205127703101440 >}}
{{< tweet 589205619212570624 >}}
{{< tweet 589205665475866624 >}}
{{< tweet 589206307401437184 >}}
{{< tweet 589206500838547456 >}}
{{< tweet 589207139442237441 >}}
{{< tweet 589213207090180096 >}}
{{< tweet 589213352913600512 >}}
{{< tweet 589230714081574912 >}}
{{< tweet 589223152443527168 >}}
