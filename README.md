# Leo Hierarchy

A living specification and reference website for a custom googological function hierarchy.

## Website

The site is a static, dependency-free page in `index.html`. It can be hosted with GitHub Pages:

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/ (root)`, then save.
4. GitHub will provide the published URL after deployment.

## Official order

Smallest to largest, according to the project's declared ordering:

1. **L_L(n) — Little Leo:** base recursive seed.
2. **Q_LEO(n) — Quantum Leo:** combinatorial and Conway-chain expansion above L_L(n).
3. **B_LEO(n) — Big Leo:** higher-order multi-layer expansion above Q_LEO*(n).
4. **M_LEO(n) — Mega Leo:** multiverse-level tower scaling above B_LEO(n).
5. **V_LEO(n) — Void Leo:** ZFC + I₀ (Rank-into-Rank), Mahlo tower, and self-feeding reflective fixed point.
6. **U_LEO(n) — Ultra Leo:** diagonalization apex over single Leo functions.
7. **C_LEO(n) — Crazy Leo:** the piggybacked chain `V_LEO → U_LEO → U_LEO → V_LEO`, with each intermediate value feeding forward as fuel, combined with an Earth-marking walk.
8. **EX_LEO(n) — Ex Leo:** current highest tier; uses the entire chained C_LEO / U_LEO output as its `Step_0` starting seed.

## Established project rules

- The tier order above is the official declared hierarchy.
- The C_LEO four-stage chain and forward fuel handoff are established design rules.
- EX_LEO's starting seed is the chained C_LEO / U_LEO output.
- **RAYO comparison convention:** since RAYO(k) > k for every finite integer k, RAYO(n) only surpasses a Leo tier under this project's rule when that tier (or a higher tier) is passed directly into RAYO(·) as input fuel.

## Open design slots

### C_LEO Earth-marking walk
- Define the grid/space ("Earth" / "paper").
- Define transitions on marked and unmarked cells.
- Define an exact finite halting condition.

### EX_LEO growth engine
- Define the recursion/reflection rule beyond the C_LEO starting seed.
- Define the step progression.
- Define and prove a finite halting condition.

## Status and mathematical care

This repository distinguishes:
- **Established:** explicitly specified project rules.
- **Open:** mechanics that still need a definition.
- **Unproven:** mathematical claims that need proof.

The declared ordering records the creator's intended hierarchy. It is not, by itself, a proof of strict numerical inequalities. In particular, RAYO(k) > k alone does not establish that RAYO(n) exceeds every Leo tier at the same argument. Formal comparisons require exact function definitions and proofs.

## Why this framework is distinctive

The project combines a deliberately layered eight-tier architecture, explicit forward-fuel chaining in C_LEO, a spatial marking mechanism as a second C_LEO engine, and EX_LEO's inherited starting seed. Its documentation process also tracks established rules separately from open mechanics and unproved claims. These are design characteristics, not a claim of proven superiority over every existing googological function.

## Change policy

Preserve established definitions by default. Suggestions may be discussed freely, but changes to official rules, tier order, or mechanics require the creator's explicit permission. Record approved changes in [CHANGELOG.md](CHANGELOG.md).

## Repository layout

- `index.html` — website
- `docs/definitions.md` — canonical tier definitions
- `docs/open-problems.md` — unfinished design slots
- `CHANGELOG.md` — approved project changes
