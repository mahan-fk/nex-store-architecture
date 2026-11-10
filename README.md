# nex-store — System Architecture & Case Study

**nex-store** is a production-ready, bilingual (FA/EN, RTL) AI-agent e-commerce SaaS built for small merchants. It was built solo from the ground up over 9 months.

## Why is the code private?
The source code is kept private by design to protect proprietary business logic and ensure data security. However, I believe in radical verifiability. This repository serves as the public proof of the system's scale, safety, and engineering depth.

## Technical Highlights
- **Architecture:** NestJS backend, hybrid LangChain + LangGraph orchestration, and Vercel AI SDK for transport.
- **Scale:** ~167K LOC, 100 registered tools in a governed registry.
- **Safety & Privacy:** 13 hard-deny rules for financial safety, 44 PII detectors, 15 Generative UI primitives.
- **Testing Rigor:** 2,500+ unit tests, 195 e2e tests, and 169 eval scenarios.
- **Delivery:** 865 commits across 167 active days (solo).

## The Case Study (PDF)
For a deep-dive into the engineering decisions, trade-offs, and the race-condition fix I contributed upstream to the Vercel AI SDK, read the full 10-page technical case study:

👉 **[Download / View MahanFakhimi_Case_Study.pdf](./MahanFakhimi_Case_Study.pdf)**
