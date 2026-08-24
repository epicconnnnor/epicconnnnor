## Hi there 👋

<!--
**epicconnnnor/epicconnnnor** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
# Connor Chen

Backend and infrastructure engineer. UMass Amherst CS, May 2026. Based in the Boston area.

I like systems where the interesting problems are about failure — what happens when a connection drops mid-stream, when a message gets delivered twice, when a consumer falls behind. Most of what I build ends up being an excuse to work on delivery guarantees, backpressure, and observability.

Currently looking for backend, infrastructure, SRE, or network engineering roles.

---

## What I'm building

**[Candle Agent](https://github.com/epicconnnnor/Candle-Agent)** — Event-driven microservices pipeline for market analysis. Streams live bars over a persistent websocket, computes bar-geometry features, runs a two-stage LLM analysis, and pushes results to a live chart over SSE.

Four independently deployable services on NATS JetStream with at-least-once delivery, durable pull consumers, and explicit ACK-after-persist. SQLite in WAL mode for concurrent read/write, Prometheus metrics per service, the whole thing in Docker Compose. Runs end to end with zero API keys via a mock LLM provider, so you can clone it and see it work in one command.

Rebuilt from a monolithic Python app — the distributed rewrite was the point.

`Python` · `NATS JetStream` · `SQLite (WAL)` · `Prometheus` · `SSE` · `Docker`

---

## Interests

Distributed systems, networking protocols, and SRE-adjacent infrastructure. Studied networking under Jim Kurose at UMass, which is a large part of why this is the direction I went.

Things I care about in practice: idempotency, graceful degradation, exponential backoff with jitter, metrics you can actually alert on, and READMEs that let someone run the thing without asking you a question.

---

## Currently

- Adding CI/CD, a React/TypeScript frontend, and AWS deployment to Candle Agent
- Working through algorithm practice in Java
- Reading more about consensus and replication than is strictly necessary

---

## Reach me

[LinkedIn](https://linkedin.com/in/connorchen1229) · [Email](mailto:epicconnor1229@gmail.com)

English and Mandarin.
