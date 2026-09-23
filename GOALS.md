# Goals

## Why this repository exists

AI-assisted development lets a solo developer spend less time writing code manually and more time directing, reviewing, testing, and making product decisions.

Many multi-agent setups become large, expensive, noisy, and difficult to control.

This repository takes the opposite approach.

The goal is to provide a **small, practical set of specialized AI assistants** that help a solo developer build, test, release, and grow software products without pretending to be an autonomous company.

## Core idea

The human remains the decision-maker.

Agents are assistants.

They exist to:
- reduce repetitive work
- improve implementation quality
- expose risks and weak assumptions
- reduce manual QA
- bring specialized expertise when useful
- help with product growth and customer acquisition
- provide an independent check before production releases

They do **not** own the product, roadmap, architecture, or strategy.

## Truth over agreement

AI assistants should not flatter the developer or validate ideas by default.

A useful assistant should be willing to say:
- the reasoning is weak
- an assumption has not been validated
- a feature probably should not be built yet
- the current plan adds unnecessary complexity
- the evidence does not support the conclusion
- there is not enough information to know

Pushback should be specific, respectful, evidence-based, and actionable.

The goal is not contrarianism. The goal is better decisions.

## Build less, learn faster

Technical founders often respond to uncertainty by building more software.

That is useful when the bottleneck is engineering.

It is wasteful when the real bottleneck is:
- acquisition
- positioning
- activation
- conversion
- retention
- pricing
- distribution

For that reason, Growth is a first-class agent in this system.

Its job is not merely to write marketing copy. Its job is to identify the current growth bottleneck, challenge feature-building when appropriate, and propose measurable experiments that can improve distribution and revenue.

## Lightweight by design

The default team is small:
- **Lead**
- **Frontend Expert**
- **Backend Expert**
- **QA**
- **Growth**
- **Release Reviewer**

Not every task needs every agent.

A small UI fix should not trigger a virtual management meeting.

A production release should receive an independent review.

## Human-in-the-loop by default

```text
Human
  ↓
Goal / constraint / decision
  ↓
Lead or specialist
  ↓
Implementation / research / testing
  ↓
Independent verification when useful
  ↓
Human judgment
```

The human should spend more time on:
- deciding what matters
- accepting or rejecting tradeoffs
- judging UX and product direction
- validating business assumptions
- making final release decisions

And less time on:
- boilerplate implementation
- repetitive debugging
- routine test construction
- mechanical code review
- generic marketing checklists

## Quality through independent checks

Agents should not blindly trust each other's summaries.

When reviewing work, inspect the actual repository state, diff, tests, and relevant evidence.

## Compatible, not coupled

The agent definitions are plain Markdown and are intended to work across AI coding environments such as Codex and Claude Code without requiring a large orchestration framework.

The objective is leverage, not theater.

## Success criteria

This repository is successful if it helps a solo developer:
1. ship useful software faster
2. maintain or improve implementation quality
3. reduce repetitive manual QA
4. detect weak technical and product decisions earlier
5. spend less time on agent micromanagement
6. improve customer acquisition and product growth
7. keep the human clearly in control
