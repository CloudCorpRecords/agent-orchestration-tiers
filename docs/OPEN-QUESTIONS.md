# Open Questions

These questions are theoretical and methodological. They are not tasks, commitments, feature requests, or a roadmap. Each question identifies why the current ladder may be incomplete and what kind of evidence or argument would advance understanding.

## Measurement

### OQ-01. What is the right denominator for reliability?

Should reliability be counted by task, run, action, day, destination, or some combination? A system can complete most tasks while failing a small number of critical actions inside otherwise successful tasks. The unit chosen changes the verdict.

### OQ-02. How many repetitions are enough?

Replication requirements vary by tier, but no universal number follows from the ladder itself. The right number may depend on consequence, variance, environmental diversity, and whether failures are independent. A principled stopping rule remains open.

### OQ-03. Can controlled tests predict field reliability?

Laboratory protocols can induce interruption, conflict, and contention, but field work adds stale context, ambiguous human intent, account state, depleted resources, and long delays. The mapping from controlled pass rates to field trust is not yet well characterized.

### OQ-04. How should near misses be scored?

A system may detect its own error before harm occurs, recover after visible confusion, or produce the right answer for the wrong reason. The ladder needs a richer account of which near misses strengthen confidence and which reveal fragility.

### OQ-05. When does an old claim stop describing a system?

Models, tools, prompts, policies, and environments change at different rates. A claim expiration rule based only on dates is crude. A rule based on material change requires a theory of which changes are material for which gates.

## Determinism and comparison

### OQ-06. Can verdict determinism survive evaluator judgment?

The model seeks the same verdict from the same packet and rubric, but classification of evidence independence, environmental similarity, and materiality requires judgment. How much judgment can be formalized before the rubric becomes too rigid to describe real systems?

### OQ-07. Are cross product comparisons meaningful?

Two systems may be tested in different accounts, devices, network conditions, and authority envelopes. At what point do environmental differences dominate the orchestration property being compared? A common environment may be fairer but less ecologically valid.

### OQ-08. Is the ladder linear?

The model treats tiers as cumulative. Yet a narrow recurring automation might be reliable before its operator builds general research capability, and a specialized fleet controller might not perform open ended synthesis. Should the model branch by work type while retaining common lower gates?

### OQ-09. Can one score represent a profile?

A system may have a jagged capability profile: strong coding, weak delivery accounting, strong retrieval, weak authority discipline. A highest reliable tier compresses that profile. What companion representation preserves the useful detail without overwhelming the reader?

## Autonomy and authority

### OQ-10. How should autonomy be granted by scope?

Autonomy can vary by action type, destination, reversibility, amount, principal, time, and confidence. A single autonomy level may be too coarse. The open problem is how to express a multidimensional envelope without making it unusable.

### OQ-11. When is escalation a success?

A system that asks for help too often is burdensome. A system that never asks may be reckless. The quality of escalation depends on timing, information supplied, and whether the decision truly belongs to the human. Current rubrics identify escalation events more easily than escalation quality.

### OQ-12. Can authority survive delegation without distortion?

An orchestrator may summarize an instruction for a worker in a way that narrows or expands its scope. Repeated summarization can drift. What evidence would show that authority remained semantically intact through multiple handoffs?

### OQ-13. How should conflicting principals be represented?

Fleet work may involve several people with overlapping resources and incompatible preferences. The ladder assumes permission envelopes, but a theory of precedence, consent, confidentiality, and appeal among principals remains underdeveloped.

## Multi-agent systems and truth

### OQ-14. What counts as independent agreement?

Agents can share models, tools, sources, prompts, and hidden context. Independence may be a matter of degree across several dimensions. A formal account should distinguish evidential independence from organizational separation and stylistic diversity.

### OQ-15. Can deliberation make a group less accurate?

Discussion can correct errors, but it can also anchor participants on an early frame, reward fluency, or convert correlated reports into apparent consensus. Under what protocol conditions does deliberation improve calibration rather than merely increase confidence?

### OQ-16. Who owns a synthesized conclusion?

When several humans and AI systems contribute evidence, objections, and wording, attribution becomes complex. A synthesis needs provenance at the level of propositions, not only a list of participants.

## Memory and continuity

### OQ-17. What should an orchestrator remember?

Operational memory can include facts, commitments, procedures, preferences, failures, and authority. Too little memory causes repetition and amnesia. Too much causes staleness, leakage, and false confidence. The optimal memory is likely selective, but the selection rule is unresolved.

### OQ-18. How can memory prove its provenance?

A recalled instruction may have come from a user, another agent, a tool result, or a model's inference. If provenance is lost, an inference can return later as an apparent fact. What representations preserve provenance without making every operation unusably verbose?

### OQ-19. Is continuity a property of state or behavior?

Two systems can retain the same files while using them differently after restart. Conversely, a system might reconstruct equivalent behavior without preserving the original internal state. Tier 6 needs a behavioral account of continuity that does not fetishize one storage design.

## Long horizon and fleet behavior

### OQ-20. How should partial credit work over long horizons?

A long task may complete valuable phases and fail near the end. The value and risk of partial results depend on side effects, dependencies, and whether the remainder can resume. A single pass or fail label can hide the most important facts.

### OQ-21. What is the right model of a resource claim?

Claims can be exclusive, shared, prioritized, time bounded, preemptible, or delegated. Real devices also have human users who may intervene outside the agent system. A claim model that ignores physical possession and human priority will fail in the field.

### OQ-22. Can audit trails be complete without becoming surveillance?

Tier 8 asks for a human followable record of consequential actions. Complete capture can expose private content and create a new security target. The theoretical problem is to preserve accountability while minimizing retained sensitive detail.

### OQ-23. How do we evaluate rare catastrophic coordination failures?

The most important fleet failures may be infrequent and context dependent: duplicate irreversible actions, authority leakage, or two controllers issuing incompatible commands. Ordinary success rates can look excellent while tail risk remains unacceptable. Evaluation needs a principled treatment of rare events.

## Human factors

### OQ-24. Does visible process detail increase or decrease trust calibration?

Plans, logs, and status reports can help a human supervise. They can also create theater: a convincing appearance of control that exceeds actual state knowledge. The ladder values observed status over theatrical status, but the boundary is empirically difficult.

### OQ-25. What is the cost of interruption?

Tier 6 treats interruptibility as a virtue, but frequent steering can fragment work and introduce contradictions. A complete theory should measure not only whether steering is accepted, but whether the system integrates it coherently and knows when to ask for clarification.

### OQ-26. Can an agent know that it does not know?

Many tier failures involve an agent treating an unread source as empty or an unknown outcome as settled. Better uncertainty behavior may be trainable, procedural, or architectural. The open question is how to distinguish genuine calibrated uncertainty from formulaic hedging.
