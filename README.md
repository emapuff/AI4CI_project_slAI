# Credit Card Pickpocket Trap Detector

An end-to-end, AI-enabled **simulated banking environment** that intercepts fraudulent
credit-card transactions in real time. An autonomous LLM-based agent acts as the lead
fraud investigator: it correlates two asynchronous data streams, orchestrates downstream
ML models to assess risk, and executes binding decisions (`ALLOW` / `CHALLENGE_OTP` /
`FREEZE_CARD`) that feed back into and alter the simulation -- closing the loop.

> **Course project -- AI4CI.**

📄 **Full project proposal:** [docs/Project AI4CI slAI team.pdf](docs/Project%20AI4CI%20slAI%20team.pdf)

---

## Team

| Name |
| --- |
| Magui Anca-Elena |
| Moisă Clementina-Ioana |
| Toda-Puiuleț Emanuela-Coralia |

---

## Why this project

Modern card fraud is distributed, high-speed and adaptive: once a card is compromised,
attackers fire rapid, geographically spread transactions before traditional systems react.
We build a **closed-loop** simulator where an agent's freeze decision actually stops the
simulated attacker -- so we can measure not just detection accuracy but the real cost of
each decision (missed fraud, customer friction, support-queue load).
