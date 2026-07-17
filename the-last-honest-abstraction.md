---
title: "The Last Honest Abstraction: Why AI Coding Isn't the End of Engineering"
published: false
description: "AI didn't make developers stop understanding software. It made an old truth impossible to ignore: engineering has always depended on abstraction."
tags: ai, programming, discuss, softwaredevelopment
cover_image: https://raw.githubusercontent.com/copyleftdev/the-last-honest-abstraction/main/assets/cover.png
---

*Why every generation thinks the next programmer understands less—and why AI changes the burden of proof, not the need for engineering.*

> "Developers can't even explain their own code anymore."

If you've spent any time around software lately, you've probably seen some version of that argument.

The culprit, we're told, is AI.

Developers are prompting language models, accepting generated code, and shipping software they couldn't possibly explain line by line. Somewhere between autocomplete and autonomous agents, we supposedly crossed a professional line. We traded craftsmanship for convenience.

It sounds like a new argument.

It's one of the oldest in computing.

## Before We Go Any Further...

Before I make my case, I want to pay homage to a rare breed of engineer.

You know who you are.

You're the people who can look at compiler output and immediately tell when an optimization didn't quite land. You read assembly like most people read JavaScript. You understand calling conventions, cache locality, virtual memory, branch prediction, linker behavior, and processor architecture—and you can still build elegant software without turning every project into a dissertation.

You're rare.

And you've quietly carried this industry for decades.

Many of the abstractions the rest of us rely on exist because someone like you spent years wrestling with complexity until everyone else could work one layer higher.

Every generation has its handful of engineers who descend into the deepest layers of the machine, then return carrying tools that allow the rest of us to build something higher.

This article isn't arguing against mastery.

It's a thank-you to the people who made abstraction possible.

## Every Layer Was Once Considered Cheating

Again and again, computing has moved upward by adding layers.

Machine code gave way to assembly for most programming. Someone inevitably complained that assembly programmers weren't "real programmers" because they no longer had to manipulate raw binary.

Higher-level languages followed. Compilers hid more of what the processor was *actually* doing. Managed memory, virtual machines, dynamic languages, frameworks, cloud platforms, containers, and orchestration systems each took another category of complexity and moved it behind an interface.

And now...

AI.

The technologies aren't a single, tidy lineage. They abstract different problems, and old layers rarely disappear. But the cultural pattern repeats:

> "Do they *really* understand what's happening underneath?"

The nouns change.

The complaint doesn't.

## The Myth of the Complete Programmer

Here's an uncomfortable truth.

Most software has never been written by people who fully understood every layer beneath it.

That isn't criticism.

It's reality.

Ask an application developer to explain exactly how their operating system schedules threads.

Ask them why their compiler emitted a particular optimization.

Ask them to walk through every page-table translation.

Ask them to trace how cache behavior affected one production slowdown.

Ask them to explain every TCP retransmission or every filesystem recovery after an unexpected shutdown.

Some can.

Most can't.

And yet...

The software still ships.

Not because understanding stopped mattering, but because software engineering evolved around abstractions with bounded responsibilities and increasingly testable guarantees.

## The Entire Purpose of Engineering

Engineering has never been about refusing abstraction.

It's been about earning it.

Every abstraction represents an enormous investment of human understanding. Someone had to master the ugly details so the next engineer could focus on solving a different problem.

A civil engineer need not manufacture every bolt before designing a bridge, but must know which loads it can bear. Software abstractions work the same way: we delegate construction, not accountability.

Requiring every software engineer to hand-write machine code before building a web application wouldn't protect craftsmanship.

Progress wouldn't slow down.

It would stop.

Abstractions aren't shortcuts.

They're accumulated knowledge.

They're understanding, compressed into reusable form.

That's not laziness.

That's civilization.

## What AI Actually Changed

AI did change something.

Just not what many people think.

A conventional compiler is expected to produce reproducible output from fixed inputs. A language model samples from probabilities. A compiler hides implementation behind a defined system; a model proposes implementation without guaranteeing that the proposal is correct.

That makes AI a less trustworthy abstraction by default—not an invalid one. It means the engineer must supply the trust boundary through review, tests, observability, constraints, and a willingness to reject plausible-looking output.

The real shift is that authorship is becoming an even weaker proxy for understanding—and an even less useful signal of correctness.

For decades, many engineers subconsciously equated "I wrote it" with "I understand it."

Those were never the same thing.

We've all inherited libraries. We've all trusted frameworks. We've all depended on operating systems we didn't write. We've all deployed software built on millions of lines of code authored by strangers.

AI simply made that reality impossible to ignore.

The responsibility hasn't disappeared.

It's moved.

Instead of taking familiarity as evidence because you typed every character yourself, you establish confidence by inspecting the design, challenging assumptions, measuring behavior, and validating outcomes.

This doesn't absolve the engineer of understanding. It changes the required depth. You may not need to explain every generated line from memory, but you do need to understand the system's boundaries, invariants, dependencies, and failure modes well enough to be accountable for what it does.

That's engineering.

## Judgment Is Becoming the Scarce Resource

The best engineers I've met have never impressed me with how quickly they type.

They impress me with how quickly they notice something feels wrong.

They can review a thousand lines and, through experience, stop at the seven that deserve attention. They know where abstractions leak. They know when benchmarks are lying. They know when a beautiful architecture is solving yesterday's problem.

They ask better questions than everyone else.

AI doesn't replace that.

If anything, it magnifies its importance.

Syntax gets cheaper.

Judgment becomes priceless.

## Standing on Invisible Giants

There's a beautiful irony here.

The engineers most qualified to criticize abstraction are often the same people who built it: compiler engineers, kernel developers, database architects, networking pioneers, language designers, and chip architects.

They spent years making impossibly complicated systems disappear behind clean interfaces—not because they wanted everyone staring at the gears, but because they wanted the rest of us to keep building.

Every abstraction they created became another floor in a building nobody could have constructed alone.

## The Last Honest Abstraction

Every generation believes the abstraction immediately beneath them was the last honest one.

Assembly programmers point to machine code.

C programmers point to assembly.

Framework skeptics point to handwritten C.

Now AI skeptics point to handwritten code.

Ten years from now, someone will publish an article insisting developers don't even understand what their autonomous software factories are doing.

Someone else will nod and say:

> "Back in my day, we actually wrote the prompts ourselves."

And the cycle will begin again.

Because the history of software has never been the history of losing understanding.

It's been the history of redistributing it.

A relatively small number of extraordinary engineers venture into the deepest layers, wrestle complexity into submission, and transform hard-earned understanding into abstractions that millions of others can build upon without mastering every detail beneath them.

Those abstractions aren't evidence that engineering is dying.

They're evidence that engineering succeeded.

Progress has never required everyone to understand everything.

It has always required enough people to understand each layer deeply enough to build the next one—and everyone who uses that layer to understand its promises and failure modes well enough to take responsibility for the result.

The rest of us stand on their shoulders.

And someday, if we do our jobs well enough, someone else will stand on ours.

---

*Editorial note: This article was refined with AI-assisted editorial review, and its cover illustration was generated with AI. The argument, factual review, and final wording remain the author's responsibility.*
