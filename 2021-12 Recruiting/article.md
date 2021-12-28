# Recruiting, an Essay
The topic of recruiting comes up often enough around me that I've started to take a keen interest. Unfortunately, there's a mixed bag of experiences to be found and while I haven't seen enough to call recruiting 'broken', it did set me asking what a *good* recruiting system may look like.[^1]

This is an essay[^2] into recruiting, from an almost clean slate (I've been through the process as a candidate and I've also had to interview people on occasion).

This article is fairly long. Some of you may be time poor, so here's a quick preview of the rest of it:

> **Summary**:
> Placeholder
> Placeholder
> Placeholder
> Placeholder
> Placeholder

Otherwise, I invite you to join me on this meandering journey.

## Intro: A broken system? (WIP)
It's relatively easy to find people having bad experiences with recruiting, and an interested reader can look further into more macro trends [TODO]. Some of the more standout criticisms of the current systems include:

* Introducing various kinds of bias
* Doesn't accurately measure what makes people good
* Causes a lot of distress etc.

Many real problems don't have solutions that satisfy everyone [^3]. Dissatisfaction alone doesn't necessarily mean the system is 'broken', but does raise interesting questions of what a perfect system could look like.

## Why care?
I don't have too many responsibilites relevant to recruiting, I just think the problem is interesting (and fun) to think about. However, there *are* people who do (or should) have more important reasons to care about this (beyond indulging curiosity), especially if they play a key role in an org.

> **Note**: I'll be using the word "org" to mean any organisation, company, team, club, or other collection of people.

Few orgs are static. When an org is growing, people are almost always needed. When someone leaves, replacements are usually needed. This wouldn't be a problem if you could drop in an identical replacement (or one close enough) like replacing a bearing in a machine, but reality isn't that simple.

I've spent my career in knowledge industries, but I've seen this happen even in retail and food: a new person changes the way the org behaves. For most cases, the effects are most strongly felt at the team level but sufficiently senior hires or small orgs can be shaken up by even a single new person.[^4] 

Consider also that many companies (such as consultancies and law firms) operate on an apprenticeship model (on-the-job training). It's common and normal for a good chunk of the most senior people to have worked their way up from when they first graduated. A batch of fresh faces could be dictating an org's future decades down the line.

Any org must balance many competing priorities, of which recruiting is only one. However, an org is nothing without it's people. I think that any decision an org has that affects its people is worth doing well, and worth taking seriously.

## The big picture
Recruiting creates change, and not all change is created equal. My mind drifts naturally to an *optimisation* problem, or how to maximise the tendency for recruiting to benefit the company.[^5]

The above problem statement is, to me, not helpful because it's too low-resolution. However, the following line of thinking was interesting to follow:
* An org carries out *functions* to achieve its aims (e.g. advertise to gain new customers, develop products to sell)
* Within an org, *people* and *groups* interact to carry out the functions. The *way* the functions are carried out can affect the org's aims
* To carry out the functions well, there are *qualities* required from the people and groups (e.g. various skills, diligence, cooperation, and more)

This allows a *slightly* tighter description of the problem statement, namely that recruiting is an optimisation problem to select a mix of people who will (either directly or thorugh interacting with a team) produce the qualities needed for org success. For completeness, this is a *resource-constrained* optimisation problem, as most orgs do not have infinite money (or time, or people) to throw at getting this mix right.

This begs the question, what *are* the qualities needed for org success? I think that this is highly specific to each org (although there may be some generalisations) and even each team. I'd prefer to concentrate on the general case, and will make this assumption:

> **Assumption 1:** An organisation knows (or has a reasonable estimate of) the qualities that are needed for it to be successful[^6]

## Performance
Obviously, getting people to act in a beneficial way is not just a matter of putting the right people in a room together. How does an org get its people to act in a certain way? One way is through culture and norms (a force which I would not underestimate), another way is through instructions and directions delivered via a chain of command.

However, what I think is most powerful is through incentives, rewards, and advancement, typically as a part of performance managmeent and/or various reviews. For now, I am also going to assume that:

> **Assumption 2:** An org's performance management and/or advancement systems encourage people to contribute to the qualities needed for collective success.[^7]

I'm not going to pretend this is easy. However, if an org can confidently say that both Assumption 1 and Assumption 2 are true, that org has a powerful *measurement* tool. Measurement is a key element of control (the other being a mechanism to influence the system) and allows an org to test its own recruiting process.

I propose that the main measure of a *good* recruiting system is how well it predicts good performance (as measured by performance management). Good candidates (as predicted by recruitment) should be good employees (as measured by performance management).

## Measuring success
This was a fairly roundabout way to explore the problem, but I think it's worthwhile. I think that the measurement of recruiting does need to be done this way because the benefits of a recruit don't exist immediately (in fact, a fresh recruit is more likely to be a net *negative* to a team for a short period of time). This is even more true if the position expects significant growth over time (e.g. graduate recruits).

What kind of data might we expect to see? I don't think it'll be entirely realistic to reduce the complexity of a whole person to a single number or data point (although it would be nice). To me, I think some interesting results may come from being able to tell two simple things from a hypothetical measurement:
* That there should be some *relative ordering* of people, even into rough buckets of 10% or so
* That it would be nice to estimate the *magnitude* of difference between people, certainly the gap between the top and bottom of the population

At this point, we're still far from a practical series of steps for a recruiting process, in the same way that the definition of a square root (The square root of X is the number Y such that X = Y^2) isn't actually a method to calculate the square root (e.g. Newton's method). However, we have some useful abstractions to work (a *meta-process*, if you will) with that can get us closer to testing a practical recruiting process.

## Hypothetical results
I mentioned two properties of an imaginary measurement (relative ordering and magnitude estimating) that can be useful. I've got a few test analyses below to show how this data may be used to identify issues within a recruiting system.
 
### Case #1 - systemic mismatch
The thought experiment that started off most of this essay to begin with was the question, "What if mediocre recruits consistently turn out to be the top performers when measured later? What would that say about the recruiting system?"

A graph (made in [tldraw](https://www.tldraw.com/)) showing this:
 
![fig1](/2021-12%20Recruiting/Pasted%20image%2020211228162054.png)
 
Now, some variation might be expected here and there (people's lives are complicated). However, something like a consistent reversal over multiple years would worry me deeply. I would have no confidence in the signal of such a system to predict people who would be helpful to an org. Even if there was no correlation that would likely be concerning if early decisions (e.g. team allocations) were made on the basis of such suspect signals.
 
A final concern here is for those who were not hired as a result of the system. I have no way of knowing whether borderline or poor-scoring candidates (according to the recruiting system) would have been better than actual recruits [^8]. Depending on the type of field, the difference could be catastrophic in terms of opportunity cost.
 
Why does the type of field matter? The next two examples will help show the difference between a narrowing skill curve (over time) compared to a widening skill curve.
 
### Case #2 - narrowing curve
Consider the case where the skill gap between the initial best performers and worst performers narrows over time. As an org, would this worry you?
 
![[Pasted image 20211228161945.png]]

I think that whether this is worrying or not has to come down to two questions:
* Whether the nature of the work is one that tends to have outliers with outsized performance (long-tail effects)
* Whether the org is set up to benefit from a higher skill floor or higher ceiling

Let's consider the example of an national education system. It probably doesn't do a country much good to have masses of illiterate children while a few geniuses thrive.

This curve could also be a sign that an org has a really strong development system. Conversely, it could also be a sign that the org's development doesn't fully meet the needs of the best recruits, leaving them comparatively underdeveloped.

What might this mean for recruiting? It may mean that an org can save cost and effort by hiring faster[^9] and trusting the internal devlopment pipeline to compensate for initial skill differences. It might mean emphasising performance less and tending more towards creating a better fit with teams. It might also mean putting resources elsewhere entirely.

### Case #3 - widening curve
Consider the case where the skill gap between the initial best performers and worst performers widens over time. Again, let's ask the question whether, as an org, this would worry you?

![[Pasted image 20211228162201.png]]

Without rehashing too much of the previous section, I'll leave an example of where this kind of curve is fine: venture capital. When your top ~1% of companies are worth as much as the rest of your portfolio, you'll often rely on your stars for growth rather than your portfolio floor.[^10]

As with the previous graph, this may not be all good news either. It's probably not good for morale if there are obvious favourites within an org, and people that feel left behind may choose to leave (or in some cases, be forced out in an 'up or out' system).

For recruiting, I think that an org can benefit significantly from throwing resources into making things better if (and only if):
* The nature of the work means that the best recruits will have an outsized performance; and
* Putting more effort into trying to measure candidates gets you *better* data[^11]

### Case #4 - demographic biases
If you've read this far you can probably imagine how to start addressing bias in your hiring process already. I'm not going to harp on the point about why cutting bias in hiring is a good thing (hint: you're probably missing out on some great people along the way), but being aware that there's a problem is how you get to fixing it in the first place. How do you know? Measure.[^12]

## The context of real recruitment
So far, I've talked a lot about abstract things. We have an imaginary meta-process measuring an imaginary recruiting system against an imaginary performance measurement system that may not even be possible to construct. What about the real world?

I'm not going to pretend that I know how to run interviews for every possible field. However, one (internet) famous example is the test used by Matasano Security (which Thomas Ptacek writes about [here](https://sockpuppet.org/blog/2015/03/06/the-hiring-post/)). What stands out to me is the work-sample test used (in their case, breaking a custom protocol, but he also suggests a similar path for a rails web app) that has the following properties:
* It collects *objective facts*
* It doesn't offer a shortcut to 'elite' candidates (which incidentally introduces another potentially biased evaluation layer)
* Is improved (by dropping tests with poor prediction value)

I'll also observe that the test is only one part of the interview process, and the whole pipeline is designed to avoid various other problems.

## Addressing specific current issues


## Ideas on interventions (WIP)
What do you believe about the work? Is it one where you can both accurately differentiate between different levels AND different levels have vastly different business impact?

How much effort to throw in getting things right?
How much effort do companies currently throw at getting things right?
How much effort should someone throw at getting somethign right?

## Uncategorised ideas



[^1]: The opinions in this essay are mine. I genuinely believe they are true. However, I am *not* a HR specialist and certainly not *your* HR specialist. If you are looking to make important decisions for you or your company, please get professional advice.

[^2]: *Essay*, deriived from the French *essayer*, meaning "to attempt" (Source: [Wikipedia](https://en.wikipedia.org/wiki/Essay#:~:text=The%20word%20essay%20derives%20from%20the%20French%20infinitive%20essayer%2C%20%22to%20try%22%20or%20%22to%20attempt%22.%20In%20English%20essay%20first%20meant%20%22a%20trial%22%20or%20%22an%20attempt%22%2C%20and%20this%20is%20still%20an%20alternative%20meaning.)). 

[^3]: For example, consider the prevalance of the "not in my back yard" sentiment for many public works (Source: [Wikipedia](https://en.wikipedia.org/wiki/NIMBY)).

[^4]: In tech (or similarly high-leverage industries) the effects can be even more pronounced. Imagine a data scientist figuring out how to raise annual revenue by 0.1%. Doesn't sound like a lot for most places, but if you applied that to Amazon or Google, that 0.1% becomes a fortune.

[^5]: There are contested claims about how exclusive the benefits of an engineering education are. For example, it's probably not fair for engineers to claim a monopoly on problem-solving skills. However, I do think that engineering training (at the university level) emphasises optimisation significantly more than any other field out there.

[^6]: If you, dear reader, are part of an organisation that does *not* know what functions and characteristics are needed to be successful, I would recommend that you stop reading and look to answer *that* question instead.

[^7]: This is much easier said than done. I agree with [this article from Yossi Kreinin](https://yosefk.com/blog/people-can-read-their-managers-mind.html) that people converge on doing what they expect to be rewarded for, not what they're told (e.g. promotion-driven development). I also think that incentives can complicate work that benefits more from intrinsic motivation (which matters by field). Finally, I think that dissecting group level qualities to the individual level is often a non-trivial problem.

[^8]: I don't know if any org may be crazy enough to go as far as hiring candidates they think aren't good just to test whether they are measuring the right things in recruiting (although I'd certainly applaud them for boldness). However, I think there's a relatively low cost in letting through a small percentage of borderline candidates between stages (e.g. a couple of iffy phone screens get to in-person interviews) to examine how good each stage is at filtering candidates.

[^9]: Paradoxically, I think that even these measures can result in better candidates despite a company putting less effort into testing (potentially if the resources are channeled towards some kind of targeted advertising, for example). I've seen strong candidates value responsiveness and an org may win by simply being the first to offer while others are dragging their feet. That's not even factoring in the (actual or perceived) signals on how things operate internally, on how long it takes to make decisions, or on the level of friction between different components of the org.

[^10]: I think it's just the nature of how difficult it is to pick winners in startups, but even the best VCs (or other funders) that I know of don't have a hit rate above 30% or so.

[^11]: It shouldn't be surprising that for some things, more effort doesn't mean better results (e.g. in a truly random experiment). However, an example that seems to work is [internships](https://mobile.twitter.com/gergelyorosz/status/1383874511938850824) when done right. There are obviously ways to do internships badly (e.g. having someone essentially be a paperweight), but the linked thread does talk about how to run an internship so it's a win-win for both intern and org.

[^12]: Paul Graham puts it better than I can in his [essay](http://paulgraham.com/bias.html) about how to detect bias without knowing anything about the application pool. 
