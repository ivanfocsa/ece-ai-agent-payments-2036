# FRANCE 2036 — Autonomous AI Payments

**Your AI Can Spend Your Money. But Who Is in Control?**

ECE engineering-school communication campaign, set in **France in 2036–2040**. Hypothetical academic policy client: the **French Ministry of the Economy and Finance**. This is an **independent student simulation**, not an official government project, and has no real financial transactions.

<!-- Campaign media assets will be uploaded separately. -->

## The idea

By 2036, AI agents could routinely pay for small digital services within budgets set by people. An assistant might buy a €0.10 API request, data, or computing power. But what if an unverified service asks for **€35**? The audience has to decide whether the agent should pay, wait for approval, or reject.

**The important distinction:** x402 is a **current** HTTP 402-based payment protocol first introduced in 2025. Our 2036 wallet, regulations, outcomes and risks are **future scenarios or campaign proposals**, not current products or official government commitments.

## Project package

The full binary asset package (PowerPoint, Word/PDF, narrated video, and PNG posts) is currently available as a downloadable archive in the project handoff. This GitHub repository is being populated with the editable source materials; missing binary assets should not be interpreted as available here.

## Deliverables

| Folder | Deliverable | Status |
|---|---|---|
| [`research/`](research/) | Four-page English research paper (DOCX and PDF), APA author–date citations | Draft for team review |
| [`slides/`](slides/) | Sixteen-slide PowerPoint with a **75-second embedded video**, clickable ethical decision branches, and PDF export | Complete |
| [`video/`](video/) | 75-second 16:9 opening video (synthetic narration + silent version), four-voice script | Complete; natural voices recommended |
| [`social/`](social/) | Three finished campaign posts, overview, editable English captions | Complete mockups |
| [`live-demo/`](live-demo/) | Responsive interactive €50 / €35 wallet decision simulator | Complete; **fake money only** |
| [`presenter/`](presenter/) | Four-person 10-minute talk track and final submission checklist | Complete for rehearsal |
| [`sources/`](sources/) | APA bibliography and fact/scenario boundary | Complete |
| [`reference/`](reference/) | Original seven-page assignment design brief | Reference only |

## Run the interactive demo

The demonstration is a static website. No build step, dependencies, accounts or wallet are required.

**Fastest:** open `live-demo/index.html` in a recent browser.

**Or start a local web server:**

```bash
python3 -m http.server 8000
# Open http://localhost:8000/live-demo/
```

Then:
1. Set the automatic spending limit (default **€1**).
2. Press **Run safe €0.10 purchase** to show a verified API transaction; wallet becomes **€49.90**.
3. Show the **€35 unknown-merchant request**, then ask the audience to choose one outcome.
4. Explore **auto-pay / ask / reject**. Click **Reset** between runs to compare outcomes.
5. Let the class vote **YES / NO / DEPENDS**, then debate **protection vs innovation**.

**No payment processing exists anywhere in this project.** All outcomes are illustrative, and vote selections stay on the local page only.

## Present in 10 minutes

| Time | Action |
|---|---|
| 0:00–1:15 | Play the video without explaining it. |
| 1:15–3:05 | Future technology, x402 precursor, benefits. |
| 3:05–5:05 | French stakeholders and vote 1. |
| 5:05–7:05 | €50 wallet demo and three branches. |
| 7:05–9:05 | Ethical debate, vote 2, ethical frameworks. |
| 9:05–10:00 | Three policy actions for France. |

All four students have speaking roles; see [`presenter/10_MINUTE_PRESENTATION_GUIDE.md`](presenter/10_MINUTE_PRESENTATION_GUIDE.md).

## Evidence and research integrity

Main evidence sources include:
- Reppel, Dalal, & Kim (2025): [Coinbase x402 launch](https://www.coinbase.com/developer-platform/discover/launches/x402).
- Cloudflare (2026): [Agentic payments](https://developers.cloudflare.com/agents/tools/payments/) (x402 and MPP).
- OECD: [Transparency and explainability](https://oecd.ai/en/dashboards/ai-principles/P7) and [Accountability](https://oecd.ai/en/dashboards/ai-principles/P9).
- French supervision and data protection: AMF, ACPR, Tracfin and CNIL (see the full [APA bibliography](sources/APA_REFERENCES.md)).

Do not confuse 2025–2026 facts with 2036 hypothetical predictions. All numbers in the classroom scenario (€50, €0.10, €35, €1) are **fictional demonstration amounts**.

## Before submitting to the teacher

**Important:** The teacher requires written English that reflects students' own natural level and has warned that directly pasted AI text may be rejected. The four-page paper is a **research draft**, not a final submission that should be forwarded unchanged. Students should review, revise, verify and own the wording, especially in each assigned section. Practise the spoken presentation without reading slides or notes.

The teacher's instructions require the document **before presentations begin** on the class day, sent to `tcooper@omnesintervenant.com`. This repository does not send email on the students' behalf.

## Technology

- Static HTML, CSS and vanilla JavaScript (no framework or npm dependencies).
- PowerPoint/PDF research deliverables.
- H.264 MP4 kinetic-typography video.
- PNG social-media artwork (1080 × 1350).

## Publishing

This repository is designed for a personal GitHub account. Given its status as an unfinished academic submission, **private visibility is recommended** until the group approves sharing it. Once a repository is created, all files can be pushed with ordinary `git` commands; GitHub Pages can optionally serve the static demo from the `live-demo` directory using a Pages workflow if made public or if the account supports private Pages.

---

*Independent educational project. No endorsement or official involvement by the French government, Coinbase, Cloudflare or any other named organization.*