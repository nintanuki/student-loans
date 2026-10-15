# Handoff

What happened last session and what to start with next. Newest entry at the top. A new session
reads this first, then `STATUS.md`, then `CLAUDE.md`.

**Only the three newest entries live here.** Older ones go, unchanged, to the top of
`HANDOFF-archive.md`. Do not read that file at clock in.

---

## Thu 10/15 (clock out) - the goal is to fill in the borrower defense form together

### What happened after the Drive export

- Frank asked whether Claude could work up to helping him fill out the borrower defense form.
  Yes, within D-002. Recorded as **D-007**, with the six-step path marked as Claude's suggestion.
  It adjusts D-006: a lawyer or clinic reviews a draft instead of writing it. Frank said "not now."
- Claude flagged once that Frank enrolled in 2006, before most of the FTC findings, so the claim
  rests mostly on what he was told. Not raised as a reason to stop.
- The zip moved from `inbox/` to `records/drive-export-2024/`, next to its extracted copy. Inbox
  is empty.
- Git: the second commit (remote recorded) was pushed by Frank from his side after Claude's push
  was blocked by the auto mode safety check. **Claude's pushes may keep getting blocked.** If this
  one is too, Frank pushes.

### Next steps

1. **The deferment check before ~27 October** (TODO tier 1). It is 12 days out as of 10/15.
2. The studentaid.gov screenshots, which also fill the Jan 2025 to July 2026 gap.
3. Then the borrower defense timeline interview, step 1 of D-007.

## Thu 10/15, later - the Google Drive export

Frank dropped `inbox/student loans-20261015T212845Z-1-001.zip`: his Google Drive "student loans"
folder, 45 files dated Nov 2024 to Jan 2025.

### What was done

- Extracted to `records/drive-export-2024/` (git-ignored). The zip was filed beside it at clock
  out. Local only.
- Text copies made in the session scratchpad to read them; not in the repo.
- Read: Frank's three notes files, the NSLDS export, every EdFinancial and Aidvantage letter, all
  screenshots, the four photos of the rejection letter, the Fresh Start transfer letter, the
  settlement and FTC printouts, first pages of the two scanned evidence packets. The partly filled
  consolidation and IDR forms were checked by field name only.
- **Not opened on purpose:** the 2023 tax return and the Dec 2024 pay stub (proof of income for an
  old IDR form, nothing this repo needs). **Could not open:** the high school transcript
  (encrypted PDF). The blank forms are blank.
- New `history.md`. Rewrote `STATUS.md` and `paths/borrower-defense.md`. Updated `paths/pslf.md`,
  `paths/teacher-loan-forgiveness.md`, `contradictions.md` (C-003 reframed, C-004 and C-005 new),
  `open-questions.md`, `TODO.md`.

### What the documents changed

- **Phoenix dates are Dec 2006 to Feb 2009**, not "withdrew 2014." C-004.
- **Every loan is from Phoenix.** Q-004 answered.
- **Sweet v. Cardona deadline was missed.** Frank knew this in Jan 2025. Borrower defense would be
  an individual claim. The application was never filled in.
- **PSLF was at 0 months in Nov 2024.** The real clock starts with the 2025 consolidation (est).
- **The 5.875% rate looks wrong.** C-005.

### Privacy

- The first pass at reading the letters printed Frank's name, mailing address and two servicer
  account numbers into the session (the filter missed the header lines). Nothing was written to a
  file. The filter was tightened after that.
- The partially completed consolidation form in the export holds his SSN, driver license number
  and date of birth. It is in `records/` and `inbox/` here (ignored), but it also lives in his
  Google Drive. Worth Frank knowing.

### Next steps

Unchanged: the deferment check before ~27 October, then the studentaid.gov screenshots, which
now also fill the Jan 2025 to July 2026 gap.

## Thu 10/15 - repo created

Frank asked for a new repo dedicated to getting rid of the student loan, modeled on the other
repos in `C:\workspaces`.

### What was built

The standard skeleton (`CLAUDE.md`, `README.md`, `STATUS.md`, `TODO.md`, `decisions.md`,
`open-questions.md`, `contradictions.md`, this file, `.gitignore`), plus folders specific to this
work: `paths/` (one file per way out), `calls/` (one file per phone call), `reference/`.

Claude's role here is **caseworker**: knows the rules, keeps the paper trail and the count, gets
Frank ready. Frank calls, signs, submits. Modeled on `health`'s secretary boundary, because the
borrower defense application is sworn and a wrong move with a servicer can be hard to undo.

### Where the facts came from

Everything was copied from `financial`: `STATUS.md`, `decisions.md` (D-013, D-027),
`open-questions.md` (Q-013), `TODO.md`, `settings.py` (`STUDENT_LOANS`),
`reference/student-loans-and-pslf.md` and `docs/LOG.md`. **Nothing was changed in `financial`.**
The student loan material is now in two places; whether `financial` keeps its copy, trims it to a
pointer, or leaves it is Frank's call.

### Things Claude added that Frank has not seen yet

- **PSLF buyback** (`paths/pslf.md`), which may let the deferment months be bought back later.
  This softens the cost Frank accepted in D-005 without reopening it. From Claude's memory, to
  verify.
- **The Sweet v. Cardona question** (`paths/borrower-defense.md`, Q-003). Whether Frank ever
  applied, and when, changes how a claim is handled. From Claude's memory, to verify.
- **The 2025 law** (`reference/rules-as-of-2026.md`). Labelled as Claude's memory throughout.

### Not done

- Nothing outstanding on git. First commit pushed to `nintanuki/student-loans` on 10/15.

### Next steps

1. The deferment check before ~27 October (TODO tier 1).
2. The studentaid.gov screenshots: PSLF count, any borrower defense application, the loan list.
