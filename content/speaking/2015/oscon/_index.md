---
layout: page
title: Docker in Production - Reality, Not Hype
footer: false
---

<div class="views-field views-field-nothing">        <span class="field-content views-field-field-details"><a href="http://www.oscon.com/open-source-2015/public/schedule/detail/42037">OSCON - Docker in Production: Reality, Not Hype</a><br>Portland, Oregon<br><span class="date-display-start">2015-07-20</span> to <span class="date-display-end">2015-07-24</span></span></div>
<br>


<br>

At DramaFever, we’ve been running Docker in production since October 2013 (well before it even went 1.0). Cutting (maybe bleeding) edge? Sounds fun! But important technology stack decisions are not made by running a Markov text generator against the front page of Hacker News. So, why are we using Docker? Simply put, it makes our development more consistent and our deployment more repeatable.
<br>
<br>
Because all the developers are developing locally using the same containers, integration is much easier when their code moves on to their EC2-based personal dev environment, the shared dev environment, QA, staging, and production. (Our previous Vagrant-based process didn’t keep us consistently all using the same environment, as production wasn’t under config management, and setting up local copies of the MySQL database with all the fixtures took just this side of eternity.)
<br>
<br>
A production instance serves code from a container, so each new autoscaled instance that has any code at all is going to have the correct code. (And our previous “check out code from GitHub and bake an AMI” deployment process was not what you’d call speedy.)
<br>
<br>
Docker provides just enough in the way of training wheels for Linux containers that everyone can use it (for rapidly increasing values of everyone).
<br>
<br>
In this talk, I will detail how DramaFever implemented Docker for our entire development pipeline from laptops to production. I’ll cover the pain points and failure scenarios we’ve encountered and how we’ve worked through them, and I’ll demonstrate the ways that Docker being open-source has helped us in our adoption.
<br>
<br>

<i>Original timeslot - Wednesday, July 22</i>

<iframe width="560" height="315" src="https://www.youtube.com/embed/Fl7h3tenASU" frameborder="0" allowfullscreen></iframe>
<br>
<br>

<i>Encore performance - Thursday, July 23</i>

<iframe width="560" height="315" src="https://www.youtube.com/embed/sXIN8EoK0sE" frameborder="0" allowfullscreen></iframe>
<br>
<br>


<iframe src="https://www.slideshare.net/slideshow/embed_code/key/rUG3levqsJNZwl" width="476" height="400" frameborder="0" marginwidth="0" marginheight="0" scrolling="no"></iframe>
<br>
<br>



{{< tweet 623908321720934401 >}}
{{< tweet 623909334691414016 >}}
{{< tweet 623911434645143554 >}}
{{< tweet 623911479742324736 >}}
{{< tweet 623911901487992832 >}}
{{< tweet 623913311310999552 >}}
{{< tweet 623913644439375874 >}}
{{< tweet 623914751744020480 >}}
{{< tweet 623915158453116928 >}}
{{< tweet 623919707788148736 >}}
{{< tweet 623920246101913600 >}}
{{< tweet 623920418638827520 >}}
{{< tweet 623920418643009538 >}}
{{< tweet 623935022001618944 >}}
{{< tweet 623921200557731840 >}}
{{< tweet 623923287614193664 >}}
{{< tweet 623931015300562944 >}}
{{< tweet 623990075018248192 >}}
{{< tweet 624022372799148032 >}}
{{< tweet 624023488961974272 >}}
{{< tweet 624031184272535552 >}}
{{< tweet 623930099146993664 >}}
{{< tweet 624250768388829185 >}}
{{< tweet 624251286695735296 >}}
{{< tweet 624248819706761216 >}}
{{< tweet 624256969671593984 >}}
{{< tweet 624257930657804288 >}}
{{< tweet 624282422826409984 >}}
{{< tweet 624286982865293314 >}}
{{< tweet 624287954933022721 >}}
{{< tweet 624288143525715968 >}}
{{< tweet 624289713596289025 >}}
{{< tweet 624291822643318785 >}}
{{< tweet 624292136691871744 >}}
{{< tweet 624292227305619456 >}}
{{< tweet 624292954258210818 >}}
{{< tweet 624294519169753088 >}}
{{< tweet 624295714290573314 >}}
{{< tweet 624650539586838528 >}}
