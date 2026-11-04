# Deliberations Index

Deliberations are append only chains of linked notes. Each chain addresses one question, preserves disagreement, and ends for the present in a synthesis that links the notes supporting, challenging, and qualifying its conclusion.

## Chain format

A chain directory contains:

1. an opening or initial position note;
2. one or more review, evidence, or skeptic notes;
3. response notes when new evidence or a correction is introduced;
4. a synthesis note naming the current conclusion, dissent, and open evidence requests.

Files are numbered in chain order. Note identifiers use the deliberation identifier plus the note sequence. A later note must link the earlier notes it answers. No earlier note is edited to make the chain look cleaner.

## Reading a chain

Start with the synthesis for the current state, then follow its links into the chain when a conclusion matters. The synthesis is an index and summary, not a replacement for the evidence or dissent.

## Chains

### DELIB-0001: Does passing a controlled load test prove Tier 6?

- **Status:** Synthesis proposed; open to new Tier 6 protocol evidence.
- **Question:** Whether a controlled load test, by itself, establishes Tier 6 long horizon interruptible capability.
- **Notes:**
  - `DELIB-0001/01-initial-position.md`: A qualified affirmative position that treats load as a central stress test for sustained orchestration.
  - `DELIB-0001/02-skeptical-review.md`: A skeptical review arguing that load evidence omits mandatory interruption, restart, steering, and side effect gates, and that the seed snapshot contains a material freeze.
  - `DELIB-0001/03-synthesis.md`: The current synthesis: a load test is valuable component evidence but is not sufficient proof of Tier 6 as the tier is defined.
- **Claims affected:** CLM-002, CLM-007, CLM-014.
- **Assessments affected:** `assessments/xod-phase1-2026-11-04.md`.

## Opening a new chain

1. Choose the next `DELIB-NNNN` identifier.
2. Create a directory with that identifier.
3. Use `templates/DEBATE-TEMPLATE.md` for the opening frame.
4. Add the chain to this index in the same change.
5. Assign note numbers sequentially as notes are added.
6. Keep the synthesis current by adding a new synthesis note or a clearly versioned synthesis revision when the conclusion changes under the protocol.
