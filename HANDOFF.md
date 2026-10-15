# Handoff

What happened last session and what to start with next. Newest entry at the top. A new session
reads this first, then `STATUS.md`, then `CLAUDE.md`.

**Only the three newest entries live here.** Older ones go, unchanged, to the top of
`HANDOFF-archive.md`. Do not read that file at clock in.

---

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

- No git commit and no GitHub remote. Frank has not created the repo on GitHub yet.

### Next steps

1. Frank creates the private GitHub repo; Claude adds the remote, commits and pushes.
2. The deferment check before ~27 October (TODO tier 1).
3. The studentaid.gov screenshots: PSLF count, any borrower defense application, the loan list.
