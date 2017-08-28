+++
title = "noona is devops style"
date = "2014-12-22"
slug = "noona-is-devops-style"
aliases = "blog/2014/12/22/noona-is-devops-style"
featured_image = "/images/kitties.png"
Categories = []
+++


In [A Woman’s Place Is at the Command Prompt](http://bridgetkromhout.com/speaking/2014/velocity-newyork/) at [Velocity NY 2014](http://velocityconf.com/velocityny2014), our panel facilitator [Lara Hogan](http://larahogan.me) asked me, "So, how did you get tricked into operations?" 

Yes, it’s funny, but there’s also a fair amount of truth there. Most people I know who work in any kind of technical operations didn't start out intending to do that; it just _happened_. In my case, I got a campus job with the computer science department, and apparently giving root to undergrad student workers was a reasonable solution to being understaffed. (It was the 1990s. Many things seemed like a good idea at the time.)

Fast-forward twenty years, and I get an out-of-nowhere email from a young man who's graduating from college in a few months and wants to know how he can be me when he grows up. (Obviously he doesn't think he'll be _me_ me, but, you know.)

Since I didn't follow a plan, I can't lay one out for him, but I can point to a few things that will probably help. Maybe. Possibly. (You realize that I’m pretty much just faking being a responsible adult, right? As long as we’re all clear on that.)

<!-- more -->

**Culture stuff**

I'm putting this first, because it's really important. If you work in tech for even a little while, you'll notice that you have a lot of social and economic privilege, no matter your demographic identity, because you have more choices in your work and life than do many of your fellow humans. This means that you have a responsibility to, in short, think about other people, not just yourself. 

Social justice is profoundly important in tech, just as it is in the wider world. Educate yourself about it. You may not read every article in every issue of [Model View Culture](https://modelviewculture.com), but being aware of the conversations happening around you is valuable.

There’s also an increasing likelihood that you may meet and even work with people who aren’t exactly like you, along one or more axes. This is a good thing. As [Aneel Lakhani](https://twitter.com/aneel) put it in his [Velocity NY 2014 Ignite](https://www.youtube.com/watch?v=Gi5EkmWi3VQ&list=UU3BGlwmI-Vk6PWyMt15dKGw), "the single strongest signal that you have something to learn is that a difference exists".

So! If you act like a decent human being who considers others, you'll be the kind of person others want as a co-worker and employee. Organizations that value a devops practice also tend to value cooperation, diversity, respect for the ideas/needs/opinions of others, accountability without assignment of blame, and generally not being a jerk. There’s a great quote by [Jesse Robbins](https://twitter.com/jesserobbins): "Don’t fight stupid. Make more awesome."


**Tools**

The one constant in your tools is going to be change. Mastery of tools is a great thing, but learning _how_ to learn is even more important. You’re going to keep needing that. And as you’ve noticed, ops isn’t something they usually teach you in school (which is why we have [OpsSchool](http://www.opsschool.org/en/latest/)).

Here's my 10,000 foot view of the stuff I think you need:

* Distributed version control. If you didn't get exposure to [git](http://git-scm.com) in school or an internship, start using it for your personal projects right now. Yes, there are other choices, but git is the one you'll probably run into in a more startup-flavored workplace. Understanding branching, merging, pull requests, forks, and the like is a good idea. Centralized version control is not a great substitute (although you’ll find it at many shops).

* Virtualization. The days of most orgs choosing to have and run their own hardware are coming to a definite middle. And even with on-prem or colocated hardware, getting the most out of your gear while allowing for flexibility means you're probably going to use virtual machines of some sort. When you start looking at private and public cloud, that's even more true. Get familiar with the concepts and execution behind hypervisors and VMs. Play with [Vagrant](https://www.vagrantup.com). Try [Docker](https://www.docker.com). Use your [EC2 free tier](http://aws.amazon.com/free/).

* Configuration management. Operating at any sort of scale is a lot easier if you can treat your infrastructure configurations as code. If you haven't done CM on the job before, take a look at the simpler implementations like [SaltStack](http://www.saltstack.com) or [Ansible](http://www.ansible.com/). Many larger shops are likely to be using [Chef](https://www.chef.io) or [Puppet](http://puppetlabs.com), so once you get the idea, it’s a good idea to look at those. [CFEngine](https://cfengine.com) has been around the longest and you may encounter that as well.

* Programming. If you’re working in ops, it’s possible you aren’t going to be building out all the new features using the fanciest of frameworks. But if you can be comfortable in languages like bash, Python, Ruby, and Go, you’ll be able to see what’s going on in most situations you’re likely to encounter. (YMMV - there’s plenty of Perl and PHP still out there - but these are what I tend to see.) And a smattering of JavaScript (specifically, Node.js) would not be amiss.


**Learning**

So wait, what about all this school stuff? It took years. There were grades and tests and group projects. Which stuff will actually matter?

* Abstraction. The specific implementations of flow control or data storage in a given language will vary. You'll want to become fluent in the languages you use, but it's also useful to understand basic data structures (how is a list different from an array? Why use one instead of another?) and concepts (what is a no-op? what is iteration?).

* Scientific method. You probably took lab classes where you proved that gravity works or electricity zaps or whatever. Here's the thing: the result was never the point. The point was teaching you to change one variable at a time and make careful observations along the way. When you're trying to solve problems in complex systems, you're going to be looking at a lot of noise. Trying to discern some useful signal is going to require you to pay pedantic attention to detail. You will learn to look for patterns while being aware that correlation does not equal causation.

* Math. Calculus actually matters, as does stats. You probably figured you'd never need calc again after finishing your physics sequence, but you will be excited to look at sums over time when you're debugging a problem looking at your [StatsD](https://codeascraft.com/2011/02/15/measure-anything-measure-everything/) data in [Graphite](http://graphite.readthedocs.org/en/latest/). Statistics will help you comprehend your metrics and their relationship to your business needs.

* Playing well with others. You know those group projects where your grade depended on other people and it was really frustrating if you couldn’t pick the people because they wouldn’t always produce usable work? Well, that’s an accurate model of the workplace. Choose your team with a lot of care; you want to know you can rely on them. And you want to be that person your classmates recruit for their future employers. 
      

**Community**

You are not alone. There are many practitioners who will be excited to encourage you along this journey. Here are some places to find them. Many may seem exceedingly obvious, but I include them in order to show a complete picture.

* Meetups. Even with zero budget, you can start meeting local people in your field and being exposed to new ideas. Go to [meetup.com](http://www.meetup.com) and search for your local area, and look at the available tech meetups. There's probably a devops or infracoders meetup, or maybe something about cloud, or a golang meetup - whichever! Join, RSVP, attend.

* Conferences. Your local community may have barcamps or unconferences. These will typically be free or low-cost with minimal barriers for entry. There may be "open space" talks, which means that topics will be chosen day-of by the attendees. There is not going to be an awesomeness test at the door. Even if you feel like you'll be out of your depth, just show up. You don't get partial credit for leaving a blank answer on a test in school, and you'll miss out on 100% of the opportunities you don't show up for (with apologies to Wayne Gretzky).

	The regional devopsdays conferences are low-cost, welcoming to newcomers, and an all-around good investment of time. Keep an eye on [devopsdays.org](http://devopsdays.org) as they start to crop up for the 2015 conference season. Come to Minneapolis in July for the one I help run! :)

The larger regional/national/international conferences sometimes have scholarships and sliding-scale rates, but your best bet for a free or discounted ticket is seeing if there's some way you can participate (ranging from volunteering to speaking). Conferences like [Monitorama](http://monitorama.com) and [Velocity](http://velocityconf.com) are wonderful if you can make them work for you.

And if you can’t make it to a conference in person, there is often a wealth of video either livestreamed or available after the fact. One good example is [Andrew Clay Shafer](https://twitter.com/littleidea)'s amazing talk about [learning organizations and no talent shortage](https://www.youtube.com/watch?v=P_sWGl7MzhU) at Velocity NY 2013.

* Podcasts. There are lots of podcasts on devops topics. Check out [DevOps Cafe](http://devopscafe.org/), [the Ship Show](http://theshipshow.com/), [the Food Fight Show](http://foodfightshow.org/), and of course the one I’m now co-hosting, [Arrested DevOps](http://arresteddevops.com). And you can play along at home most weeks with [hangops](http://www.hangops.com)!

* Chat. A lot of people in the open-source world find IRC (often on [freenode](https://freenode.net)) useful, and a lot of companies use team chat like [Slack](https://slack.com). Probably a good idea to become familiar with both models.

* GitHub. As mentioned above, you’re going to want to have a reasonable grasp of git, and it’s a good idea to become familiar with [GitHub](https://github.com). While the "GitHub resume" is ridiculous (because many people can’t open-source their work and don’t have infinite free time), as a student you do have the opportunity to put some of your code out there. And if you want to try forking an open-source repository and contributing something, that will give you conversational material for an interview.
       
* Newsletters. A good place to start is [Gareth Rushgrove](https://twitter.com/garethr/)’s well-curated [devops weekly](http://www.devopsweekly.com).

* Twitter. Not just useful for letting your apps be spammy or following your favorite public figures. In fact, I’d recommend making it your professional face. Tweet like it could be read by your next hiring manager (because it probably will be).

* Blogs. Lots of them out there. Start with Etsy’s [Code as Craft](https://codeascraft.com), and you’ll also find great stuff on [SysAdvent](http://sysadvent.blogspot.com). And if you follow interesting people on Twitter and read DevOps Weekly, you’ll find plenty of blog posts to read.

* Link aggregators. Reddit and Hacker News are popular at the moment. I find the comments to be of highly variable quality, and the content usually shows up on Twitter first, but you may want to at least be aware these exist. (Protip: if you’re going to be linked from the front page of Hacker News, read up on the [Slashdot Effect](http://en.wikipedia.org/wiki/Slashdot_effect) and take precautions. [GitHub Pages](https://pages.github.com) are a free and simple way to have a personal site you don’t have to worry about.)

* StackExchange. You’ve probably used this to help with homework, but now you could consider using the free time you have as a student to answer some questions on there. You’ll help others, and it may also be a good way to showcase an area you understand well. (Note: I do not do this myself; however, I know folks who do, and who find it rewarding. I’m told there’s also a [decent jobs board](http://careers.stackoverflow.com/).)

**Career**

_Finally_, you’re thinking. Maybe she’s going to answer my _actual question_. I left this for last because the other stuff is what’s going to make the most difference. Finding a fancy way to discuss your greatest strength & weakness is a waste of time. Recruiters will start circling, but you will probably find that you’re more engaged and interested when talking with people you’ve met about opportunities you’re passionate to pursue. 

* LinkedIn. Make an account. Connect to the people you know. Copypasta your resume onto there. It’s a fine way for folks to get an idea of whom to ask about you. Beware the recruiterspam and endorsements of dubious value. (I’m endorsed for "awesomeness". Seriously. Amusing, but not useful.) 

Turn off the InMail if it becomes aggravating, but keep connecting to the people you meet. (Don’t do that annoying thing where you let LinkedIn spam your entire contact list, though. Write personal notes to each person if you’re sending out contact requests.) 

The more people you meet, the less you may like LinkedIn, but it’s still a great way to help others by displaying your connection graph.

* Recruiters. Take five minutes and watch [Pete Cheslock](https://twitter.com/petecheslock/)’s Ignite talk [Recruiting Is Broken](http://vimeo.com/79377825). And then, resolve to take the time to meet people in your field yourself. You don’t need recruiters for that.

* Resumes. GPA! Nifty interests or hobbies making you stand out! Your degree being in the exact right thing! Keyword filters that want JavaScript and you only listed Node.js! Yadda yadda yadda. A resume is a tool used to screen people before they talk to the hiring manager. Meet and talk to the hiring managers on your own, and they might want your resume for the files. Eventually. After deciding they want to hire you.
 
* Interviews. Don’t stress out. It’s going to be fine. Do not forget that an interview goes both ways. Make sure _you_ ask questions that show you are interested and curious. Read about the organization and have specific questions about their current projects or place in the market. Protip: you’ll likely have more fun in the revenue-generating end of the business, not in a department that’s viewed as a cost center.

Ask questions about the tech environment like "where are your most painful areas of technical debt" and "can you run me through what your deployment process looks like" and "which [SPOF](http://en.wikipedia.org/wiki/Single_point_of_failure) scares you the most"?

It’s very likely that instead of just the hiring manager, peers will also be interviewing you. They will be attempting to decide if a) they want to interact with you daily and b) you will have a net-positive effect on their lives. You should talk to them and answer the same questions for yourself.

And if anyone asks you to solve fizzbuzz or how many golf balls fit in a school bus, and you can’t stop rolling your eyes, you probably won’t be very happy together. :)


**TL;DR:**

By this time (if you’ve read this far), you’re thinking, "Are you fucking _kidding_ me? I have final projects, and exams, and internship stuff. When I am going to do all this additional homework you just laid out for me?!?!"

Don’t panic. This is less a to-do list and more a set of resources; think of it as stuff to check out while you’re home for the holidays, after you run all the family’s software updates. It’s not even a DevOps primer - for that, you could read Matt Stratton’s [DevOps: A Crash Course](http://www.mattstratton.com/tech/devops). He links all the contextual stuff that I’ve not covered in an acceptable amount of detail during this whirlwind tour. 

In short: if you want to do the devops-y stuff I do, trying out some subset of the ideas in this post is as good a place to start as any. Cheers, and do let me know how you get on!

_(If you’re wondering about the title of this post, it’s a play on Psy’s line that "[oppa](http://seoulistic.com/korean-culture/what-it-means-to-be-oppa-unnie-hyung-noona-older-in-korea/) is gangnam style". Because hey, [hallyu](http://en.wikipedia.org/wiki/Hallyu) is awesome. And for folks who want to work with me at a super-fun international streaming video site, check out [DramaFever](http://www.dramafever.com/company/careers.html.))_
