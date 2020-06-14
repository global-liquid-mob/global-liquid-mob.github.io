# Global Liquid Mob

## The current thinking goes something like this: 
**Hypothesis:** Mob programming, as a format, is very resilient and thrives on collaboration.

**Conclusion to be tested:** It is possible to construct a globe-spanning mob that maintains the fluid nature of single-piece work throughout multiple continuous 24 hour cycles by changing the makeup of the mob throughout each day in a structured way, generally “flowing" east-to-west in a non-stop and sustainable fashion.

A simplistic example of what is proposed has groups of between 2 an 3 people all participating from within 1 or more _neighboring_ time zone(s) identified as a single "group". They are separated by approximately 3-5 hours on either side from two simlar groups: one to the east, another to the west. Each group, in _their local_ morning, combine to mob with the group to _their_ east making what they view as a "morning" mob. The two groups function as one mob totalling 4-6 people.

In this simplistic case, each group takes a break at the midpoint of their day, after which they reform into an _afternoon_ mob, having left the group to their east and now joining with the group to their west, again seperated from them by approximatelt 3-5 time zones.

In general, at all times, there is a functioning mob of roughly 4-6 people who have carried the code base further with each successive change. This will initially feel strange, because it is very new. If in the format's full implemnatation the same cycles repeat _each day_, then it is expected that these cycles will become routine.

**Open questions**
There are many questions about the details: that, in part, is what the experiment is designed to surface. There are also some absolutes:
* at any given time a _“mob"_ consists of _at least_ four people, and not more than 7 (with the exception of a mob behaving like normal people and breaking for a meal),
* actively working together on the _same thing_, 
* on _one computer at a time_, as the driver rotates.

Some of the advantages of a global and fluid model include but are not limited to:
* _where_ people _are_ can vary widely _so long as_ they can work _together_.
* at each change of who is part of a given mob, there are _multiple_ other mobbers 
that have been working on that solution for roughly _the last four hours_, so there is effectively no "break" or "handoff". 
It is more akin to a continuous _flow_.
* Learning is going on continuously, and it may turn out that the role of ["archivist"](https://github.com/willemlarsen/mobprogrammingrpg/blob/master/theArchivist.pdf) is elevated in this model to reinforce contginuous learning and commnication at multiple levels.

Some minimally viable conditions can be met for almost all participants, _ideally_ continuously: 
1. a reliable computer connection, 
2. _minimally_, good voice connectivity, 
3. ideally, video connection that allows each participant to see all other participants [^1], 
4. the ability to transfer control of the code being worked on between individuals easily, or, control of a single computer that is editing the code.
Note that none of the above challenges are significantly different from remote pair programming. They are challenges with well-known solutions or remediations. Not every partipant may be able to meet _all_ of the above conditions _all_ of time (technology sometimes fails us and this isn't any different than in a normal workday).

## The current focus
We are seeking participation from all hemispheres,
* .. from people already experienced with mob programming,
* .. who can commit to a _minimum_ participation of some number of days greater than 1,
* .. and are willing to share their eperiences freely.
That said, yes, we are well aware that most people _work_ for a living, generally Monday - Friday. So, that would suggest the most practical experiment would be run...
* for a duration not to exceed 2 days (at least while we are asking for volunteers),
* on a _weekend_ (yes, not _everyone_ can give up time with their family, and we're not asking for _everyone_ just _enough_ people)
* no more time than what you would devote to a coderetreat, which is typically about the length of a workday. 
What we are modeling is a _slice_ of a workweek: 2 consecutive days, functioning as a mob (many different connected mobs actually), developing a project[^2], together.

More specifically, to be a _healthy_ experiment, we need some _varienty_: e.g. 
1. a mix of developers and non-developers, which will likely include designers of varying sorts (we frankly do not know what all may be required; it's an _experiment_). 
2. men, women, and every other variety of human (Please don't ask for an explicit list. At some point that just gets silly), 
3. from pretty much everywhere on the planet (all hemispheres, both in latitude and logitude). 

## How do I volunteer? ##
Please email any of the following individuals (we anticipate creating a more sophisticated onboarding process later, but for now ...)
Name | email
------------ | -------------
Bob Allen | bogghead@gmail.com
Christian Hujer | christian.hujer@nelkinda.com
Daniel Bartholomae | daniel@bartholomae.name

## Links
* [GitHub Organization](https://github.com/global-liquid-mob)
* [Website Source Code](https://github.com/global-liquid-mob/global-liquid-mob.github.io)

[^1]: Being able to see the faces of the people you are working with turns out to be a pretty important factor in how well a mob works together. That said, there may times or reasons why that just isn't possible or desireable at _some_ time or for _some_ people. To be clear, it is highly desireable in faciltating human-to-human communication.

[^2]: Current thinking regarding a project focus is to consider using and _existing_ Open Source Project that can be forked and made more easily applied beyond it's original limited intention. One candidate project is India's [AarogyaSetu_Android application](https://github.com/nic-delhi/AarogyaSetu_Android) in large part because it is focussed on helping in a very tangible and relevant way. Please see [this Washingtom Post article](https://techcrunch.com/2020/05/26/aarogya-setu-india-source-code-release/) that makes clear why "contract tracing" is important enough that two major countries, Germany and India, have both developed, and Open-Sourced applications to aid with the process.
