---
title: "OpenClaw Jakarta Meetup #5: From Demos to Real-World AI Agents"
description: "OpenClaw Jakarta Meetup #5 brought developers and agentic AI users together to discuss useful, measurable, and responsible agents."
date: "2026-07-23"
thumbnail: "./assets/openclaw-jakarta-meetup-5-thumbnail.png"
lang: en
translationKey: openclaw-jakarta-meetup-5
authors:
  - name: "IndopenSource Maintainers"
    github: "IndopenSource"
tags:
  - community
  - open-source
  - artificial-intelligence
  - openclaw
status: published
---

OpenClaw Jakarta Meetup #5 took place in South Jakarta on Thursday, July 23, 2026. Supported by DANA Indonesia, which provided the venue and refreshments, the event brought together developers, engineers, and users of OpenClaw and *agentic AI* to explore how AI agents are being applied to real-world problems.

The speakers shared first-hand experience building products, from browsers for AI agents and property search to financial advisory systems. The strongest thread of the evening, however, came from Hannes Rudolph, OpenClaw Community Manager: building an agent that can perform useful work does not mean handing the entire process over to AI.

## Use AI Where It Is Actually Needed

Vince Iswara, CEO of DANA Indonesia, opened the event with a reminder that AI must be used responsibly. AI compute is not cheap, so it should be reserved for problems that genuinely benefit from it rather than simple tasks that can be solved more efficiently.

That message also appeared in a session by Raden Muhammad Hadi, Senior Data Scientist at DANA Indonesia, on a *Financial Advisory Agent Stack*. The system uses several subagents with distinct responsibilities, including planning the execution, carrying out tasks, providing financial literacy context, and reviewing results with different model types.

Hadi compared several models to match each task with the right capability. The system also uses statistical methods such as TBATS for forecasting. The presentation demonstrated why an agentic system in finance cannot rely on a single model and a single instruction.

## Hannes Rudolph: Start with Small Loops

Joining through Zoom, Hannes opened his session to questions from the audience. He argued that a more practical approach to agentic systems is to start with small loops, give the agent planning and checking steps, and then study its results and mistakes.

Model evaluation is an important part of that process. Each model change should be benchmarked so that an improvement in one area does not quietly damage another capability. Even when using a *vibe coding* approach, developers still need to understand the process and inspect the code line by line.

His message was straightforward: focus on the outcome, build checks into the process, and do not expand the automation before it performs well within a smaller scope.

<div class="flex justify-center">
  <img src="https://raw.githubusercontent.com/IndopenSource/Blog-IndopenSource/main/content/2026/07/assets/openclaw-jakarta-meetup-5.png" alt="Attendees at OpenClaw Jakarta Meetup #5" loading="lazy">
</div>

## Three Real-World Views of AI Agents

Zen Aufa Bahalwan introduced Camoufox as a way to handle browser obstacles such as CAPTCHAs, *forbidden* responses, and bot-detection systems. Camoufox gives agents an *anti-detect* browsing capability. Its use still needs to remain within lawful and responsible boundaries.

Okza Pradhana, from the Data Engineering Indonesia community, presented PropGen, an agent orchestration system for property search. The demo showed how an agent can collect and process information that would otherwise be spread across many sources.

Hadi's personal financial advisory system illustrated a different set of requirements: a strong knowledge base, model selection based on capability, and a review layer before results reach the user.

The three sessions showed that the value of an AI agent is not measured by the number of models it uses or the length of its *workflow*. Its value appears when the system can complete real work, be inspected, and operate within clear boundaries of responsibility.

OpenClaw Jakarta Meetup #5 ultimately became a place to compare what has been built, what remains difficult, and what the community can improve together. DANA's support and the presence of the OpenClaw community brought an enterprise perspective and the experimental spirit of *open source* into the same room.
