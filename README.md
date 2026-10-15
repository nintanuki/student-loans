# student-loans

A workspace with one goal: get Frank's federal student loan, about $50,000, cancelled rather than
paid off.

```
inbox/  ->  the tracked docs  ->  outbox/
(drop)      (refined truth)      (the call script, the form, the decision)
records/    (raw letters and exports, local only)
```

Claude is the caseworker. It knows the rules, keeps the paper trail and the payment count, and
gets Frank ready for every call and form. Frank calls, signs and submits. See `CLAUDE.md`.

## The two ways out, in Frank's order

1. **Borrower defense.** A discharge claim that the University of Phoenix misled him.
   `paths/borrower-defense.md`.
2. **PSLF.** Forgiveness after 120 qualifying payments while working for his school district.
   `paths/pslf.md`.

Watched but not chosen: Teacher Loan Forgiveness (`paths/teacher-loan-forgiveness.md`). The
repayment plan itself decides whether a month counts toward PSLF (`paths/repayment-plan.md`).

## The map

| | |
|---|---|
| `STATUS.md` | The living snapshot and the deadlines. Every figure dated. Start here. |
| `TODO.md` | The working list, in tiers, easiest first. |
| `HANDOFF.md` | What happened last session and what to start with next. |
| `decisions.md` | Every ruling, append only, each with its reason. |
| `open-questions.md` | What Claude still needs to ask Frank. |
| `contradictions.md` | Where two facts disagree, kept side by side. |
| `calls/` | One file per call, with names and reference numbers. |
