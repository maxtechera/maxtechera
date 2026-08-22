# Max Techera

I build AI systems that go into production and keep improving after they get there.

Twelve years an engineer. CEO of [LastRev](https://github.com/last-rev-llc) and [AnswerAI](https://github.com/the-answerai), CTO before that, and I still write the code. Professor of software engineering at Universidad ORT since 2018. Montevideo, Uruguay, working with teams anywhere.

`2,110 merged PRs` · `10M+ users reached` · `20,000+ enterprise pages` · `#1 App Store product` · `1,000+ engineers trained`

## What I help companies do

**Get AI past the demo.** Most AI projects stall between a promising prototype and something a
business can depend on, and it's rarely the model's fault. It's failure modes nobody designed, no
way to measure whether the thing worked, and no path from "it ran once" to "it's better this month
than last." That gap is the work I do.

**Build agents that produce commercial results.** Not chat assistants. Systems that run conversion
experiments on live pages, work a revenue pipeline from first idea through close, and turn a backlog
into shipped work with independent checks at every gate.

**Make it survive production.** Narrow interfaces, invariants written down, defined behavior on
every failure, and enough logging to reconstruct what happened. A model is one component in a
system, and it gets treated like any other dependency you don't fully trust.

**Bring a team up to speed.** I've taught software engineering at university since 2018 and trained
over 1,000 engineers on applied AI: Claude Code, MCP servers, agent architecture, and how to tell a
real system from a wrapper around someone's API.

## Track record

**[LastRev](https://github.com/last-rev-llc/lastrev-libraries)** (CEO, previously Director of
Engineering). Co-authored the Next.js and Contentful framework that **Oracle, Dropbox and Coalition**
run their sites on. The architecture I'm proudest of: clients had built roughly **300 content types**
because they kept encoding presentation into content (a hero with a blue button was one type, red
button another). Separating content types from display variants, bridged by a data-mapping layer,
collapsed that to **25** and killed the combinatorial explosion. A unified GraphQL data layer with a
fully typed generated SDK made it framework and CMS agnostic, so the same layer later ran on Vue and
Nuxt and then on Sanity. **6x performance improvement, 20,000+ pages, 10M users reached.**

**[AnswerAI](https://github.com/the-answerai/theanswer)** (founder and CEO). Started when ChatGPT
shipped, built with Brad Taylor and Adam Harris. Began as multi-source RAG, pivoted to agent
orchestration, and now runs at enterprise scale on a multi-tenant TypeScript runtime with
self-hosted and cloud deployments plus usage-based billing. **296 PRs authored.**

**Top Nine.** React Native app with a Node backend that reached **#1 on the US App Store**.

**Teaching.** Professor at Universidad ORT Uruguay since 2018.
[maxtechera.dev](https://maxtechera.dev) covers applied AI engineering for a Spanish-speaking
audience: 1,000+ developers trained, 5,000 on the newsletter.

Twelve years of production systems in TypeScript, Go, Python, C#, Node, React, React Native and
Next.js. Multi-tenant enterprise runtimes, GraphQL data layers, CLIs, MCP servers, mobile apps at
App Store scale.

## What I've built to prove it

Four open-source systems that form one loop: generate something real, measure what happened, learn
from it, run again.

**[overlay](https://github.com/maxtechera/overlay)** runs conversion experiments on any live page,
including one you don't own. It reads the page, proposes variants against components that actually
exist, and scores each with a separate model that had no hand in writing it. Output is a
dependency-free script under 2KB that skips an element rather than guessing when the page changed
underneath it.

**[ship](https://github.com/maxtechera/ship)** boots a nine-agent GTM team on one command and runs
the pipeline from idea through validation, awareness, lead capture, nurture, closing and
measurement. A critic gates every stage with fresh context and no access to the executor's work log.
Nothing deploys without a credential check across 30-plus integrations.

**[orchestrator](https://github.com/maxtechera/orchestrator)** dispatches work against your ticket
board, verifies every deliverable independently, and ships only what passes.

**[memory](https://github.com/maxtechera/memory)** makes runs compound instead of repeat. Three
tiers over an Obsidian vault, with hooks that capture decisions and outcomes automatically, so run
eleven starts from everything run ten worked out.

Also: **[hushdrop](https://github.com/maxtechera/hushdrop)** (zero-knowledge artifact sharing on your
own domain), **[claude-plugins](https://github.com/maxtechera/claude-plugins)** and
**[skills](https://github.com/maxtechera/skills)** (agent tooling for Claude Code, OpenClaw, Gemini
CLI and Codex), **[admirarr](https://github.com/maxtechera/admirarr)** (zero-dependency Go CLI).

## How I think about it

The fundamentals matter more now than they did five years ago. Models got good enough that anyone
can produce code or copy in a minute, which made generation cheap and pushed all the difficulty into
the questions that were always the hard ones: what to build, how it fails, and how you'd know if it
worked.

Most teams use a fraction of what these models can do. They generate a draft, a human decides it's
fine, and it ships. Nothing gets measured, nothing gets remembered, next week starts from scratch.
The version I build closes the loop, and it needs two things that aren't AI problems: a signal you
can trust, which means nothing grades its own output, and memory that survives the session, or
you're running cycle one forever.

## Get in touch

If you're trying to get AI doing real work inside your company and it keeps stalling short of
production, that's the problem I like.

[Email](mailto:maxi.techerag@gmail.com) · [LinkedIn](https://www.linkedin.com/in/maxtechera/) · [X](https://twitter.com/maxtechera) · [Toptal](https://www.toptal.com/resume/maximiliano-techera) · [maxtechera.dev](https://maxtechera.dev)
