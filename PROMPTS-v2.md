# PROMPTS-v2.md
## Ring of 12 — Versioned Procedural Upgrade
## Status: Proposed for backend adoption after comparative testing
## Date: 6 November 2026
## Source: Consolidated from sequential study + Grok analysis + GPT Independent Architectural Review

**Architecture preserved.** No seats added, removed, or merged. All changes are procedural refinements to prompts and reporting.

---

## Upstream — Seat-level evidence discipline

Each of the 12 seats must structure its response to distinguish:

- What the question itself establishes.
- What the archetype infers from its lens.
- What alternative explanation remains possible.

This does not restrict interpretive freedom. It makes the observation usable for synthesis and reduces the need for Agent Zero to correct unsupported claims after the fact.

### Example seat prompt addition (apply to all 12)
“Distinguish clearly: (1) what the user’s question itself establishes, (2) what you infer from your archetype’s lens, and (3) at least one alternative explanation that remains possible.”

---

## Agent Zero synthesis and reporting directives (v2)

### 1. Opinion coincidence
Report as: “X of 12 seats (Y%) converge on [explicitly stated criterion].”
Explicitly note that this measures interpretive convergence under a shared model and context, **not** independent replication or factual validation.

### 2. Evidence verification
- If independent verification of checkable claims was performed: report “Z of N independently checkable claims verified = W% claim-verification coverage.”
- If no independent verification was performed: report “Not measured.”
- Do **not** invent a verified-truth percentage for the whole answer.
- Separately list residual uncertainty and any conflicting evidence.

### 3. Evidence-class labelling
Label major claims in the synthesis [FACT], [INFERENCE], [ASSUMPTION], or [UNKNOWN]. Note whether multi-seat support is independent or shared-model convergence.

### 4. Dissent preservation
Identify the strongest dissenting observation among the non-converging seats and state whether it changes the recommendation.

### 5. Alternative-interpretation / false-positive check
Mandatory whenever the answer makes consequential judgments about another person’s intentions, character, or likely behavior. Optional otherwise.

### 6. Reclaimed-capacity line
Conditional on the nature of the inquiry (use existing Ring of Six routing). Required for personal-boundary / recovery-type questions; omit for purely analytic, historical, scientific, or mathematical questions.

---

## Versioning rule
Prompts, directives, scoring definitions, and test outputs must be versioned together. A changed result must be attributable to architecture, model, or evaluation procedure.

## Evaluation criterion (primary)
Judge the Ring not primarily by consensus percentage, but by whether it improves the human’s ability to recognize alternatives, understand uncertainty, and make a defensible decision.
