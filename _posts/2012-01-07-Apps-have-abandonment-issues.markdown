---
layout: post
title: Software abandonment (& how to avoid it)
category: design
image: software_abandonment_issues.jpg
alt: Software abandonment issues
---

Customers ditch a company or its products for all sorts of reasons. Sometimes an app is broken or outdated, or has terrible support.<sup>[<a id="footnote-1-ref" href="#footnote-1">1</a>]</sup> Sometimes a company affiliates with something that customers find offensive.<sup>[<a id="footnote-2-ref" href="#footnote-2">2</a>]</sup> Boredom might be the saddest reason for software abandonment. Addressing your boring software is not only necessary to keep customers, it can transform disinterested users into a body of happy, habitually returning customers.

Behavioral psychology, flow theory, and game theory provide testable principles for cultivating habitual use of software. This is an exploration of a few of those principles and some guidelines to encourage customers to not only stick with your software, but to derive pleasure from its use.

## Cultivate new habits
We are creatures of habit who routinely eat the same foods, wake up at the same time, and gripe about the same things to the same people.<sup>[<a id="footnote-3-ref" href="#footnote-3">3</a>]</sup> To keep your customers returning, your software must present tasks that encourage habitual use. The habit of using your software fosters the habit of returning. As you refactor or develop new features, be an enabler. Consciously create habit-forming interactions between the customer and your software through operant conditioning.<sup>[<a id="footnote-4-ref" href="#footnote-4">4</a>]</sup>

Positively reinforcing users as they interact with your software conditions them to expect to feel good when they use it. They will crave more time with your software when their expectation to derive pleasure and happiness is met with reinforcement and rewards. 

<a href="http://commendablekids.com">Commendable Kids</a>, a 2010 Rails Rumble finalist, demonstrates a fine example of positively reinforcing habit-forming user experience through the use of badges. Taking cues from the Boy Scouts of America, the app encourages kids by guiding their behavior with a simple badge-based rewards mechanism.  I asked one of the app's creators, Brian Burridge, why he chose to make badges a central mechanism of the app. He said:

> The desire to receive symbols of achievement has been one I've observed over both my 14 years of being a parent and my 20 years in martial arts, with both children and adults working diligently toward that next belt level.

Every good deed, skill, or accomplishment is rewarded by unlocking a badge that can then be shared with friends and family. That's why the app works so well at driving its users back to Commendable Kids. The authors of Game-Based Marketing say of badges:

> Often represented visually, badges show that players have completed specific tasks. The badge’s value is a powerful and fundamentally social game mechanic. While society generally discourages personal claims of accomplishment like bragging, badges allow boasting without being obvious.<sup>[<a id="footnote-5-ref" href="#footnote-5">5</a>]</sup>

Badges are just one way to positively reinforce behavior in software. Implementing a badge mechanism in your app is a great way to encourage habitual use, but consider those interactions that you want to reward. The behavior that you want to be habitual is that which should be rewarded and, as the authors of Game-Based Marketing point out, "The underlying drive to keep playing based on a belief that you will someday win those rewards is exactly the type of motivation that gives loyalty programs their power." When you cultivate new habits by reinforcing behavior, your customers will return to your software, not just by rote, but because it feels good to keep coming back.

## Cut a clear path
Conditioning a rat to tap a pedal for a food pellet is one thing, but cultivating complex habitual behavior in humans requires testing, logging, and a series of successive approximations. B.F. Skinner, who developed the theory of operant conditioning, referred to this process as shaping.<sup>[<a id="footnote-6-ref" href="#footnote-6">6</a>]</sup> If the behavior that you want to cultivate into habits is complex, then you must shape their behavior in steps over time.

Condition your customers into complex behavior with a series of steps to get them there. The best way to do this is to iterate over the features you develop in small chunks, deploying often and getting feedback. This keeps you engaged with your customers and trains them toward the final behavior you expect, rather than pushing out a new feature which is repellant because of its complexity. Be patient. Habits take time to create, and the more complex the behavior, the longer it takes to solidify that behavior into something habitual. Author and behavioral psychologist Susan M. Weinschenk, Ph.D., writes:

> If you want people to commit to something big, you first need to get them to commit to something that is related, but very small. This changes their self-persona, which opens the door to larger commitments. When people form a habit, they are essentially making a new commitment. Choose something small for them to do first and then you can build a bigger habit and commitment later.<sup>[<a id="footnote-7-ref" href="#footnote-7">7</a>]</sup>

All of this talk of training and conditioning may seem controlling, but remember that people not only need guidance, they like it. Your customers don't want to think about the best way to accomplish a task; it is your job as a developer to present them with the best way. Robert Hoekman, jr., in Designing the Obvious, suggests becoming familiar with the user's situations and focusing on the problems that users are trying to solve. He says:

> You can't ask users outright what they want. You get theoretical answers. You don't get the answers that result from real choices in real situations. You don't get the truth about how people think and work.<sup>[<a id="footnote-8-ref" href="#footnote-8">8</a>]</sup>

Focus on understanding the situations your users are in when they use your software, then present them with the best way to accomplish their tasks. Understanding their situations and the problems they want to solve should give you confidence to guide them toward a solution that you judge is best for them, which you can confirm through feedback and usage statistics.

## Go with the flow

In the 1960s, Mihaly Csikszentmihalyi, a Hungarian psychology professor, proposed a concept called flow theory. Wikipedia offers a concise definition:
 
> <i>Flow is the mental state of operation in which a person in an activity is fully immersed in a feeling of energized focus, full involvement, and success in the process of the activity.</i><sup>[<a id="footnote-9-ref" href="#footnote-9">9</a>]</sup>

This is exactly the state of mind that your customers should achieve when they use your software. To enable this state of mind, three conditions need to be present. First, they must be engaged in a task that has clearly defined goals and benefits. Second, the task must be challenging enough to engage, but not so challenging that they feel frustrated  and unable to complete it. Finally, the task should be giving the user constant feedback.<sup>[<a id="footnote-10-ref" href="#footnote-10">10</a>]</sup>

A team of computer science students at Columbia University propose an approach to software development that they have named HALO (Highly Addictive, sociaLly Optimized) Software Engineering. This approach uses operant conditioning and flow theory to create a competitive/collaborative software development environment. In their paper, they use the principles of flow theory to structure this type of environment, the goal of which is to achieve a high level of focus and involvement in the software development process. The principles from which they draw are the same that you should consider for your application.  In their background, they state:

> To gain this high level of involvement, participants must have a clear set of goals that are challenging and require skill, have immediate feedback, and be utilizing their entire concentration.<sup>[<a id="footnote-11-ref" href="#footnote-11">11</a>]</sup>

They cite the work of Finneran and Zhang around flow theory and flow states of people while they use computers, making the observation that there "must be a fit between the participant, artifact (i.e., tool), and task."<sup>[<a id="footnote-12-ref" href="#footnote-12">12</a>]</sup> Reducing unnecessary page loads, clicks, and obstructions to completing tasks in your software reduces the amount of thinking your customers have to do to accomplish their tasks. Make the most important tasks in your software the most obvious, then make them the most effortless.

## One is the loneliest number
As a developer, it can feel defeating to see the number of users of your software diminish. Attracting new customers takes a lot of work and keeping them returning takes even more. But instead of making customer retention your sole motivation, focus on developing features because they improve the lives of your customers in a meaningful way. Nothing alienates the very customers you're trying to keep around like desperation. And, as developers of abandoned software know well, customers find other things to do with their time when there's not a constant reason to return.

If you're looking for the short answer, it's this: your customers will not abandon your software if they are in the habit of using it, and habits don't come by chance. You can cultivate habitual use by careful observation of the most important tasks your users need to accomplish. If you understand the situations your customers are in when they're accomplishing tasks in your software, then you're on the right track. Use this understanding to identify the most important tasks and make them the most obvious. Create habits for your customers that keep them coming back to accomplish those tasks. Then, display a measure of these accomplishments as progress toward longer-term goals. It's not magic, it's science.

<hr />

<sup id="footnote-1">1</sup> An alarming example of a customer support train wreck is Ocean Marketing's Paul  Christoforo responding to an inquistive customer about why he hasn't received any information about a purchased product. The entire email exchange was published at <a href="http://penny-arcade.com/resources/just-wow1.html">Penny Arcade</a>. <a id="footnote-1" href="#footnote-1-ref">&#8617;</a>

<sup id="footnote-2">2</sup> GoDaddy's CEO, Bob Parsons, in the span of a single year, has managed to offend a stunning number of its customer base, first with video footage of his elephant hunt, and more recently GoDaddy's support of SOPA. <a href="http://gawker.com/5870851/has-godaddys-elephant+killing-ceo-finally-gone-too-far">Gawker</a> is a good jumping off point for more information. <a id="footnote-2" href="#footnote-2-ref">&#8617;</a>

<sup id="footnote-3">3</sup> In 2008, scientists tracked the movement of 100,000 people using geo-locatable data from their cell phones. The patterns of movement they tracked were so habitual that they could "obtain the likelihood of finding a user in any location." <a href="http://www.nature.com/news/2008/080604/full/news.2008.874.html">Nature</a> published the research.<a id="footnote-3" href="#footnote-3-ref">&#8617;</a>

<sup id="footnote-4">4</sup> I haven't come up with any real use for negative reinforcement, or punishment, in software. At least not any that I'd use. Maybe one day there will be books like <a href="http://www.amazon.com/NurtureShock-New-Thinking-About-Children/dp/0446504130/ref=sr_1_1?ie=UTF8&qid=1324606843&sr=8-1">Nurture Shock</a> condemning too much reward and positive reinforcement in our software, rather than our parenting. Until then, never, ever punish your customers. <a id="footnote-4" href="#footnote-4-ref">&#8617;</a>

<sup id="footnote-5">5</sup> Linder, Joselin; Zichermann, Gabe (2010-03-09). Game-Based Marketing: Inspire Customer Loyalty Through Rewards, Challenges, and Contests (p. 75). John Wiley and Sons. Kindle Edition. <a id="footnote-5" href="#footnote-5-ref">&#8617;</a>

<sup id="footnote-6">6</sup> Visit the <a href="http://en.wikipedia.org/wiki/Shaping_(psychology)">Wikipedia article</a> for a brief overview of complex behavioral training through shaping. <a id="footnote-6" href="#footnote-6-ref">&#8617;</a>

<sup id="footnote-7">7</sup> Weinschenk, Susan, Ph.D (2011). 100 Things Every Designer Needs To Know About People (p. 140). New Riders. <a id="footnote-7" href="#footnote-7-ref">&#8617;</a>

<sup id="footnote-8">8</sup> Hoekman, Robert, j.r. (2011). Designing the Obvious: A Common Sense Approach to Web & Mobile Application Design (p. 57). New Riders. <a id="footnote-8" href="#footnote-8-ref">&#8617;</a>

<sup id="footnote-9">9</sup> Definition taken from the <a href="http://en.wikipedia.org/wiki/Flow_(psychology)">Wikipedia article on flow theory</a>. <a id="footnote-9" href="#footnote-9-ref">&#8617;</a>

<sup id="footnote-10">10</sup> Csikszentmihalyi, M.; Abuhamdeh, S. & Nakamura, J. (2005). Flow, in Elliot, A., Handbook of Competence and Motivation. (pp. 598–698) New York: The Guilford Press. <a id="footnote-10" href="#footnote-10-ref">&#8617;</a>

<sup id="footnote-11">11</sup> Quoted from <a href="https://mice.cs.columbia.edu/getTechreport.php?techreportID=1457&format=pdf">HALO (Highly Addictive, sociaLly Optimized) Software Engineering </a> (2010). <a id="footnote-11" href="#footnote-11-ref">&#8617;</a>

<sup id="footnote-12">12</sup> Christina M. Finneran and Ping Zhang (2002). <a href="http://melody.syr.edu/pzhang/publications/AMCIS02_Finneran_Zhang.pdf">The Challenges of Studying Flow Within a Computer Mediated Environment</a>. <a id="footnote-12" href="#footnote-12-ref">&#8617;</a>

