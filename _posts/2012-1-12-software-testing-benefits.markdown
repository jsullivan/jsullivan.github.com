---
layout: post
title: Software testing - are the benefits mythical?
category: development
image: unicorn.jpg
alt: Software testing benefits
---

I read a <a href="http://www.simple-talk.com/dotnet/.net-framework/unit-testing-myths-and-practices/">post recently</a>, sent from a co-worker to our entire engineering team that made a number of invalid assertions about testing, mostly the costs of unit testing. The most fallacious was that the benefits of unit testing are mythical. Normally, I would not respond to a post of this nature because the premise is invalid. However, given the amount of views and positive feedback of the post, I felt compelled to respond with some actual evidence to help shed light on the actualities of the subject.

## Unit testing needs a cost/benefit analysis

One of the assertions that Mr. Fischer makes is that unit testing needs to be evaluated from a perspective of cost of development, or the additional time it will take to deliver value when writing unit tests. Debating this point is nonsensical, because those who still believe that unit tests take additional time have never truly adopted testing as part of their development process. Initially, as does learning any new concept, it will add time to your development cycles. This is absolutely true. Is this really uncommon though? Does it not take additional time to introduce new technology into the architecture? It most certainly does, but that does not stop teams from doing so. I used this example because it helps to illustrate the fallacies in measuring unit testing by the time they add to development. In order to do this, you have to assume that unit testing is always going to add additional time. Just like with that new technology, it will be difficult at first, but that will subside as you get more familiar with the tool. C# was difficult for me to learn to program in at first. However, as I wrote more and more code in C# I became more and more efficient until I left the .Net landscape for greener pastures. Testing is no different. Once you learn the concepts behind testing you'll become just as proficient as you are with that new piece of technology to which you you recently upgraded or switched.

Since the benefits are difficult to grok for those who haven't experienced them, I want to illustrate a real, documented cost of software. Lehman suggested two very important laws in a 1985 publishing:
 
> A computer program that is used will be modified. When a program is modified, its complexity will increase, provided one does not actively work against this.<sup>[<a id="footnote-1-ref" href="#footnote-1">1</a>]</sup>

The second point is what we need to focus on. So what exactly is complexity? And what does “one actively working against this” mean? In most cases, complexity is measured by the cost of change. How long does it take to understand this code? How long does it take to fix a bug in this code? How long does it take to enhance this code? These are all questions that can identify the cost of change. There is also an intangible piece to this puzzle: how frustrating is it for a developer to enhance this code? How deflating is it for a project manager to wait twice as long because of a difficult piece of code and a developer frustrated from modifying the difficult piece of code? In an extreme case, how was the business affected by not getting to market quick enough? What does it cost when your system has begun to rot?<sup>[<a id="footnote-2-ref" href="#footnote-2">2</a>]</sup> How is expensive is your code as its complexity grows over time and becomes more brittle?<sup>[<a id="footnote-3-ref" href="#footnote-3">3</a>]</sup>

Another way to look at this is as a cost of maintenance. What does your software cost your company to maintain? Let's characterize maintenance on a project. Maintenance requires you to: 

1. <b>Prevent</b> – increase maintainability for the future
2. <b>Adapt</b> – adapt to changes in the software environment (technologies, upgrades, etc)
3. <b>Perfect</b> – accommodate new or changed requirements by enhancing the software
4. <b>Correct</b> – deal with errors found by fixing them

Consider a survey of 487 companies conducted by Lientz and Swanson in the late 70's that concluded, of these categories, 50-85% of life cycle costs on a software project were incurred in maintenance.<sup>[<a id="footnote-4-ref" href="#footnote-4">4</a>]</sup> Of that percentage, 21% of the costs were spent on fixing errors. This is yet another real cost of development that testing can greatly reduce. Despite the survey having been performed long ago, I think it mostly holds water in terms of maintenance costs and bug costs. Perhaps that will change in the next decade once nobody feels testing is anything other than a critical component of any application.

These are all real questions that become much more evident as the complexity of your application grows. They represent some of the tangible costs of a software project, not lagging for a few weeks while the team learns how to effectively test their application. Testing also resolves the majority of these issue by demanding a looser form of coupling resulting in higher cohesion thus higher quality software and/or the interaction of multiple software systems.

## A culture of quality

Another related aspect of testing is the culture of quality that testing usually brings along with it. Despite the subjectivity, a culture of quality is important for any team to be highly productive. Without it, bugs will be rampant, maintenance will be cumbersome, support will be infuriating, and morale will sink right along with the ship. I've seen firsthand how unraveling a “big ball of mud” can erode a team causing a profound ripple effect felt throughout the company.<sup>[<a id="footnote-5-ref" href="#footnote-5">5</a>]</sup> Distrust and negative feelings can form throughout an organization as the perception grows that the software is being developed rapidly enough, especially in today's world where so many businesses are completely dependent on technology in their daily work.

A fixation on quality champions great software. If you don't agree, please have a look at Apple's success. Building great software takes time, commitment to excellence, ambition, and phenomenal chemistry on the team. Testing is a pillar of quality. Without it you're on unstable ground.

In closing, Mr. Fischer is most certainly right in the fact that testing does take time. What he is wrong about is that unit testing adds time. The wording is subtle but the difference in perspective is enormous. Approaching measuring the cost of development by how long it takes to learn a technique can never yield a reasonable outcome. Measuring the cost of change, or from another view the cost of maintenance, is a much more scientific, provable approach to ascertaining what the investment in a project actually costs.

Testing is a technique, yet it has much more sweeping effects than just another methodology or concept. It can transform the reputation of the software you put out in an unimaginable way if you choose to unlock its power. I like to think of projects with a focus on testing (quality to a larger extent) as handmade solid oak tables. They will withstand the test of time in comparison to a cheap, fake wooden table cobbled together that lasts a fraction of the time.

<div class="guest_writer">
	<div class="guest_photo">
		<img src="/images/tim_linquist.jpg" />
	</div>
	<p>
		<i>This post written by <a href="http://twitter.com/tim_linquist">Tim Linquist</a>. Tim is a Rubyist and software testing evangelist. He's developing a better platform at <a href="http://g5platform.com">G5</a>.</i>
	</p>
	<div class="clearfix"></div>

</div>

<hr>

<sup id="footnote-1">1</sup> Lehman, M.M.; Belady, L.A. (1985), Program evolution: processes of software change, Academic Press Professional, Inc., San Diego, CA. <a id="footnote-1" href="#footnote-1-ref">&#8617;</a>

<sup id="footnote-2">2</sup> Wikipedia provides an entry on <a href="http://en.wikipedia.org/wiki/Software_rot">software rot</a>. <a id="footnote-2" href="#footnote-2-ref">&#8617;</a>

<sup id="footnote-3">3</sup> Wikipedia provides an entry on <a href="http://en.wikipedia.org/wiki/Software_brittleness">software brittleness</a>. <a id="footnote-2" href="#footnote-2-ref">&#8617;</a>

<sup id="footnote-4">4</sup> Lientz, B.P., E.B. Swanson, and G.E. Tompkins. “Characteristics of Application Software Maintenance.”Communications of the ACM, 21(6):466-471, June 1978. <a id="footnote-4" href="#footnote-4-ref">&#8617;</a>

<sup id="footnote-5">5</sup> Wikipedia provides an entry on the so-called <a href="http://en.wikipedia.org/wiki/Big_ball_of_mud">big ball of mud</a>. <a id="footnote-4" href="#footnote-4-ref">&#8617;</a>

