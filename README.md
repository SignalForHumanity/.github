# Signal For Humanity

**Build systems that make life better. Measure whether they actually do.**

Signal For Humanity is an open-source initiative focused on using software, artificial intelligence, automation, and data to solve practical problems that improve human well-being.

The goal is not to build technology for its own sake.

The goal is to identify places where people, resources, and organizations fail to connect efficiently — and build systems that help close those gaps.

## The Idea

Many important problems are not caused by a complete lack of resources.

They are coordination problems.

Food exists while people are hungry.

Useful goods are discarded while someone nearby needs them.

Volunteers are willing to help but do not know where help is needed.

Small organizations have resources but lack the infrastructure to coordinate them.

Information exists but does not reach the right person at the right time.

Modern software can reduce that friction.

AI makes it possible to go further: systems can continuously observe conditions, identify opportunities, coordinate resources, learn from outcomes, and improve over time.

Signal For Humanity exists to explore and build those systems.

## Principles

### Human Benefit Is the Objective

Technology is a tool.

Success should ultimately be measured by real-world outcomes:

- Were more people helped?
- Were fewer resources wasted?
- Did something become more accessible?
- Did communities become more resilient?
- Did the system reduce unnecessary cost or effort?
- Did it create measurable improvement over what existed before?

Technical sophistication is useful only insofar as it contributes to those outcomes.

### Open by Default

Projects should be open source whenever practical.

A useful system for addressing a human problem should be something communities can inspect, modify, deploy, improve, and adapt to their own circumstances.

The objective is not dependency on Signal For Humanity.

The objective is to create tools worth copying.

### Local First, Scalable Later

Large problems often become tractable when reduced to local ones.

Instead of attempting to optimize an entire country, begin with:

> What can we improve in one community?

Build it.

Measure it.

Learn from it.

Then determine whether the same system can work elsewhere.

A successful system should be capable of spreading without requiring centralized control.

### AI Should Do Work

Signal For Humanity is particularly interested in **agentic systems**: AI that can participate in an ongoing operational process rather than simply answer questions.

Where appropriate, agents may:

1. Observe a system.
2. Maintain an understanding of its current state.
3. Identify problems and opportunities.
4. Develop possible interventions.
5. Take authorized actions.
6. Measure the results.
7. Learn from those results.
8. Improve future decisions.

The intended loop is:

```text
Observe
   ↓
Understand
   ↓
Plan
   ↓
Act
   ↓
Measure
   ↓
Learn
   ↓
Improve
   └──────────→ Observe
```

Autonomy should be proportional to risk. Low-risk, reversible actions can be automated aggressively. Actions involving people, money, safety, privacy, or other significant consequences should have appropriate safeguards and human oversight.

### Measure Reality

A system should not declare itself successful because an AI believes an idea worked.

Where possible, projects should establish measurable objectives and collect evidence about actual outcomes.

Experiments can fail.

An unsuccessful experiment that produces useful evidence is more valuable than a successful-looking project that never measures its impact.

### Build Small Things That Work

Signal For Humanity does not require every project to become a startup, platform, or massive application.

Sometimes the useful thing is:

- a small Rust service,
- a matching algorithm,
- a public dataset,
- an optimization model,
- an autonomous agent,
- a mobile application,
- an API,
- a protocol,
- or a script that eliminates several hours of unnecessary human work.

Build the smallest system capable of producing the desired outcome.

Then improve it.

---

# Projects

## FoodRelay

**Move available food to where it can do the most good.**

[FoodRelay](https://github.com/SignalForHumanity/FoodRelay) explores localized food distribution as a coordination problem.

Food may be produced, sold, donated, needed, transported, and discarded within the same geographic area without those participants having an effective mechanism for coordinating with one another.

FoodRelay aims to provide that coordination layer.

The long-term vision includes connecting local producers, businesses, organizations, volunteers, transportation capacity, available food, and local demand.

Rather than simply providing a directory or marketplace, FoodRelay can evolve into an intelligent system capable of continuously observing the local food network and helping improve it.

```text
Producers ───────┐
Businesses ──────┤
Food Surplus ────┤
                 ▼
             FoodRelay
                 │
       ┌─────────┼─────────┐
       ▼         ▼         ▼
     Match     Route     Predict
       │         │         │
       └─────────┼─────────┘
                 ▼
          Local Distribution
                 │
                 ▼
              Outcomes
                 │
                 ▼
          Learn & Improve
```

Potential measures of success include:

- food redistributed,
- food waste prevented,
- unmet demand satisfied,
- transportation distance reduced,
- producer participation,
- recipient accessibility,
- fulfillment reliability,
- and cost per successful distribution.

FoodRelay is an example of the broader Signal For Humanity philosophy:

**find wasted capacity, identify unmet need, and build the coordination system connecting the two.**

---

# Building Agentic Public Infrastructure

One of the central research directions of Signal For Humanity is the idea that AI agents can help operate public-benefit infrastructure.

Traditional software waits for someone to use it.

An agentic system can observe what is happening and ask:

> What needs attention right now?

That could mean noticing that a food source consistently has excess inventory, recognizing an underserved geographic area, discovering inefficient transportation patterns, identifying an organization that could participate in the network, or detecting that a previous intervention did not work.

The system can then investigate, propose an intervention, execute actions within its authority, and evaluate what happened.

Over time, this creates infrastructure that does more than store information.

It **learns how to coordinate resources better.**

## Humans Remain in Control

Autonomy does not mean unlimited authority.

Agentic systems should operate within explicit boundaries.

Actions should be observable and attributable. Important decisions should be explainable. High-impact actions should require appropriate authorization. Systems should be designed so humans can inspect, override, restrict, or disable autonomous behavior.

The objective is not to remove humans from communities.

It is to remove unnecessary coordination work so humans can spend more time actually helping them.

---

# What Belongs Here?

A Signal For Humanity project should have a plausible path toward measurable human benefit.

Examples could include:

- food distribution,
- resource matching,
- accessibility,
- disaster response,
- mutual aid,
- transportation coordination,
- community logistics,
- education,
- environmental monitoring,
- public-interest data,
- volunteer coordination,
- waste reduction,
- or tools that allow small organizations to accomplish work previously requiring much larger resources.

Projects do not need to solve humanity-scale problems.

Solving one small problem well is enough.

If it works, someone else can build on it.

---

# Contributing

Signal For Humanity welcomes developers, researchers, designers, domain experts, community organizations, and people who simply understand a problem that technology might help solve.

You do not need to arrive with a solution.

A well-defined problem is valuable.

A useful contribution might be:

- identifying a real coordination failure,
- contributing code,
- providing domain expertise,
- supplying or improving datasets,
- testing a system in the real world,
- evaluating outcomes,
- improving documentation,
- identifying unintended consequences,
- or proposing a better approach.

AI-assisted contributions are welcome.

What matters is whether the resulting work is understandable, testable, safe, and useful.

---

# A Simple Standard

Before building something, ask:

**Does this solve a real problem?**

Before adding complexity, ask:

**Does this make the solution meaningfully better?**

After deploying it, ask:

**Did it actually help?**

Then measure the answer.

---

## Signal For Humanity

**Find the signal. Build something useful. Help humanity.**
