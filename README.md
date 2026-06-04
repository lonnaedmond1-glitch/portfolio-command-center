# Field Operations Scorecard

**[Live demo →](https://portfolio-command-center-orpin.vercel.app/)** · part of [lonnaedmond.com](https://lonnaedmond.com)

An operations dashboard that scores every active job on health so the worst problems surface first. Built for the question leadership actually asks: *"how are the jobs doing?"* — answered at a glance instead of in a meeting.

## What it does

- Rules-based health scoring across every active job: margin trend, schedule position, field-report freshness, AR aging
- Exception-first layout — at-risk jobs surface before healthy ones
- Persona walkthroughs (Ops Lead / CFO / Executive) showing the reasoning behind the design
- Fleet, compliance, sales pipeline, and weekly scorecard views in one place

## Stack

React / Next.js, deployed on Vercel. The demo runs on synthetic data; the production version of this architecture runs against a live operational data layer and is private.

## Status

Active development: this project is being upgraded with an AI diagnosis layer — LLM tool-calling against [ai-tooling](https://github.com/LonnaEdmond/ai-tooling) (an MCP server with 31 typed tool contracts), with structured diagnosis outputs and an evaluation suite. Follow the build in `BUILDLOG.md` as it lands.
