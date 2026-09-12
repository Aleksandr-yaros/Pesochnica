# Yaros Product Factory / Strong River

**Status:** CANONICAL SANDBOX

This repository is the top-level engineering sandbox for the Yaros Product Factory strategy.

## North Star

We do not optimize isolated products. We optimize the system that produces products.

`SYSTEM -> CORE -> SDK -> MODULE/ADAPTER -> PRODUCT -> EVIDENCE -> SYSTEM vNEXT`

Every new product must become faster, cheaper and more provable than the previous one.

## What belongs here

- Strong River / Salym / Anti-Salym rules
- Product Factory Core contracts
- Adapter SDK rules
- AI OS rules
- Reference end-to-end flow
- Pulsar reporting and evidence rules
- Programmer reporting template

Product-specific implementation remains in its own repository. This repository defines the shared mechanism and acceptance rules.

## Mandatory rule

Before opening a new product branch, answer:

1. Which shared Core/SDK does this reuse?
2. Which factory bottleneck does it improve?
3. Which two or more products benefit?
4. How will end-to-end evidence be produced?
5. What prevents the same class of error from repeating?

If these are unclear: `CLOUD -> REWORK`.

Start with [START_HERE.md](START_HERE.md).
