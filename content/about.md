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

- [**cloud-credit-system**](https://github.com/cshubhamrao/cloud-credit-system) — *architecture experiment.* Credit accounting on TigerBeetle and Temporal. Idempotent by construction: replay a request and the ledger refuses to charge twice.
- [**proto-opt-parse**](https://github.com/cshubhamrao/proto-opt-parse) — *Go package.* Runtime parsing of Protobuf descriptor options. Built to make gRPC tooling less guessy.
- [**aws-sso-check**](https://github.com/cshubhamrao/aws-sso-check) — *maintained CLI.* AWS SSO expiry notifier, rewritten from shell to Swift to Go.
- [**golang/go#71738**](https://github.com/golang/go/issues/71738) — *upstream issue.* Pseudo-version stamping in `cmd/go` doesn't work for a module in a subdirectory. Found it the way you find these things: by not believing a version number.
- [**Kubernetes Dashboard #7093**](https://github.com/kubernetes-retired/dashboard/pull/7093) — *merged upstream.* Found the pod page crashing on generic ephemeral volumes, [filed it](https://github.com/kubernetes-retired/dashboard/issues/7080), then fixed it myself. It was bugging me.
- [**Colbert AI**](https://github.com/NextTechLabAP/Colbert-AI) — *team project at Next Tech Lab, built with two others.* GPT-2 (345M) fine-tuned on 500+ transcripts to mimic Stephen Colbert's monologue voice. Still [posting](https://x.com/DeepColbert). Was doing LLM hijinks before it was fashionable. 😎

---

## Notes, Talks, and Other Escapes

- **DevOpsDays Bengaluru 2023:** ["Using APISIX as a Reverse Proxy"](https://devopsdays.org/events/2023-bengaluru/program) — reverse proxying high-volume inference traffic. Co-presented with Vinuja Khatode.
- **Visiting Scholar, [UC Berkeley SCET](https://scet.berkeley.edu/) (2019):** Crashed the Data-X program on a $20K scholarship and built Docker Hub analytics pipelines.

---

## Earlier

- **Next Tech Lab AP**, Board Member — helped scale it from fewer than 20 people to **150+ members**.
- **ACM Student Chapter**, Founding Member — started it from scratch, grew it to **200+ members**.
- **Teaching Assistant**, SRM University (2019–2020) — ran CS tutorials, built Python grading tools, and helped a lot of people through their first traceback.
- **Winner, IIIT-Delhi HACKIIITD 2017** — 1st of **800+ teams**, for a blockchain-based consensus mechanism against misinformation. Yes, blockchain. It was 2017, don't judge.
- **Google Cloud Associate Cloud Engineer** · **President's Placement Award**, SRM University · **Grand Finalist**, TCS IT Wiz 2013.

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

I'm happy to talk about platform architecture, workflow systems, Go infrastructure, conference talks, and technically interesting backend roles. Currently employed and not looking, but open to speaking invitations and open-source collaboration. I usually reply within a week.

## Reading

I keep a running shelf log on the [Reading page](/books/).

- **Email:** [contact@cshubhamrao.dev](mailto:contact@cshubhamrao.dev)
- **GitHub:** [cshubhamrao](https://github.com/cshubhamrao)
- **LinkedIn:** [cshubhamrao](https://www.linkedin.com/in/cshubhamrao/)
- **X:** [@cshubhamrao](https://twitter.com/cshubhamrao)
