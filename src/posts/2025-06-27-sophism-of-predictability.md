---
title: "Sophism of predictability — Is software estimation an illusion?"
description: "What if our trust in estimations is nothing more than a well-packaged illusion — a sophism?"
date: 2025-06-27
---

In **software development**, calendar predictability is a powerful weapon. Deadlines are drawn like battle plans, and estimations are treated like epic **prophecies**.

But what if our trust in these prophecies is nothing more than a well-packaged illusion — a **sophism**?

What follows is a mix of curious laws, traps, and one coffee-corner conversation that changed how **I see** all of it.

## The coffee talk

The other day, I was in the coffee corner having an **interesting conversation** with my managers when I threw out a simple **question**:

> “Do we even care about story points for estimations? If we miss the sprint goal for whatever reason, we just adjust and move on. The story points seem like an obsolete number at that point.”

As the words left my mouth, I paused. In that same instant, I answered myself:

> “**Of course** we care about story points and estimations. Otherwise, how could we predict deliveries or build roadmaps?”

My manager thought for a second and then said something that’s been living rent-free in my head ever since:

> “Often, it’s not really about how long something will take. It’s about how aligned we are as a team — how well we understand the complexity, the importance, and the value of a user story. Story points are more about shared understanding than delivery timing.”

That conversation stuck with me… estimation isn’t just planning, **it’s a ritual**.

One that gives us the **illusion of predictability in a world that rarely is**—and that **illusion** is the **sophism**.

## Anatomy of the sophism

We try to estimate based on what **we think we know** — familiar patterns, **past experiences,** or anything that might give **credibility** to our **guesses**.

We say things like:

> “We’ve done this before”
> “If we break it into smaller pieces, we can parallelize the work”

But in doing so, we fall into a trap of our own making — **a fallacious tale of predictability**.

Each new feature isn’t a repetition, it’s a **unique challenge**. Yet human **optimism biases** us. We shrink timelines, not because the work is simple but because we’re **afraid to admit the truth**:

- This feature might take a long time.
- It might be difficult.
- We might not even have the skill set to complete it yet.

And as always, we forget the one universal truth of software:

> **The unknown unknowns will come.**

We can’t estimate our way out of that. And so, **we focus our energy on the things we *think* we know**. The easy wins, the low-hanging fruit.

Then the **bike shed** problem strikes.

## Bike shed, reactor core, and the false sense of progress

![A bicycle parked under a wooden shed](/images/bike-shed.jpg)

We fall into **endless discussions** about naming conventions, linting rules, pixel spacing, or the color of a button — small details **without much value**.

Why do we do this?

Because these are the **things that feel safe**. They give us the illusion of control and progress. Debating tiny details makes us feel productive, even when we are **avoiding the deeper uncertainties** like the architectural risks, the integration nightmares and the business trade-offs that actually define success.

Let’s consider a **fictional scenario**: a committee is responsible for approving the construction of a nuclear power plant. **The stakes are high**: safety, engineering, environmental impact, and yet the committee spends most of its **time debating the small details, like the design of the staff bicycle shed.**

**We polish the bike shed while the reactor core design goes untouched**.

It’s easier to argue about what color to paint the shed than to confront the terrifying complexity of the nuclear reactor inside.

The shed is visible, graspable, and harmless — it is obvious. The core? It’s abstract, risky, and mentally heavy, **so we avoid it**.

**And in doing so, we leave the most critical discussions behind.**

This phenomenon even has a name: [Parkinson’s Law of Triviality](https://en.wikipedia.org/wiki/Law_of_triviality).

And worst of all?

This **false sense of productivity** reinforces the **sophism**.

## Hofstadter’s Law and the recursion of delay

If we are making any decisions, then surely we must be making progress, right?

Even when we do manage to focus on the real work, the reactor core instead of the bike shed, we are still not safe and we still need to deal with **unknown unknowns**.

We plan, we break things down, **we add buffers**, we even sandbag a little, using our experience and gut feel to play it safe.

And still… we’re **late to delivery**.

> “It always takes longer than you expect, even when you take into account Hofstadter’s Law.” — Douglas Hofstadter

That’s the trap: we plan for delay, and we still get delayed.

Why? Because delay isn’t just a scheduling issue. It’s an emergent property of building software — or many other things.

**Every project contains dark matter**: interactions, **edge cases**, fragile integrations, unexpected constraints, **stakeholder indecision,** and **flaky environments**. These things don’t live in Jira tickets, **they emerge during execution**. And by the time they appear, the roadmap is already out of sync with reality.

**This is the recursion** of [Hofstadter’s Law](https://en.wikipedia.org/wiki/Hofstadter%27s_law):

Even when we acknowledge our own estimation bias and try to correct for it, we still underestimate because **some things only become knowable once we begin**.

**And to me, delay isn’t a sign of failure.** It is often a signal that we’re building something complex enough to be worth building.

But instead **of embracing that complexity**, we hold onto delivery dates and rigid estimates.

**We offer confidence over honesty, certainty over adaptability, but not out of malice, *but out of habit*.**

And so, the **sophism persists**.

## A powerful statement

![A runner moving alongside a tortoise](/images/runner-and-tortoise.jpg)

Recently, **during a grooming session**, we were discussing a new feature that seemed simple at first glance. But after spending a good amount of time debating the **bike shed**, we finally looked into the **reactor core** — and realized the actual effort required was much larger than the timeline allowed.

Then the **feature lead** said:

> “We need to be really fast if we want to make it by the deadline”

Before anyone could respond, one of our senior engineers gently pushed back with a ***powerful statement***:

> “It’s not about speed”

I was instantly pulled out of the room in my mind. That moment — simple, quiet, but deep — reminded me of an article by Robert C. Martin, **Uncle Bob**, titled *“[It’s Not About Speed](https://wiki.c2.com/?ItsNotAboutSpeed)”.* One particular passage from it hooked me years ago and still does:

> So. It’s not just about speed. Being the fastest programmer does not mean you are the best programmer. Spending the time to clean up your code and invest in sound architecture is just as important as implementing the right functionality; and perhaps even more important.

With that in mind, we leaned into the **discussion** — and something shifted.

We stopped worrying about how long it would take.

We walked through implementation details, we discussed **corner cases**, critical flows and even **side effects** of that change in a year from now. We discussed **priorities**. ***It was exciting***.

The feature began to feel real, concrete, tangible.

For a moment, we **stopped thinking *tactically*** and **started acting *strategically***.

And so, the **sophism persists**.

## The time plasticity of a feature delivery

Have you ever been about to leave your place, checked the bus timetable, and realized you still had 10 minutes?

So you start mentally sequencing the steps: finish getting dressed, grab your backpack, find your keys, put your shoes on. You’re at the door — and suddenly you remember you **forgot** your phone.

You run back inside — now you’re losing precious seconds. You finally find your phone and storm out to the door, sprinting to the bus stop. **You didn’t *plan* to run**. The idea was a calm walk. You had ten whole minutes.

And yet, somehow, you’re there — just barely — sweaty but on time.

Here’s the twist: even if you had checked the timetable **20 minutes earlier**, chances are you’d still have forgotten your phone. You’d still have left later than intended. **Something would have filled the time** — because you *had* it.

The same phenomenon plays out in software delivery. When we’re given the luxury of a generous deadline, we tend to postpone. We pick up other tasks, stretch the scope, tweak and refactor. The original commitment starts to drift into the background.

And then [**Parkinson’s Law**](https://en.wikipedia.org/wiki/C._Northcote_Parkinson) hits:

> ***“Work expands so as to fill the time available for its completion.”***
> — C. Northcote Parkinson

This law was originally satire — a jab at bureaucratic inefficiency — but its core insight maps alarmingly well to our world: **If we assign large timelines just for the sake of comfort or padding, we’ll almost certainly end up using all that time. Not because we needed it, but because *it was there.***

## From tactical execution to strategic thinking

We’ll never remove uncertainty from software development — and we shouldn’t try to. What we *can* do is stop pretending that certainty was ever the goal.

That’s what it means to think **strategically** as a team.

Where a ***tactical team*** focuses on short-term completion and estimation as a delivery promise, the ***strategic team*** treats estimation as a **communication tool** — a way to uncover **complexity**, align **expectations**, and surface **risks**.

Instead of asking *“How fast can we finish this?”*, the ***strategic team*** asks:

- *“What might block us?”*
- *“Which part of this feature is most critical to understand first?”*
- *“What’s unclear, and how do we find clarity early?”*

Estimation is still part of that process — but it’s ***reimagined***.

**T-shirt sizes** become a lightweight, low-stakes way to **signal uncertainty**.

A “*Large*” doesn’t just mean “more work” — it means **“we need to talk about this more.”**

**During Planning Poker**, **something** even more **valuable happens: *disagreement***.

When one person throws down a “*2*” and another a “*13*,” the room has to stop. Not to argue over the “right” number, but to ask: ***what are we seeing differently**?*

Is there ***hidden complexity***? Is someone ***missing context***?

**The number itself matters less than the conversation it starts.**

Planning Poker becomes a **discovery tool**, not a performance.

**Velocity** becomes a reflection tool — not a scoreboard.

Tracking team velocity over time lets us learn **how we work**, not punish ourselves for what we didn’t deliver. It reveals patterns, bottlenecks, and places where expectations are far from reality.

And then there’s **alignment**.

Then teams don't estimate efforts— they **estimate understanding**. They stop to ask:

- *Do we agree on what this feature means?*
- *Why it matters?*
- *What a Definition of Done looks like?*

Estimation becomes a **checkpoint**, not a bet.

And when timelines **do** tighten — as they always will — ***strategic teams*** rely not on wishful thinking or sandbagged numbers, but on **prioritization and negotiation**.

They ask: *What is truly essential for this release? What can be postponed without harm?*

## The sophism fades

Estimation won’t save us from **complexity**. But ***strategic*** thinking might.

It’s not about avoiding delay. It’s about **understanding** it, so we can **shape** it, respond to it, and navigate it **with honesty**.

***The sophism of predictability doesn’t go easily***. But **every time a team pauses** to **align**, **adapts** their scope with intention, or **admits** what they don’t yet know — ***it fades a little more***.

![An arrow in the center of a target](/images/target.jpg)

*First published in [Inbank product & engineering](https://medium.com/inbank-product-and-engineering/sophism-of-predictability-is-software-estimation-an-illusion-d307c84b5758) on June 27, 2025.*
