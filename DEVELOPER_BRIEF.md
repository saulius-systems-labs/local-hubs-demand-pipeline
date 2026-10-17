# Developer Brief: Local Hubs Demand Pipeline

**Status:** Discovery and prototype planning only. This document is not authorization to launch a service, contact prospective customers, spend money, publish content, or access production systems. The local-hub landing-page sections and copy are not ready for publication. Discuss and explicitly approve them with the project owner only after the developer is confirmed and the contract is signed. Until then, the concept is reference material only; do not present its copy, claims, offers, venue details, or calls to action as approved.

## Source material

- [Vilnius local hub landing-page concept (Google Doc)](https://docs.google.com/document/d/1FlrGlW_IFY8nORlPJ2RSP4PQmrb9nBXVOTyp5CY9qtc/edit?usp=sharing) — supplied planning input; its claims and proposed offer have not been independently verified or approved for publication.
- [Project #2: Local Hubs Demand Pipeline & AEO Directory](https://github.com/orgs/saulius-systems-labs/projects/2)
- [Repository overview](README.md)

The source concept proposes a localized directory with Learn / Build / Improve routes, a local representative profile, a coworking venue, case studies, a sponsorship offer, FAQs, and structured data. These are concepts for discussion after the developer is confirmed and the contract is signed, not approved requirements, facts, or publishable content. In particular, do not draft for publication or publish page sections, venue relationships or addresses, endorsements, representative credentials, deployment metrics, prices, offers, availability, privacy/compliance guarantees, or partner names before the project owner has explicitly approved the content and its evidence.

## Delivery sequence and acceptance

### W1 — Governance, consent, and evidence (first; blocks W2 and W3)

**Deliverables**
- Approved discovery scope naming the initial city, audience, user problem, and accountable human reviewer.
- Evidence register containing each proposed public claim, source URL, verification date, permitted wording, and approval state.
- Written data map covering collection purpose, minimum fields, consent, access, retention/deletion, and human review. If intake is not needed for the directory prototype, record that decision.
- Success measures and explicit out-of-scope list.

**Accept when** the owner/reviewer approves these artifacts; city, audience, and success measures are explicit; no unsupported claims or personal lead data are required to proceed.

### W2 — Useful local directory pilot (after W1)

**Deliverables**
- Confirmed CMS platform and content model/field map, if authorized for technical discovery.
- After the developer is confirmed, the contract is signed, and the project owner has explicitly approved the sections and copy: one original pilot page for the approved city. Before that gate, use placeholders only and do not treat prototypes as approved content.
- After the content approval gate: evidence-backed copy and source register; Learn / Build / Improve paths with approved destinations or clearly marked placeholders. Before approval, no publishable page copy; unresolved content must remain visibly placeholder-only.
- Responsive and accessibility review, structured-data validation where applicable, and a short content-quality/duplication review.

**Accept when** the developer-confirmation and signed-contract gate is met, the project owner has approved the page sections and copy, each factual claim has a current approved source, links and structured data match verified content, and accessibility/mobile checks have recorded results. Until then, only explicitly authorized technical discovery using placeholders may proceed; no public content or launch is approved.

### W3 — Consent-aware intake prototype (after W1; synthetic data only)

**Deliverables**
- Approved field contract and form states, including validation, errors, optional communications consent, retention/deletion behavior, and human-review ownership.
- Non-production prototype and test results using synthetic data only.
- Abuse, privacy, and security review notes; documented data flow and explicit confirmation that no production credentials, live customer records, CRM writes, or automated customer messages are used.

**Accept when** the prototype passes the agreed tests and review; all integrations are mocked or isolated in a non-production environment; no personal or production data is processed.

### W4 — Pilot review and go/no-go (after W2 and W3, or explicitly document a decision not to build W3)

**Deliverables**
- Pilot readout against W1 success measures, including evidence quality, accessibility, usefulness, and feedback with appropriate consent.
- Written go/no-go decision, named approver, unresolved risks, and separately approved next scope, budget, ownership, and launch criteria if applicable.
- Written permission and evidence for any partner, venue, commercial, or customer-result claims proposed for publication.

**Accept when** the decision and rationale are recorded and no launch, partnership, price, payment, or delivery commitment is implied without explicit written approval.

## Developer working rules

- Start with W1; do not start public-page copy or publishing while blocking decisions remain open. Landing-page sections and copy require a separate explicit discussion and approval after the developer is confirmed and the contract is signed. Any authorized earlier technical discovery must use placeholders only.
- Keep changes small and reviewable. Work through issues and pull requests; link implementation to its issue and request a named maintainer review before merge.
- Record assumptions, source links, verification dates, test evidence, and remaining decisions in the relevant issue. Use Project #2's **Evidence status** field: **Not assessed** → **Source verified** → **Approved for publication**. Source verification alone is not publication approval.
- Use placeholders for unresolved facts and integrations. Do not invent URLs, contact details, schedules, partner status, sample results, CMS credentials, or production configuration.
- Keep personal data, customer records, credentials, tokens, and production secrets out of issues, commits, and this repository. Use synthetic fixtures for the intake prototype.

## Decisions required before implementation

The project owner/maintainer must answer these in the W1 issue or explicitly mark them out of scope. Landing-page section and copy decisions are deferred until the developer is confirmed and the contract is signed, then require explicit owner approval before publication:

1. Which city is the first pilot, who is the target user, and what user problem has priority?
2. Is the first deliverable a research artifact, a static page, or a working CMS-backed page? Which repository/site and CMS are in scope?
3. Which Learn / Build / Improve destinations and calls to action are approved? If unavailable, should those routes be omitted or shown as non-functional placeholders?
4. Is the proposed representative, venue, address, schedule, and partner relationship real and approved for public use? Who supplies written permission and authoritative sources?
5. Are the case studies and their numerical outcomes documented, attributable, and permissioned? If not, omit them; do not present draft examples as real deployments.
6. Are the sponsorship price, claimed asset value, pilot-slot count, retainer, and any payment terms approved? If not, omit commercial claims from implementation.
7. Is a form required in this discovery phase? If yes, what exact fields, consent wording, lawful basis, reviewer, retention period, deletion method, abuse controls, and synthetic-only destination are approved?
8. What are the CMS schema and actual 38 field definitions? The source document refers to a 38-field schema and an 18-field representative schema but does not provide the complete field inventory, types, requiredness, validation, or ownership.
9. What are the acceptance targets for content originality, accessibility, responsive behavior, structured data, and pilot success? Who signs off each?
10. Who is the issue owner and reviewer for each workstream, and what timeline/budget (if any) is authorized? No owners or due dates are currently assigned.

## Current project structure assessment

Project #2 has four open workstream issues and a project-level evidence gate. They express the right sequence and safety boundaries, but the issues have no assigned owners, reviewers, or repository milestones; the current task descriptions do not enumerate the artifacts above or clearly encode W1 → W2/W3 → W4 dependencies. Use this brief to make those outputs explicit. Do not infer dates, resourcing, production scope, or approval from the planning concept.