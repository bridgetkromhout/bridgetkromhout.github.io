---
layout: page
title: Cooking Up Drama
footer: false
---

<a href="http://sched.co/2HaE">Chef Conf</a><br>
Santa Clara, California<br>
2015-03-31 to 2015-04-02<br>

<br>

Presented with Peter Shannon (<a href="http://peterjshan.com/posts/2015/04/chefconf2015/">link to his blog post on the topic</a>)
<br>
<br>
"What do you mean, we don't have configuration management?" Joining DramaFever's ops team last year, we both came from orgs that used Chef, but initially we disagreed about which flavor of CM to use here. We cooperated to build awesome instead of vying for the upper hand. (Go go gadget devops.) We'll discuss the initial concerns around going with Chef and how we addressed them.
<br>
<br>
DramaFever uses Docker extensively, but we found Dockerfiles aren't enough to keep All The Things consistent. We need to predictably create and maintain the host instances and then launch containers in the right environment for our main Django app or any of our golang microservices. Using Chef along with other tools such as Packer, we're beginning to bring order to dev, qa, monitoring, CI, and our AMI creation process as well as our entire application infrastructure. 
<br>
<br>
We'll detail how we're reducing deployment overhead and increasing maintainability for our AWS-based video platform, which streams international content, documentaries, and horror to a rapidly growing worldwide audience.  We will also share some of the pitfalls and corner cases we are working through in order to create our desired infrastructure.

<br>
<br>
<iframe src="//www.slideshare.net/slideshow/embed_code/46616404" width="476" height="400" frameborder="0" marginwidth="0" marginheight="0" scrolling="no"></iframe>
<br>
<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/8fcDZB-QMRA" frameborder="0" allowfullscreen></iframe>
<br>
<br>


{{< tweet 583318103850795008 >}}
{{< tweet 583373288962846720 >}}
{{< tweet 583380097836564480 >}}
{{< tweet 583380307237175296 >}}
<pre>
@dmarsh @bridgetkromhout Loving her talk!

— Ines Sombra (@randommood) April 1, 2015
</pre>

{{< tweet 583381355121115141 >}}
{{< tweet 583382501457969152 >}}
{{< tweet 583384681346809858 >}}
{{< tweet 583386564723490816 >}}
{{< tweet 583386575968473088 >}}
{{< tweet 583386848099069952 >}}
{{< tweet 583387772217663488 >}}
{{< tweet 583388507575422977 >}}
{{< tweet 583388563527434240 >}}
{{< tweet 583388608616239104 >}}
{{< tweet 584021185840558081 >}}
{{< tweet 584089778691289088 >}}
