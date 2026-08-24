# Agentic AI Requirements Toolkit

**Live site: [nmohanaraman.github.io/agentic-ai-requirements-toolkit](https://nmohanaraman.github.io/agentic-ai-requirements-toolkit/)** · **DOI: [10.5281/zenodo.22082816](https://doi.org/10.5281/zenodo.22082816)**

Nine original, field-built frameworks for specifying, bounding, and evidencing AI systems that act on their own — and for deciding what AI takes, what the analyst keeps, and where to grow. Each framework ships with an explanation, a worked example, and a fill-in template.

Built by [Mohanaraman Namasivayam](https://www.linkedin.com/in/mohannamasivayam) — Business Analyst / AI Requirements & Governance Practitioner. IEEE Senior Member · Member, IIBA · ORCID [0009-0002-5676-5590](https://orcid.org/0009-0002-5676-5590).

## Why this exists

Requirements engineering has rested for decades on a quiet assumption: software does what it is told. Agentic AI breaks that assumption — an agent chooses its own steps, so the specification must constrain the space of acceptable behavior instead of enumerating flows. These frameworks were built in practice, on enterprise data platforms, to fill that gap for working analysts and product owners. None requires writing code; all require thinking differently about what a requirement is.

At the center of the toolkit are three boundary classes: **MAY ACT** (independently, within thresholds), **MUST ASK** (named approver, defined SLA), and **MUST NEVER** (prohibited, with rationale). Autonomy expands by documented decision, never by drift.

## Collection 1 — Specifying agentic systems

First published in [“The Business Analyst's Guide to Agentic AI Requirements”](https://www.modernanalyst.com/Resources/Articles/tabid/115/ID/7213/The-Business-Analysts-Guide-to-Agentic-AI-Requirements.aspx), ModernAnalyst, August 23, 2026.

| ID | Framework | What it does |
|----|-----------|--------------|
| F-01 | [Agentic Requirements Stack](https://nmohanaraman.github.io/agentic-ai-requirements-toolkit/frameworks/agentic-requirements-stack.html) | Six layers that define what a complete specification means for a system that chooses its own steps |
| F-02 | [Autonomy Boundary Canvas](https://nmohanaraman.github.io/agentic-ai-requirements-toolkit/frameworks/autonomy-boundary-canvas.html) | Turns “the agent can help with X” into explicit, stakeholder-approved authority |
| F-03 | [Tool Contract Specification](https://nmohanaraman.github.io/agentic-ai-requirements-toolkit/frameworks/tool-contract-specification.html) | Every API, query, or system call the agent can invoke is a capability grant — and each grant gets a contract |
| F-04 | [Escalation & Handoff Matrix](https://nmohanaraman.github.io/agentic-ai-requirements-toolkit/frameworks/escalation-handoff-matrix.html) | Replaces “human in the loop” with routing rules |
| F-05 | [Agentic Traceability Ledger](https://nmohanaraman.github.io/agentic-ai-requirements-toolkit/frameworks/agentic-traceability-ledger.html) | From requirement to runtime evidence: proof that everything the agent did was specified |

## Collection 2 — The AI-augmented analyst

First published in [“The Irreplaceable BA: How to Stay Essential in an AI-Augmented World”](https://www.batimes.com/articles/the-irreplaceable-ba-how-to-stay-essential-in-an-ai-augmented-world/), BA Times, July 29, 2026.

| ID | Framework | What it does |
|----|-----------|--------------|
| F-06 | [BA Value Pyramid](https://nmohanaraman.github.io/agentic-ai-requirements-toolkit/frameworks/ba-value-pyramid.html) | A map of where your time creates value — and where the automation zone begins |
| F-07 | [Task Triage Matrix](https://nmohanaraman.github.io/agentic-ai-requirements-toolkit/frameworks/task-triage-matrix.html) | For each task: augment, automate with governance, protect, or elevate |
| F-08 | [Skill Investment Matrix](https://nmohanaraman.github.io/agentic-ai-requirements-toolkit/frameworks/skill-investment-matrix.html) | Where to spend development time: invest, maintain, build selectively, or divest |
| F-09 | [5-Day AI Sprint](https://nmohanaraman.github.io/agentic-ai-requirements-toolkit/frameworks/five-day-ai-sprint.html) | One task, real data, documented failures, and a decision — in five days |

## Repository structure

- `index.html` — landing page (both collections)
- `frameworks/*.html` — one page per framework (9), permanent URLs
- `templates/*.docx` — downloadable working templates
- `style.css` — shared stylesheet

Static site, no build step. Hosted on GitHub Pages from the `main` branch.

## License and citation

All frameworks and templates are licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — reuse and adapt freely with attribution. The toolkit is archived on Zenodo — cite it as: Namasivayam, M. (2026). *Agentic AI Requirements Toolkit* (Version 1.0). Zenodo. https://doi.org/10.5281/zenodo.22082816. Each framework page also carries a pre-written citation; per-framework deposits with individual DOIs are planned.

If you use a framework on a real initiative, attribution is the only ask — and hearing how it performed is the welcome extra: [nmohanaraman@gmail.com](mailto:nmohanaraman@gmail.com).

*The views expressed here are the author's own, and all examples are illustrative composites rather than descriptions of any specific employer, client, or engagement.*
