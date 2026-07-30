---
title: "About Me"
description: "Senior Software Engineer building the systems other systems depend on: control planes, APIs, workflow engines, and schema-carried correctness."
date: 2024-12-15
lastmod: 2026-07-30
draft: false
showToc: true
TocOpen: true
schemaProfilePage: true
---

Hey! I'm Shubham — a Software Engineer who builds the backend for your backends. Control planes, APIs, workflow engines: the stuff that sits behind the stuff users actually see. It's my job and my passion, and the passion came first.

I like systems where **failure is a first-class feature**: idempotency, retries, backpressure, graceful degradation.
I like it better when the mistake never gets a chance to fail — the rule that lives in the schema instead of in someone's memory, the test that locks out a class of bug instead of the one instance you just found.
I'm happiest when a graph goes down because we fixed it, not because we hid it.

I've had the chance to speak at **DevOpsDays Bengaluru 2023** (because apparently I have opinions about API gateways now), and once won a hackathon by building a blockchain thing before it was cool. Also did a semester at **UC Berkeley's Sutardja Center**, soaking up the Silicon Valley chaos.

Currently obsessed with: policy as schema data instead of code you have to remember to call, invariants that fail at import time rather than in production, and reviewing generated code at its failure paths — that's where it's thin.

**Bio (short version):** I build the platform layer other engineers build on: control planes, workflow DSLs, entity reconciliation, and schemas that refuse to let you ship a mistake. I talk about API gateways at conferences and still get a kick out of hacking on protocol compilers. Community builder, systems tinkerer, and far too interested in what protobuf descriptors will let you get away with.

---

## What I've Built

### @ Lyric.tech

**Senior Software Engineer, Core (Platform)** — *2025–Present*

- Core backend services in **Python** and **TypeScript**: entity reconciliation, workflow DSLs, Temporal workflows, and the platform and data APIs behind them.
- Design focus: correctness under change — evolvable schemas, retries that are safe to repeat, and operational clarity (alerts that mean something).
- Getting a front-row seat to supply chain reality: messy inputs, real-world constraints, and a lot of "it depends".

### @ Tune AI (formerly NimbleBox.ai)

**Software Engineer** — *2020–2025*

The arc says more than the title does: ML scripts → services I owned end to end → the Go control plane, its Kubernetes operator and the IaC underneath → shared platform libraries → in-process frameworks that shipped with the argument for them written down.

- Designed the gRPC backbone for model serving, schema-first, so clients and servers could evolve without a flag day. It carried **100M tokens/day** and latency dropped **40%**.
- Built document processing on batch inference with replayable runs — a failed batch could be re-run without double work. **100K documents daily**, **54%** cheaper, precision-recall held at **95%**.
- Wrote a reusable cron scheduler that runs in-process, and shipped it with a "Why?" README making the case against Kubernetes CronJobs for our workloads. Killed **70%** of the boilerplate scheduling code. You're welcome, future me.
- Led the **OpenTelemetry** adoption because debugging distributed systems without traces is pain.
- Shipped a GenAI architecture for a UAE event management company — automated **40%** of their workflow and cut proposal creation time by **20%**.
- Where it all started: ML pipeline orchestration, containerized model serving with FastAPI, and liberating models from Jupyter notebooks (not a fan).

---

## Side Projects

A mix of things I've built, fixed, or accidentally broke:

- **cloud-credit-system** — credit accounting on TigerBeetle and Temporal. Idempotent by construction: replay a request and the ledger refuses to charge twice.
- **proto-opt-parse** — Runtime parsing of Protobuf descriptor options in Go. Built to make gRPC tooling less guessy.
- **aws-sso-check** — AWS SSO expiry notifier, rewritten from shell to Swift to Go.
- **Colbert AI** — GPT-2 (345M) fine-tuning to mimic Stephen Colbert's monologue voice using 500+ transcripts. Was doing LLM hijinks before it was fashionable. 😎
- **k8s-dashboard fix** — Contributed a fix to the Kubernetes Dashboard. It was bugging me.
- Also found a bug in the Go compiler's release note item's functionality. No big deal.

---

## Notes, Talks, and Other Escapes

- **DevOpsDays Bengaluru 2023:** APISIX as reverse proxy for high-volume inference traffic. Co-presented with Vinuja Khatode.
- **Visiting Scholar, UC Berkeley SCET (2019):** Crashed the Data-X program on a $20K scholarship and built Docker Hub analytics pipelines.

---

## Back in College

### Next Tech Lab AP — *Board Member*
Helped scale from a scrappy group of **<20 people to 150+ members**. Lots of recruiting, mentoring, and figuring out how to build a culture around exploring cool stuff.

### ACM Student Chapter — *Founding Member*
Started the chapter from scratch and grew it to **200+ members**. Organized workshops, hack nights, and way too many pizza-fueled coding sessions.

### Teaching Assistant — *SRM University (2019–2020)*
Ran tutorials for CS courses, built grading scripts in Python (because I'm lazy), and helped students debug their first tracebacks. Ensured a generation of students didn't quit Python. You're welcome.

---

## Honors & Awards

### Winner, IIIT-Delhi HACKIIITD (2017)
**1st place out of 800+ teams**. Built *"Reliability of Media"* — a blockchain-based consensus mechanism to combat misinformation. Incentivized honest votes with crypto rewards and locked consensus on-chain. Yes, blockchain. It was 2017, don't judge.
### Other Wins
- **Google Cloud Associate Cloud Engineer** (Valid until 2026)
- **President's Placement Award** from SRM University
- **Grand Finalist** — TCS IT Wiz 2013 (ask me tech trivia)

---

## Tech I Actually Use

| | |
|---|---|
| **Daily Drivers** | **Go** (control planes, tooling), **Python** (services, ML infrastructure), **TypeScript** (platform services) |
| **Backend** | gRPC + protobuf (including custom options), ConnectRPC + buf, FastAPI, Temporal, Apache APISIX |
| **Infrastructure** | Kubernetes (operators, CRDs, Kubebuilder), Docker, AWS, GCP, Terraform, Pulumi |
| **Data Stuff** | Kafka, RabbitMQ, PostgreSQL, Redis, TigerBeetle |
| **Observability** | OpenTelemetry, distributed tracing, structured logging |

---

## Let's Talk

Building something interesting? I'm always up for a conversation about distributed systems, backend architecture, or why gRPC is underrated.

## Reading List

Trying to keep tabs on what I'm reading? I keep a running log on the [Books page](/books/).

- **Email:** [contact@cshubhamrao.dev](mailto:contact@cshubhamrao.dev)
- **GitHub:** [cshubhamrao](https://github.com/cshubhamrao)
- **LinkedIn:** [cshubhamrao](https://www.linkedin.com/in/cshubhamrao/)
- **X:** [@cshubhamrao](https://twitter.com/cshubhamrao)
