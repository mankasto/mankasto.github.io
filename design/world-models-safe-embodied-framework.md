# Six-capability framework for safety-critical embodied world models

## Figure purpose

Communicate the six progressively stronger capabilities required to move world models from plausible generation to verified action in safety-critical embodied systems.

## Classification

- Primary paper type: survey / position paper.
- Secondary type: safety-critical embodied AI conceptual framework.
- Figure type: six-level capability progression with a restrained execution-feedback loop.

## Frozen user correction

The visual center is the six capability levels—not the manuscript organization, chapter mapping, technical-route taxonomy, or benchmark structure:

**Generation → Modeling → Understanding → Reasoning → Decision → Verification**

## Source-to-figure ontology

| Element | Source claim | Role | Treatment |
|---|---|---|---|
| Safety-critical embodied setting | Autonomous vehicles and robots act in open physical environments | Context | Referenced by two compact vector scene marks |
| Generation | Produce plausible future observations | Capability level 1 | Expanded progression cell |
| Modeling | Represent structured world state and dynamics | Capability level 2 | Expanded progression cell |
| Understanding | Preserve objects, relations, constraints, and uncertainty | Capability level 3 | Expanded progression cell |
| Reasoning | Compare action-conditioned counterfactual consequences and risks | Capability level 4 | Expanded progression cell |
| Decision | Rank candidate behaviors and select, defer, or reject | Capability level 5 | Expanded progression cell |
| Verification | Check evidence, constraints, and runtime safety before execution | Capability level 6 | Expanded progression cell |
| Safe embodied action | Verified decision changes the environment | Outcome | Small terminal shield/action mark |

## Role-causality ledger

| Actor | Action or state | Affected actor | Response | Consequence | Evidence/update target |
|---|---|---|---|---|---|
| Embodied agent | Candidate action | Physical environment and other agents | Environment evolves | Alternative future state and risk | Reasoning and decision |
| Decision system | Select, defer, or reject | Embodied agent | Executes or withholds action | Safe or unsafe outcome | Verification and feedback |
| Runtime verifier | Checks evidence and constraints | Proposed decision | Accepts, revises, or blocks | Bounded execution behavior | Execution record / verified adaptation |

## Relation semantics

- Main solid arrow: conceptual capability progression, not a literal software pipeline.
- Thin internal arrows: each capability adds decision-relevant responsibility to the previous level.
- Dashed branch inside Reasoning: counterfactual future comparison.
- Teal connector from Verification to safe action: verified execution.

## Reference brief (local manuscript figures)

The reference set is local-only and drawn from the supplied draft.

| Reference | Useful attribute | Rejected attribute |
|---|---|---|
| Fig. 1, p. 3 | Exact six-stage capability order and cross-domain framing | Manuscript chapter strip and dense photographic thumbnails |
| Fig. 3, p. 8 | Restrained semantic accents | Dashboard-style box repetition and issue rows |
| Fig. 5, p. 16 | Compact paper density and disciplined connectors | Routes/mechanisms/outcomes taxonomy |
| Fig. 8, p. 21 | Explicit verified feedback | Photographic repetition and many operational stages |
| Fig. 9, p. 22 | Large labels and concise progression | Handwritten type and decorative softness |

## Information budget

- Expanded: all six capability levels, each with one title, one short scientific question, and one compact evidence mark.
- Referenced: autonomous driving and robotics at the entry; safe action at the exit.
- Omitted from the thumbnail: the safety-gated feedback loop, to keep the six-level progression visually dominant at small size.
- Omitted: manuscript sections, taxonomy of technical routes, model lists, benchmark names, detailed metrics, and future-work categories.

## Figure-family contract

- White canvas with dark navy text and thin structural rules.
- Early predictive capabilities use muted blue; cognitive comparison uses restrained amber; safety authority uses teal.
- Red appears only as a tiny unsafe branch within reasoning or rejection evidence.
- Clean sans-serif typography with a two-level hierarchy and one annotation size.
- Thin 1.5–2 px outlines, 5–8 px corner radii, compact gaps, and consistent triangular arrowheads.
- Refined 2D vector marks; no photography, gradients, shadows, logos, or neural-network decoration.
- Cells are aligned scientific stages, not application buttons or dashboard cards.

## Planner

**Goal:** Show six progressively stronger capabilities from plausible future generation to verified safe action.

**Components:** Driving/robotics context; six ordered capability levels; small action-conditioned branch comparison inside Reasoning; verified safe action.

**Layout:** Wide 1200 × 650 canvas. A single ascending six-stage band fills the visual center. The left context enters Generation. Each stage is slightly taller than the previous one, encoding stronger capability without implying that deployed modules must execute serially. A thin arrow above the cells labels the conceptual progression. Verification connects to a terminal shield/action mark.

**Relations:** Each level retains the previous predictive competence and adds a more decision-relevant responsibility. Reasoning compares consequences of candidate agent actions. Decision ranks and may select, defer, or reject. Verification independently checks evidence and constraints before action.

## Stage labels

1. **Generation** — What could the future look like?
2. **Modeling** — What state and dynamics govern it?
3. **Understanding** — What objects, relations, and constraints matter?
4. **Reasoning** — How do candidate actions change risk?
5. **Decision** — Which action should be selected or rejected?
6. **Verification** — Is the decision supported and safe to execute?

## Stylist

Use a compact conceptual progression, not a poster. Give the six stages equal horizontal width and progressively greater height. Retain generous inner padding but narrow inter-stage gaps. Use only small line-art evidence marks: generated frames, structured state nodes, object/constraint relation marks, branching futures, ranked actions, and a shield/check. Keep the six titles readable at a 190 px-wide thumbnail; supporting questions may become secondary at that size without affecting the macro story.

## Skeleton specification

- Canvas: 1200 × 650.
- Small context zone: x=35–150, y=260–470.
- Six-stage progression: x=175–1060, y=155–500; six equal 135 px cells with 12 px gaps and stage tops rising from y=265 to y=155.
- Main progression arrow: x=190–1050, y≈115.
- Safe action terminal: x=1080–1170, y=225–420.
- Bottom region remains open so the capability progression dominates the thumbnail.
- Short framework title at x=35, y=45; no subtitle or chapter labels.

## Negative constraints

Do not show the manuscript outline, chapter numbers, survey organization, method families, long model lists, datasets, benchmark names, metric lists, or open-challenge taxonomy. Do not depict the six levels as a concrete neural architecture or promise a safety guarantee. Avoid photos, screenshot crops, detailed vehicles, mascots, badge numbering, colored card walls, glossy effects, giant arrows, and paragraph-length labels.

## QA gates

- Check A — pass: the six levels and their responsibilities are directly supported by the abstract, Section 1.4, Sections 2.1–2.4, Section 4, and Sections 8–9; no model architecture is invented.
- Check B — pass: the ascending continuous progression directly matches the manuscript's capability thesis and the user's correction; manuscript organization and nonessential taxonomies are excluded.
- Check B2 — pass: the grayscale skeleton makes the six-level progression and terminal safety outcome recognizable without color; stage bounds, connectors, and feedback corridor do not overlap.
- Check C — pass: the final render has no overlaps or clipping; the six titles, stage order, progression arrow, context, and safe-action outcome remain recognizable in both the 2400 × 1300 export and a 380 × 206 thumbnail preview.
- Check D — not applicable because this is a standalone website thumbnail.
