# Recruiting, an Essay
This is an essay[^1] into recruiting, mostly based on a thought experiment. For the benefit of those of you who may be time poor, here's a quick preview of its highlights:

> **Summary**:
> Recruiting should generate a signals about how good a candidate is, allowing an org to filter its pool of candidates. One failure mode is failing to predict good performance from good candidates, or bad performance from bad candidates.
> 
> I suggest that performance review/measurement is a key piece of data to inform both the efficacy and the level of effort required for recruiting. Examples from a thought experiment show how an org might detect problems in its process, or how it could decide whether to add more effort/resourcing to a process.
> 
> As takeaways, I suggest that:
> * Orgs should shape the core of their interview to provide the most reliable signal of a candidate, to the exclusion of other aspects if necessary
> * Orgs should actively collect data and use it to check their own systems
> * Orgs should be careful how they measure their processes

## Do we know what good looks like?
When I moved jobs, I was asked for feedback on the process and got to talk to people who genuinely wanted to make the recruiting process better. This is commendable because there's plenty of pain[^2] in the way recruiting seems to happen currently, including:

* Time-consuming interview processes
* Tests with varying levels of arbitrariness[^3]
* Uncertainty about progress, generally due to low levels of communication

I welcome efforts to reduce friction, although some pain may be inevitable because rejection hurts no matter how kindly worded. The price of getting some good candidates may be creating some bad experiences along the way.

However, what if this wasn't the case? What if a hirihg process was giving people a bad time *without* resulting in good candidates? Do people currently responsible for hiring even know the answer to the question in their own orgs?

I haven't seen many people talk about this scenario. I think people can more readily understand the apparent trade-off between an easier and more difficult process. The intuitive balancing act is between the effort to selecting a promising candidate, and the opportunity cost of selecting a candidate who's not that good[^4].

However, it makes me more nervous to imagine if an org didn't even understand what a good candidate looks like in the first place, independent of the difficulty of the hiring process.

## Foundations of the thought experiment
Let's pause here and construct a basic working model for recruiting:
> The goal of recruiting is to attract and select good candidates for addition to an organisation (substitute as you want for company, team, club, etc.). The processes in recruiting should generate **signals** about how good a candidate is, and these signals inform a **filter** for the candidates. 

One obvious failure mode for such a filter is it would predict low performance from good candidates, and good performance from bad candidates. How common is this problem in practice? Probably not as rare as some would like to believe, based on the following examples:

* Thomas Ptacek's [essay](https://sockpuppet.org/blog/2015/03/06/the-hiring-post/) on the faults of hiring in software, introducing randomness, subjectivity, bias, and more.
* Dan Luu's [essay](https://danluu.com/culture/) on how a simple Fibonacci number coding question *did not discriminate* between the strength of candidates
* Hillel Wayne's [post](https://www.hillelwayne.com/post/linked-lists/) outlining how the popularity of linked list interview questions has persisted despite them seeming to test for something far removed from most companies today

I care that the org that I'm a part of would select people well, and I think it would benefit others to do so too. Adding people to a group is probably the most direct way to change its beaviour[^5]. Here are a couple of types of org that should pay special attention to this process:

* A rapidly growing org or team needs heavy recruitment effort just to scale and deal with the workload. Hiring capable people may well be the difference between maintaining growth or stagnating/regressing.
* Some orgs operate on an apprenticeship model, where the most senior people in the org have often worked their way up from the bottom. A batch of fresh grads could be dicating this kind of org's future in a decade or two

That said, all orgs should hopefully have an interest in recruiting well. Getting back to the concept of recruiting as a filter, how would an org go about constructing this filter, given that each org will have its own needs?

My thoughts drift naturally to the concept of *optimisation*, or how to maximise the tendency for recruiting to benefit the org[^6]. Thinking further:

* An org carries out *functions* to achieve its aims (e.g. selling things, distributing products) that it would benefit from being done better
* Within an org, *people* and *groups* interact to carry out the functions
* The way functions are carried out depends on the *qualities* of the people and groups

This allows a *slightly* tighter description of the problem statement:
> Recruiting is an optimisation problem to select a mix of people who will (either directly or in a team) produce the qualities needed for org success. The processes in recruiting should generate signals about how good a candidate is, and these signals inform a filter for the candidates.

For completeness, this is a *resource-constrained* optimisation problem, as most orgs do not have infinite money (or time, or people) to throw at getting this mix right.

This begs the question, what *are* the qualities needed for org success? I think that this is highly specific (although there may be some generalisations). I'd prefer to concentrate on the general case, and will make this assumption:

> **Assumption 1:** An organisation knows (or has a reasonably good estimate of) the qualities that are needed for it to be successful[^7]

Obviously, getting people to act in a beneficial way is not just a matter of putting the right people in a room together. How does an org get its people to act in a certain way? One way is through culture and norms (a force which I would not underestimate), another way is through instructions and directions delivered via a chain of command.

However, what I think is most direct is through incentives, rewards, and advancement, typically as a part of performance managmeent and/or various reviews. For now, I am also going to assume that:

> **Assumption 2:** An org's performance management and/or advancement systems encourage people to contribute to the qualities it sees are needed for collective success.[^8]

I'm not going to pretend this is easy. However, if an org can confidently say that both Assumption 1 and Assumption 2 are true, that org has a powerful *measurement* tool. Measurement is a key element of control (the other being a mechanism to influence the system) and allows an org to test its own recruiting process.

I propose that the main measure of a *good* recruiting system is how well it predicts good performance (as measured by performance management). Good candidates (as predicted by recruitment) should be good employees and be rewarded/advanced as such.

I think that the measurement of recruiting does need to be done this way because the benefits of a recruit don't exist immediately (in fact, a fresh recruit is almost certainly a net *negative* to a team for a short period of time). This is even more true if there is significant attention required in the short term (e.g. graduate recruits).

## A hypothetical measurement
What kind of data might we expect to see? I don't think it'll be entirely realistic to reduce the complexity of a whole person to a single number or data point (although it would be nice). To me, I think some interesting results may come from being able to tell two simple things from a hypothetical measurement:

* That there should be some *relative ordering* of people, even into rough buckets of ability
* That it would be nice to estimate the *magnitude* of difference between people, certainly the gap between the top and bottom of the population

At this point, we're still far from a practical series of steps for a recruiting process, in the same way that the definition of a square root isn't the same as a method of calculating the square root[^9]. However, we have some useful abstractions to work (a *meta-process*, if you will) with that can get us closer to testing how an org recruits.

Some interesting thought experiments can come out of this abstract measurement. It was this first experiment, in fact, that spawned the thoughts behind this essay. Put simply, "what would it say about a recruiting system if seemingly mediocre recruits consistently outperform supposed top candidates?". This might look like this:

![fig1](/2021-12%20Recruiting/Pasted%20image%2020211228162054.png)

Some variation would be expected here and there (people's lives are complicated after all), but I would be deeply worried if this was a consistent pattern in an org. I would have no confidence in its recruiting process to identify good candidates, and decisions made on the basis of these signals (e.g. early team allocations) would be on shaky ground.

Ordinarily, it would seem like a silly question to ask about the candidates not hired (and therefore not measured by performance reviews). However, if I had evidence that my recruiting filter had a negative correlation with job performance, I'd worry immensely that the best candidates I could have gotten as an org did not even get hired.

The next thought experiment was along similar lines, "what would we be able to tell about the gap between the top and bottom performers over time?". A narrowing curve would look something like this:

![fig2](/2021-12%20Recruiting/Pasted%20image%2020211228161945.png)

Conversely, a widening curve would look something like this:

![fig3](/2021-12%20Recruiting/Pasted%20image%2020211228162201.png)

If you were an org, which would you prefer? I think the answer to this comes down to two questions:
* Whether the nature of the work naturally has outliers with outsized performance (long-tail effects)
* Whether the org is set up to benefit more from a higher skill floor or ceiling

I think considering the nature of the work is helpful to understand whether the skill narrowing or widening is caused by, or is in spite of, whatever development mechanisms are put in place at an org. You may want to make sure, for example, that high growth is really due to high potential and not favouritism in being provided development opportunities.

It may be useful to ask, isn't the most important thing the movement of the skill floor in an absolute sense? I think this is broadly true (e.g. healthcare) but has important exceptions, when the best could potentially provide returns orders of magnitude greater than the worst[^10]. 

What does this mean for recruiting? It would seem that an org would benefit significantly from throwing resources into trying to seek out only the best candidates if (and only if):
* The nature of the work is such that the best recruits will have an outsized performance; and
* Putting more effort into trying to measure gets you *better* data

If the work doesn't benefit much from hiring outliers, an org may save cost and effort by hiring faster[^11]. It might mean that resources are better allocated towards the development process instead, or that recruiting focuses more on team fit over raw skill.

Conversely, the work may benefit from hiring outliers, but you might not be able to tell who's likely to be one based on the interview alone. At this point, it may also be worth saving cost and effort, rather than chasing a signal that isn't there. Better yet, redirect effort into the channels which you know will give you a better signal[^12].

This essay didn't start out addressing diversity and unconscious biases in recruiting, but it's worth mentioning here. If you accept that reducing bias in hiring is a good thing, then you need to measure where it happens to have a shot at fixing it[^13]. 

## Lessons from the Abstract
I've spent a long time talking about things in the abstract. We have an imaginary meta-process measuring an abstract recruiting system against an idealised performance measurement system (which may not even be possible to construct). What about the real world? What can you, as part of an org, do for your own processes?

I would suggest the main takeaway is that your recruiting processes should be constructed of things that give the best signal and attempt to cut all else. I won't pretend this is easy, because lots of heuristics (e.g. what school someone attended, what their grades are) are seemingly sensible and fast ways to prune a large applicant pool, but it's probably better in the long run.

In particular, the *core* of your recruiting process (which is often the interview) should give you the most reliable signal of how good a candidate would be. The (internet) famous example of Matasano security comes to mind, which Thomas Ptacek writes about [here](https://sockpuppet.org/blog/2015/03/06/the-hiring-post/)). While the pipeline is structured to avoid various problems, the work-sample test stands out to me because it aims to:
* Collect *objective facts* about a candidate
* Avoid creating a shortcut for 'elite' candidates
* Is continuously improved (by dropping tests with poor prediction values)

The second takeaway is that you should actively look to collect and check your systems using the data they emit. It is possible, for example, to understand how well different steps in a process filter candidates by comparing the signals from one to the next[^14]. I talked to a team looking to address gender bias in its recruiting, and suggested that they look at whether the gender balance was getting worse as candidates went from resume screening through to interviews, as a starting point.

The third, more sobering takeaway, is that you should be careful what aspects you place importance on in a recruiting process. I had the chance to talk to a recruiting expert recently, and asked what metrics they are usually assessed on. The answer I got focused on things like time to find a candidate and cost of search, and I didn't hear anything about the candidate's performance.

The costs of finding a good candidate are not cheap (especially with senior hires), and the time waiting for a position to be filled is useful work not done. It's understandable that someone would try to keep these down. That said, if the difference between a good and great candidate is significant enough, the potential upsides can dwarf those costs completely[^15].

I was fortunate to come across this [post](https://commoncog.com/blog/cash-strapped-hiring/) by Cedric Chin, writing about how to hire efficiently. A few ideas that I have not covered, but would like to highlight as interesting are:

* There is a default hiring approach of essentially throwing money at candidates, but there is a more efficient way for companies that cannot afford to hire at the top of the market
* Using differentiated hiring criteria means that you can hire talent underprced by the market
* The HubSpot example identifies common/stereotypical sales attributes such as "aggression, objection handling, needs identification and closing ability were *negatively* correlated with success at HubSpot", which showed up in the collected data

This essay is not the be all and end all of recruiting, but is hopefully useful to you, your team, or your org.

#### Contact:
I enjoy writing about interesting problems. If you found this essay interesting, have some thoughts to discuss, or would just like to get in touch, feel free to do so at [hello@jrmylow.com](mailto:hello@jrmylow.com)


[^1]: *Essay*, deriived from the French *essayer*, meaning "to attempt" (Source: [Wikipedia](https://en.wikipedia.org/wiki/Essay#:~:text=The%20word%20essay%20derives%20from%20the%20French%20infinitive%20essayer%2C%20%22to%20try%22%20or%20%22to%20attempt%22.%20In%20English%20essay%20first%20meant%20%22a%20trial%22%20or%20%22an%20attempt%22%2C%20and%20this%20is%20still%20an%20alternative%20meaning.)).

[^2]: An example of how easy it is to find bad experiences is [/r/recruitinghell](https://old.reddit.com/r/recruitinghell/), with currently around 250,000 subscribers. This doesn't necessarily mean that the majority of experiences are bad, but the problem resonates with a lot of people.

[^3]: I'm aware of ongoing debates around coding tests, case studies, psychometric testing, brainteasers, and more.

[^4]: This can be talked about using the language of false positives or false negatives, which may be useful to some people but it's not how I ususally think.

[^5]: To clarify, I mean this changes the relationships and the dynamics of the group, instead of just group's position or ideas here. It is perfectly possible for a group to collectively change their minds about something quickly, but I'd probably point to that as a *characteristic* of this group being that it *can* change its mind quickly.

[^6]: There are contested claims about how exclusive the benefits of an engineering education are. For example, it's probably not fair for engineers to claim a monopoly on problem-solving skills. However, I do think that engineering training (at the university level) emphasises optimisation significantly more than any other field out there.

[^7]: If you, dear reader, are part of an organisation that does *not* know what functions and characteristics are needed for it to be successful, I would recommend that you stop reading and look to answer *that* question instead.

[^8]: This is much easier said than done. Yossi Kreinin [writes]](https://yosefk.com/blog/people-can-read-their-managers-mind.html) on how people converge on doing what they expect to be rewarded for, not what they're told (e.g. promotion-driven development). I also think that incentives can complicate work that benefits more from intrinsic motivation (which matters immensely for some fields).

[^9]: The square root of a number x is the number y such that y\*y = x. It helps you tell whether a number is the square root of another, but doesn't help you find it. To do so, you would need additional steps e.g. Newton's method. 

[^10]: I think for some important real-world systems, you need to have measures to accommodate both the skill ceiling and floor. Education is the best example that comes to mind, you need to lift up the floor well, but also make sure not to stifle the best into mediocrity.

[^11]: Although I describe hiring faster as less rigorous, it may actually result in producing better hires overall. The responsiveness of a company and speed of hiring contributes to signal how decisive and competent a company is at moving. An org may snap up a strong candidate simply being the first to move while others drag their feet.

[^12]: An expensive exercise is [internships](https://mobile.twitter.com/gergelyorosz/status/1383874511938850824), that allow an org to measure a candidate closely over a few months, as well as giving them the advantage in convincing the promising ones to stay. 

[^13]: Paul Graham puts it better than I can in his [essay](http://paulgraham.com/bias.html) about how to detect bias without knowing anything about the application pool. Put simply, if people of a given demographic perform better (objectively) than the average, your hiring process is biased against them because they would have had to overcome it to enter to begin with.

[^14]: I think one interesting way (although it may not be the most efficient use of effort) is letting a small fraction of borderline candidates through from one stage to the next and seeing how they perform. I don't think any company will be crazy enough to go as far as hiring a candidate on this basis (although I'd applaud them for boldness). However, I think that within stages it would provide useful information about whether, for example, a phone screen is filtering out candidates that would otherwise be great at an interview.

[^15]: A friend described a team he knew of that worked to reduce operating costs by ~1% at a major international company, a multi-million dollar cost saving. The team paid for itself many times over that year, and recruitment costs of even hundreds of thousands would be a drop in the bucket for this level of return. 
