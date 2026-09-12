# Strong River v1.2 — Salym + Anti-Salym

## Canon

Yaros builds a Product Factory, not a collection of isolated projects.

### Seven Sage facets

Every substantial decision is evaluated on:

1. Clarity
2. Value
3. Actionability
4. Trust
5. Connectivity
6. Measurability
7. Durability

### Five Sage questions

1. Can this be solved once in Core instead of multiple products?
2. Can at least two products/integrations reuse it?
3. Does it remove manual work or duplication?
4. Is the result measurable with evidence?
5. Does it avoid a new isolated stack/API/plugin/team?

## Product Factory engines

- Requirement / Intent Engine
- Architecture / Contract Engine
- Build Factory
- AI Factory
- Integration Factory
- Evidence Factory
- Learning Factory

## Factory KPIs

- Time-to-Working-Flow
- Time-to-New-Adapter
- Reuse Ratio
- Core Adoption
- Evidence Coverage
- Cost per Successful Flow
- Manual steps Idea -> Production
- Repeat Error Rate

## Anti-Salym

Before SCALE attack the system with eight failure modes:

1. Platform Trap — platform work without a working product
2. Fake Reuse — shared Core with only one real consumer
3. Mega-Core — common layer becomes a monolith
4. Human Bottleneck — critical path depends on one person
5. Evidence Theater — dashboards/reports without E2E proof
6. Adapter Leakage — product-specific logic leaks into Core
7. AI Leakage — products bypass common AI Gateway/budget controls
8. Local Fix — bug is fixed locally without prevention rule/test

Any critical FAIL blocks SCALE.

## Definition of Done

A change is DONE only when it has:

- owner;
- contract/API where applicable;
- test;
- staging/sandbox proof;
- telemetry/logging;
- acceptance evidence;
- reuse check;
- prevention update for repeated failure classes.

## Reference chain

`Order/Document -> Yaros -> QR/Payment -> Bank -> payment.paid -> KKM/Receipt -> ERP/1C -> reconciliation -> telemetry/evidence`

The first implementation proves the mechanism. The second proves reuse.
