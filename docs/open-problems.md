# Open design slots

These sections are intentionally incomplete. Do not invent rules to fill them. Ask the creator for missing mechanics and obtain explicit permission before changing established definitions.

## C_LEO Earth-marking walk

The walk is part of C_LEO and is combined with its established piggybacked chain:

`V_LEO → U_LEO → U_LEO → V_LEO`

The exact walk rules remain to be defined.

### A. Grid / space
Questions to settle:
- What does "Earth" or "paper" represent mathematically?
- Is the space finite from the start?
- What are its coordinates, adjacency rules, and boundary conditions?
- What is the initial marked-cell configuration?

### B. Transition rule
Questions to settle:
- What does the process do on an unmarked cell?
- What does it do on a marked cell?
- How does the current state determine the next position?
- How does marking interact with the C_LEO chain and fuel values?

### C. Finite halting condition
Questions to settle:
- What exact state ends the walk?
- Why must that state be reached?
- Can the number of transitions be bounded or defined recursively?
- What proof establishes termination for every allowed input?

## EX_LEO growth engine

Established starting point: the complete chained C_LEO / U_LEO output is EX_LEO's `Step_0` seed.

### A. Recursion / reflection
Define the exact rule that expands EX_LEO beyond its starting seed.

### B. Step progression
Define how `Step_0` generates `Step_1`, and how each later step receives its input or fuel.

### C. Finite halting condition
Define the stopping condition and provide a proof that the process halts after finitely many steps for every allowed input.

## Status vocabulary

- **Established:** explicitly supplied and accepted as a project rule.
- **Open:** not yet defined; requires creator input.
- **Proposed:** an idea suggested for consideration, not part of the official hierarchy unless approved.
- **Unproven:** a claim for which a proof has not yet been supplied.
