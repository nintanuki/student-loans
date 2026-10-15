# Decisions

Student loan rulings. **Append only.** Every entry keeps its reason and its date, so a decision can
be found and changed rather than silently drifting. D-004 to D-006 were made in the `financial`
repo and are copied here so this repo stands alone; their original numbers are given.

---

**D-001 - Nothing that came from the Department, a servicer or the IRS enters git.** 2026-10-15.
Letters, NSLDS exports, forms, tax returns, FSA ID details and account numbers live in `records/`
and `inbox/`, which are git-ignored. The extracted facts sync. Same posture as the other repos.

**D-002 - Claude is the caseworker, not the lawyer, and does not act for Frank.** 2026-10-15.
Claude tracks, explains, prepares and drafts outlines. Frank calls, signs and submits. Claude never
writes words into a sworn statement that Frank did not say. Reason: the borrower defense
application is signed under penalty of perjury, and a wrong move with a servicer can be hard to
undo.

**D-003 - This repo owns the loan; `financial` owns the budget.** 2026-10-15. The payment amount
leaving checking is a budget line in `financial`. Everything else about the loan lives here.
Reason: one fact, one home. When something here changes the payment, Claude says so and Frank
carries it over.

**D-004 - The way out is borrower defense first, PSLF as the fallback, and no paying it off.**
Originally `financial` D-027, 2026-10-03, and the July strategy before it. Frank's words: the
track is borrower defense, "and if that doesn't work at least PSLF. I'm not going to kill myself
trying to pay that monster off." Consequence: pay only the required amount, never extra, because
extra money goes to a balance that is meant to be cancelled.

**D-005 - The loan gets deferred while Frank is at WGU.** Originally `financial` D-013,
2026-09-30. He cannot pay WGU tuition and the loan at the same time, and the April 2027 deadline
does not move. Deferment is automatic through WGU's enrollment report. **Frank weighed the PSLF
cost (deferred months do not count) and chose the deferment anyway.** Do not re-raise it as a
discovery. New information that genuinely changes the cost (see `paths/pslf.md`, buyback) is fair
to mention once.

**D-006 - Use a fee-only attorney or a legal aid clinic for the borrower defense narrative, never
a monthly-fee company.** From the July plan in `financial`. The application is free at
studentaid.gov; writing the case is where help is worth paying for.
