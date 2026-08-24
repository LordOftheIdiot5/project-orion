# Contributing to Project Orion

Thank you for helping design a free, private, lifelong personal AI mentor.
This repository is in **Phase 0**: open protocol and reference architecture.
There is no production client yet. Most useful work right now is specification,
safety, pedagogy, and on-device architecture — not feature spam.

Please read [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) and
[GOVERNANCE.md](GOVERNANCE.md) before opening a pull request.

## What we need most

| Area | Examples |
|------|----------|
| On-device ML | Quantized mentor models, NPU budgets, offline eval |
| Privacy & crypto | Device-first inference, E2E sync, threat models |
| Protocol | Capability negotiation, local memory, upgrade rails |
| Pedagogy | Child-safe tutoring loops, anti-addiction constraints |
| Systems | Android / low-end phone runtime, mesh / satellite ops |
| Deployment | Village co-op playbooks, OEM / NGO packaging |
| Docs | Whitepaper clarity, translations, worked examples |

If you are unsure where to start, open a GitHub Discussion or Issue with the
question you actually have. Do not wait for a perfect RFC.

## How to propose a change

1. **Search existing issues** so we do not fork the same idea twice.
2. **Open an issue** for anything larger than a typo. Protocol changes need
   discussion before code.
3. **Fork and branch** from `main`. Use a short name:
   `docs/amina-story`, `spec/offline-memory`, `fix/readme-links`.
4. **Keep PRs small.** One idea per pull request.
5. **Write for the next reader.** Explain *why*, not only *what*.
6. **Link the issue** in the PR body.

## Document conventions

- Protocol and architecture text lives in Markdown, licensed Apache 2.0.
- Treat [WHITEPAPER.md](WHITEPAPER.md) as the public thesis. Do not silently
  rewrite the mission. Tighten claims, add evidence, or mark hypotheses as
  hypotheses.
- Normative protocol language (when we add it) uses RFC 2119: MUST, SHOULD,
  MAY.
- Do not add telemetry, ads, growth hacks, or dark patterns — even as
  “optional.”

## Local workflow

This repo is documentation-first. There is no build step.

```bash
git clone https://github.com/LordOftheIdiot5/project-orion.git
cd project-orion
```

Preview Markdown on GitHub or with any Markdown viewer. Keep line lengths
readable; do not wrap tables into noise.

## Review

Maintainers review for:

- Alignment with the non-negotiable principles (free, private, offline-capable,
  non-manipulative, auditable, culturally adaptive)
- Technical honesty — no invented benchmarks
- Child-safety and privacy impact
- Clarity for people who do not live in this repo

A contribution can be accepted, requested-changes, or parked as a discussion
if it is important but not Phase 0.

## License of contributions

By submitting a pull request, you agree that your contribution is licensed
under the [Apache License 2.0](LICENSE), with no additional terms.

## Contact

- Issues and pull requests: this GitHub repository
- Conduct reports and private contact: **Loticoins@proton.me**
