# Project Orion Governance

Orion belongs to no corporation and no government. The protocol, reference
implementations, and safety specifications are licensed under
[Apache License 2.0](LICENSE) so anyone can implement, audit, and fork them.

This document describes how we make decisions while the project is still a
seed, and how stewardship should look if the protocol leaves this repository.

## Current phase (Phase 0)

Until a multi-stakeholder foundation exists, this GitHub repository is the
canonical public workspace.

| Role | Who | What they do |
|------|-----|----------------|
| Curator | LordOftheIdiot5 | Merge to `main`, keep the thesis coherent, name maintainers |
| Maintainers | Listed in this file as they are appointed | Review PRs in their working area, apply the Code of Conduct |
| Contributors | Anyone | Issues, RFCs, patches, translations, critique |

Phase 0 decisions use **rough consensus**: if serious technical or ethical
objections remain, we do not merge. Silence is not consent for privacy,
child-safety, or manipulation-related changes.

## Working groups (when staffed)

Modeled loosely on the IETF: groups produce documents, not products.

1. **Privacy & Safety** — on-device inference, encryption, anti-manipulation,
   age-appropriate design.
2. **On-device ML** — model size, quantization, eval, upgrade path.
3. **Pedagogy** — lifelong teaching, local languages, cultural adaptation.
4. **Connectivity & Deployment** — offline core, mesh, satellite co-ops,
   OEM / NGO packaging.
5. **Protocol** — capability negotiation, local memory, sync, versioning.

A working group may exist as a GitHub Discussion category and a set of
issues before it has a charter. Charters are merged as Markdown RFCs.

## Decision rules

1. **Non-negotiables are not votes.** Free forever, private by default,
   offline-capable core, no manipulation, open audit, cultural adaptation
   without imposition. See the [whitepaper](WHITEPAPER.md).
2. **Running text beats slogans.** A claim in the README that contradicts
   the protocol docs is a bug.
3. **Privacy and child-safety objections block merge** until addressed or
   explicitly deferred in writing.
4. **Forking is a feature.** If consensus fails, a fork is legitimate.
   The name “Project Orion” for official protocol releases stays with the
   stewards of this repository (and later the foundation).
5. **No paywalls in the core.** Implementations may offer paid hardware or
   hosting; the mentor protocol itself MUST remain free to run locally.

## Toward a foundation

The intended long-term steward is a multi-stakeholder foundation — governments,
NGOs, companies, researchers, and communities — operating like the IETF does
for internet protocols:

- Open mailing lists / GitHub for every working group
- Published RFCs
- Rough consensus and running code
- No single vendor veto

Until that legal entity exists, do not treat tweets, decks, or private chats
as protocol. If it is not in this repository (or a linked, dated RFC), it is
not canonical.

## Amendments

Changes to this governance document require a pull request, at least seven
days of open comment, and curator (later: foundation board) approval.
The Code of Conduct may be enforced immediately without waiting on that
window.

## Contact

- Public: GitHub Issues and Discussions
- Private / conduct: Loticoins@proton.me
