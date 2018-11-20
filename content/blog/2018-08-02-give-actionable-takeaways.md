+++
title = "give actionable takeaways"
date = "2018-08-02"
slug = "give-actionable-takeaways"
featured_image = "/images/kitties.png"
Categories = []
+++

Cutting right to the chase: those selecting talks for a conference want to know, what’s in it for their attendees? If your talk proposal lays that out clearly, it increases your chances of being selected to speak. So for every talk proposal, make sure you can articulate what your actionable takeaways are. But! Lots of other stuff goes into getting on that stage; let’s talk about it.

<!-- more -->

#include \<std_disclaimer.h\>

I’ve spoken at a bunch of conferences, been on the program committee for several, and helped revise the talk proposals of other speakers a number of times, often resulting in talk acceptance. This advice works (for some values of “works”) for me and some other people, while you may have experiences that intersect but don’t overlap 100% with my opinions - and you are probably right, for your use cases! Pull requests accepted. For example, Sarah Drasner gave me a link with [more talk-abstract-writing recommendations](https://marcysutton.com/writing-winning-talk-abstracts/)!

<br>
**Meh vs Shiny**

Some topics do well one year (seemingly appearing on every conference program) and less well the next (garnering “seen it” comments). Hype cycles and trendiness are real, and program committees aren’t immune. (And yes, I totally have given a talk called “Ops in the time of serverless containerized webscale”. Meta is funny!) This also means this is gameable, to a point. Inserting contradictory buzzwords isn’t going to help, though. It is a good idea to look at the event’s website and see what they say they want right now, and see what tracks they are running this year or featured in past years. 

The right degree of focus - resolution, if you will - is related to whether you’re proposing a talk to a single-track or multi-track event, and if the event has a highly specific focus. In an infrastructure-focused event, if there is a “containers” track separate from the “k8s” track, maybe your Istio deep dive will do well there. In a single-track event, organizers might refrain from the highly specific deep dives that can work in a multi-track event.

If there isn’t an obvious place for your talk to land, it can be harder to program it (especially if track chairs are programming each track without really consulting each other, and each thinks your talk belongs elsewhere). And keep in mind that the plural of anecdote isn’t data; you want to make it clear why you’re the right person to talk about something, so don’t make your talk too specifically about one use case that might not apply to many attendees.

If the event had a lot of emphasis on a specific topic in the past, the organizers may be over it (even if their attendees aren’t). While you don’t want to propose something you don’t want to talk about, you want to [skate to where the puck’s going](https://en.wikipedia.org/wiki/Wayne_Gretzky#Early_years): especially as an experienced speaker, you’ll want to tailor your focus area to what’s new and what’s next.

<br>
**Focus and Scope**

Talk proposals are quite often unclear on focus and scope. If I’m reading hundreds of proposals, I’m going to upvote the ones that don’t [bury the lede](https://en.wiktionary.org/wiki/bury_the_lede), that are scoped properly, where it sounds like the speaker will deliver something of value for the attendees.

Some talk submission tools let you submit the same abstract to multiple events. I’d encourage you to consider customizing if the events differ in scope and audience. Think of it as customizing your intro email to someone you want to hire or introduce to a friend’s org. That’s going to be a lot more appealing than a generic recruiterspam, right? And a description that promises attendee interaction mid-talk will play a lot better when the event organizers expect 50 people in your room rather when they expect 300; instead of asking “can you adapt this for a different-sized audience” they might just move on to a proposal that already seems better suited to their needs.

And remember, a 30 minute talk with 300 people in the room will take up 150 person-hours of time. You want everyone in that room to feel like their time was spent well, and that means you gave them something they can use. Maybe you’re informing, maybe you’re inspiring, but your approach to the topic should be centered around them, not yourself. The people selecting talks will notice this.

<br>
**From Curated to CFP**

So, who’s selecting these talks, and for what sort of event?

Speaking at first-party events differs when your employer running the event (in which case you may be voluntold a) that you’re speaking and b) about what!) or if you’re appearing at a second-party event in support of a partner/customer/etc (in which case you’re probably selected as a speaker based on affiliation and/or specific tech).

But sometimes you may want to speak at a third-party event unaffiliated with your employer or its direct business concerns. How does that kind of talk selection work?

Some events are curated and operate by invitation. Those invitations usually are mostly going to happen if you’ve already given some public-facing talks, so let’s focus on the kind of events where you can apply to speak. (Realistically, many events will feature a mix of talks selected by various mechanisms!)

The program committee are often volunteers from the relevant tech communities. They will read the submissions, vote on them, and in some cases select the talks to form a specific track they are running. Every time I review proposals and upvote wonderful ideas from people I know will give a great talk, there are tragically more talks than time slots. Disappointment all ‘round, but don’t take it personally! Just submit sessions next time! (And please don’t harangue the program committee for a justification of their decision; it’s not constructive and may backfire for the future.)

Note that if you submit more than one talk proposal, you may be surprised in the other direction if more than one gets accepted! It is completely fine to pick and choose which one to ACK. You don’t have to give multiple talks! Recently I gave a three-hour workshop on the pre-conference day and then gave the opening keynote the next day; that sort of context switching requires a lot of energy, and I wouldn’t recommend doing it frequently.

<br>
**CFP details (AKA what even are all these things?)**

Some events run a “call for participation”, also known as a call for proposals or a call for papers.

Don’t worry; you do not need to write a “paper” for a typical tech industry event! You are writing a talk title and talk description, and sometimes other explanatory detail, so as to help the event organizers know if your proposed talk is a good fit for their event.

You are enough. You do not have to be the world’s greatest expert to talk about a topic. Don’t rule yourself out because you feel like you don’t meet some imaginary standard; the conference organizers may really want a case study from a first-time user of a specific tech stack.

You can totally speak at an event you haven’t previously attended! Of course, attending gives you a window into the topic and the participants, but you can also look at past programs and read blog posts and tweets about the event.

The conference may hold a separate call for keynotes, workshops, Ignites, or other things that aren’t the regular conference talk slot. They may be hand-curated. They may be in some cases a placement as part of a sponsorship. And your conference chairs might be in the front row of selected sessions, scouting for their next year’s keynotes.

What should go into your talk proposal to make it as appealing as possible? Let’s talk about some of the typical items a CFP will ask you to provide.

***Title***

At a multi-track event, the title will help attendees quickly choose the session most relevant for them. Good titles are guideposts to the differentiators between talks.

An example of a talk title I used which was accepted: “Docker in Production: Reality, Not Hype”. Just by looking at the title, an attendee can guess that I’ve probably done this thing, and that my perspective probably isn’t all marketing fluff.

And one proposed talk title of mine that was rejected: “Scaling on a Shoestring”. I intended to talk about controlling our AWS spend with the use of autoscaling and spot instances, but it wasn’t clear from the title what the talk would be about. I could have called it “Keep Your Cloud Bills From Autoscaling to Infinity” and it may have been more appealing.

Or maybe not, because I proposed it to a relatively expensive conference with a focus on larger scale. If companies could afford to send their employees there, they probably wanted those employees focused on topics more relevant to their use cases. That doesn’t mean that would be a bad talk in all circumstances; it means it wasn’t right for that specific event and audience.

Reading the titles for talks that event has featured in the past should give you insights into how specific they tend to be, if they tend to contain puns, and the like. There isn’t a “right” sort of title, but there is definitely a “too long for their field length” title, so you probably want to avoid complete sentences.

***Description***

The description (also known as “abstract”) is where you go into more detail about what your talk is about. Some events will ask for a shorter and also a longer form of this. You’re safe in assuming that they will publish whatever you put in this field. (They hopefully will talk with you before editing it on your behalf, but be prepared for that to be necessary, because sometimes what you put is too long or not exactly the right focus.)

Knowing your audience allows you to focus the description on them - on what they’re there for, not just on yourself and your organization. Here’s a sample description that you might write:

“We use tool X and tool Y. We have N monthly active users. We also are awesome for reasons P and Q.”

I’m reading that and going, “yeah, great, and…?” The most typical complaint from program committee reviewers is that a talk description lacks sufficient detail. The reviewers are trying to make sure the talk is a good fit, and if they don’t have enough information, the default answer is going to be “meh”. 

Think of it like this: the audience is looking for themselves in your description. Why did you use tool X and Y but not the ever-popular Z? What can they glean about your org’s reasoning that helps them see if this is a pattern they should match? Your vanity metrics aren’t telling them how fast this growth happened or if you had to re-architect multiple times. You mentioned some results, but they can’t tell if you traveled a similar journey to them along the way; instead, say a bit about your growth, your decision-making, and what problem you were trying to solve.

Here’s a rewrite of that description:

“When we saw our monthly active users were growing exponentially, we realized that tool S plus tool T, which had gotten us this far, wasn’t going to keep scaling. We examined W and spent several months evaluating Z before rebasing on X and Y; we’ll talk about the tradeoffs for us. We’ll talk about how the P and Q in our culture reinforces and is guided by our tool choice process and implementation. You’ll leave better able to recognize tradeoffs in the X through Z space.”

Much better with those details! Nobody has a goal of doing exactly what you did (because, um, you already did that thing). They want to be awesome themselves in their own endeavors, so it’s good if your talk proposal helps the organizers see how your talk does exactly that. Don’t just talk about what you did. Talk about why, and talk about what you learned.

And yes, your colleagues are the ideal people to help you rewrite your descriptions and make them punchier!

***Video***

If you can link to a video of yourself talking on a similar topic, that can help organizers decide that they want you on their stage. Here’s how to get such a video before you speak at a conference:

- Speak at a brown-bag session or other recurring event your employer hosts
- Check meetup.com for relevant local meetups. Attend them, and talk to the organizers about letting you give a talk or even a “lightning talk” at their next session. (This means you would give a short talk - perhaps 5 to 10 minutes long - before their next scheduled talk.) Pre-gaming your talk at a meetup is a good plan in general, if you can swing it!
- Give a heartfelt explanation to your cat, dog, or goldfish, with your phone as (recording) witness.

You want video because a conference is not a collection of technical blog posts. Organizers realize that being able to write an appealing talk description does not mean that you will be able to speak aloud about it in front of other humans. Seeing you on video gives the organizers a bit more confidence in putting you on stage in front of their attendees.

Note that this video doesn’t need to have super high production value. Hand your phone to a friend and have them record you speaking!


***Bio***

The purpose of the bio is to say a little about yourself and where you’ve studied, worked, volunteered, and participated in the community. Depending on the conference site, space is usually limited. One or two short paragraphs is probably fine; think “summary” more than “exhaustive list”.

You’re answering the question “why would an attendee want to see this person talk about this topic”, not giving your entire CV. It’s fine to mention the last few places you’ve worked or projects you’ve contributed to; it’s probably out of scope to mention your opinions of every single techie thing on the planet (though one or two fun facts can’t hurt).


***Picture***

The picture of your face (also known as headshot) helps the event in promoting your talk ahead of time, and helps audience members recognize you when walking around at the event. Do not use a picture of your pet or a picture of yourself when you were a kid or that great far-off silhouette shot from hiking the Grand Canyon. All those pictures are delightful, but are also less than useful for this specific purpose.

You do not need to have a posed professional shot here (although once you get to the conference, they sometimes offer that as a perk). My current headshot and the one I used before that were both taken at restaurants by my dinner companion. You do want it to look reasonably like you look currently (especially as it’s weird if your hair or glasses change lots, and the conference tries to do some art that features your previous look).


**How? What? How? Three excellent questions.**

**Expect the Unexpected**

Sometimes you may propose a three-hour workshop and get slotted into a 35 minute talk instead (this may have in fact happened to me this spring!) - this is an opportunity to get creative. Be flexible; you may surprise yourself! If a conference asks you to change something, you can always say no, but if you want the opportunity, you may sometimes need to give a slightly different talk than you’d expected! (They should give you plenty of advance warning, of course!)


**On Multiple Speakers**

My first conference talk was co-presented with a colleague, and I love co-presenting to this day. (It’s a great way to feature a friend or colleague!) However, a multiple-speaker presentation works best when the speakers interact. Yes, that is more work. It’s also worth doing, and it’s also worth mentioning in notes to the reviewers so they don’t automatically downvote the multi-speaker talk on that basis.

Conferences will often be rightfully skeptical of “customer plus vendor” because they tend to be “enthusiastic endorsement” followed by “heavy-handed pitch”. And even if it’s co-workers, splitting the time can just mean the attendees get two shorter related talks instead of one full-length one. And the worst is “let me shoehorn in a co-presenter from an under-represented group so I can tick that ticky box”. _(Narrator: we can tell when you’re trying that.)_

If you’re going to have multiple speakers, the whole should be more than the sum of the parts - it should be an interactive talk where the audience gets more out of it than they would have gotten from a single speaker on that topic.

**What about “blind” review?**

I’ve [written about “blind” review at length](https://bridgetkromhout.com/blog/in-the-kingdom-of-the-blind/). The [teal deer](https://knowyourmeme.com/memes/tldr) version is that “blind” review doesn’t solve the actual problem of representation on tech stages; it’s basically diversity theater. Fight me! (Okay, the less confrontational view is that removing the identifying info from a homogenous pool doesn’t magically add diversity to the mix.)

That said, if an event is choosing “blind” review, definitely don’t include your name/rank/serial number in the talk description, as it will vex the organizers if they have to redact sections of your talk description before it goes to the reviewers.


**Language to Avoid**

It’s possible that those selecting talks are similar to you, with similar perspectives and viewpoints. However, it’s equally possible that some phrases you take for granted may be unappealing to the reviewers. For example, I work for a little startup out of Redmond that you may have heard of. We already operate at a disadvantage in some MSFT-skeptical circles, so we need to be even more careful about any accidentally negative impressions.

Avoid calling anything “obvious” or anyone a “thought leader”. Your target audience isn’t limited to “guys”, and your favorite tech isn’t shown in its best light by you bashing other tech choices. You don’t want to land in the “nope” column just by virtue of sounding like you don’t know people-not-you exist in the world! And be cautious about jargon turning into acronym soup; if a reviewer has to use Wikipedia’s disambiguation page at any point, they are going to wonder how clear your talk will be.

**What will it take to get you into a late-model cloud today?**

Vendor pitches have their place (usually in the product announcements on the keynote stage of your first-party event), but usually a third-party event is super not-gonna-be-interested in something that’s clearly a sales pitch for your employer’s products. A dead giveaway for this is when the talk is proposed by the marketing department, promising a speaker who’s a different employee at the company. Those proposals operate at a disadvantage because the selection committee will be rightfully skeptical as to whether the proposed speaker has even seen the talk description! (Once I reached out to a friend because of a severely out-of-character and “meh” talk proposal - turns out he didn’t even realize it had been submitted on his behalf!)

Along those lines, third-party conferences often will consider speaker substitution to be a Very Big Deal (where it would be completely fine and expected for your internal roadshow or company conference). The third-party event may be trying to balance experience levels, demographics, or any manner of other factors in their programming, so if a talk gets accepted, and you commit to doing it, don’t assume you can swap in a colleague without it being a whole discussion. Like, swapping in your colleague might be super, except the conference organizers don’t want her speaking in the same time slot as one of her collaborators on an open source project (and that might not have been a consideration for you!) - so you do need to discuss it with the conference, not just swap speakers and assume it’s #probablyfine.

When talking with my co-workers, I say this: if you want to talk about something related to your work (and often we do! Since, you know, job!), it’s good to de-emphasize the Microsoft angle (like Anil Dash describes in [Dev Rel must be provided with a clear distinction from sales engineering](https://medium.com/glitch/dev-rel-must-be-provided-with-a-clear-distinction-from-sales-engineering-3ba17a4cda4f)) and emphasize that your talk is about open source. If there’s a separate area for notes to reviewers, you can clarify that although you work for a vendor, you will have actionable takeaways for people who aren’t using your specific products - you’ll cover higher-level themes and principles with broad applicability. (If this is not yet true, make it be true, because that’s key to getting accepted by events that aren’t picking you specifically for your employer.) It may not be fair that other companies can slather their names all over everything and we can’t get away with it, but that’s the reality on the ground today.

**How do you get to Carnegie Hall? Practice!**

If you can give an early version of your talk to a smaller-scale audience, it can help you make it better. Sure, start with pets, family, and colleagues, but eventually you have to talk in front of strangers.

An ideal situation is a friendly local meetup where you’ll be providing content the attendees will appreciate, and where you feel comfortable handling Q&A. If you tell the attendees that they’re getting a sneak peak of conference material for free, and they can help you refine it by their questions, then you’ll usually get questions that help you sharpen and clarify the material before you give it to a larger (paying) audience.

I was rehearsing a [talk version of this blog post](https://www.slideshare.net/bridgetkromhout/give-actionable-takeaways) with my spouse [Joe](https://twitter.com/joelaha/) and he added, “And meetups are always looking for speakers! If they don’t have a speaker, they have to have a panel with some other meetup organizers for the umpteenth time.” I resemble that remark!


**Closing the Deal**

Let me explain. No, there is too much; let me sum up. You want to be on stage. How can you improve your chances?

***Flawless mechanics***

- Check those details and have colleagues peer-review before you send in the proposal.
- Use crisp language, including everything required, and keep the scope well-defined.

***Audience awareness***

- Know what the organizers themselves want; make sure your topic is definitely right in their wheelhouse for this specific event and in general don't be a pain to the organizers. Yes, sure, you are a special snowflake... just like every other potential speaker they’re dealing with! You want to make the organizers’ lives easier, not harder.
- Include details to help attendees read your description and see themselves being awesome; remember that it’s not about you - it’s about them.

***Actionable takeaways***

- Explicitly state what the benefit to the audience will be.
- There should be no question of “do we want this talk?”, but rather “where are we going to fit this talk into the schedule, because we need it!”


<i>fin</i>

<i>Thanks to [Nina Zakharenko](https://twitter.com/nnja), [Sarah Drasner](http://twitter.com/sarah_edo), [Scott Cate](http://twitter.com/ScottCate), and [Tim Gross](https://twitter.com/0x74696d) for their thoughtful feedback as I wrote this. All mistakes, opinions, and hot takes are my own.</i>
