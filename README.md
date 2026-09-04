## Aleksandr Lepesii

Software engineer, eight years. I build production systems — and for the last two,
systems built on language models, together with the measurement that says whether
they work.

Most of the work sits in the unglamorous middle: retrieval and guardrails, evaluation
harnesses, model gateways, instrumentation, CI that catches a regression before a
customer does. I care more about a number being defensible than about it being good.

**Now:** building and running **Vouch** solo, end to end — a live product where a model
drafts and an evaluation loop decides whether the draft is grounded in its sources.
Judge accuracy sits at 93–96% against a hand-labelled 342-claim set. I quote that as a
range because the rare class is 39 examples and a single claim moves the miss rate 2.5
points.

### What's here

| | |
|---|---|
| [**crow**](https://github.com/leansii/crow) | Detects drift between design intent and what was actually implemented — structure, styles, rendering and E2E coverage |
| [**conductor-claude**](https://github.com/leansii/conductor-claude) | Agent workflow for specifying, planning and implementing features |
| [**earshot**](https://github.com/leansii/earshot) | Feedback service in Go: an LLM enriches and deduplicates incoming reports, a human approves before anything is filed |
| [**vitals**](https://github.com/leansii/vitals) | Cloudflare Worker that health-checks several projects on a cron and alerts only on state change |
| [**ux-knowledge**](https://github.com/leansii/ux-knowledge) | 170 UX/UI patterns as a knowledge base for AI-assisted interface work |
| [**sotto**](https://github.com/leansii/sotto) | Local-only meeting transcripts from Meet and Zoom captions. No servers, nothing leaves the machine |
| [**vuegram**](https://github.com/leansii/vuegram) | Vue 3 components for Telegram Mini Apps, themed from Telegram's own variables |

Mostly Python, TypeScript and Go. Kubernetes and GCP underneath. Bangkok, UTC+7.

[leansii.com](https://leansii.com) · [LinkedIn](https://www.linkedin.com/in/aleksandr-lepesii/) · fresh-hawk0h@icloud.com
