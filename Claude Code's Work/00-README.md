# README — Interview Guidance, Distilled

## What this is

This folder distills six full-length books on interviewing, self-promotion, and job search into one compact, cross-referenced system. The goal: when you're staring down a real interview, you should be able to hand a downstream LLM three things — this folder, your resume, and a job description — and get back a tailored 60-second pitch, your 3 core messages, and answers that hold up even for questions you never rehearsed.

**Source books** (all in the parent folder, read-only, untouched):
1. *101 Great Answers to the Toughest Interview Questions* — Ron Fry
2. *Interview Intervention* — Andrew LaCivita
3. *Get That Job* — Thea Kelley
4. *301 Best Questions to Ask on Your Interview* — John Kador
5. *Brag!* — Peggy Klaus
6. *What Color Is Your Parachute?* (2011) — Richard Nelson Bolles

(Two files in the parent folder — *101 Great Questions.pdf* and *Steve Dalton's 2-Hour Job Search.epub* — were 0 bytes / empty and contained no extractable content, so nothing from them is reflected here.)

## What was kept vs. cut

**Cut:** motivational filler ("believe in yourself"), the philosophical/"meaning of work" material in *Parachute*, redundant Q&A lists (all six books independently cover "greatest weakness," "tell me about yourself," etc. — you don't need six versions), multi-day self-assessment worksheets, verbatim sample dialogues, and anything that was generic advice repeated across sources.

**Kept and grafted together:** the handful of *genuinely distinct, load-bearing frameworks* each book contributes, merged into single superstructures wherever two books were describing the same underlying mechanic in different words. For example:
- Bolles's "5 underlying employer questions," Kelley's "Three Cs" (Competence/Compatibility/Chemistry), and Kelley's REV filter all triangulate on the same 3-pillar structure — so they became **one** framework (file 02), not three.
- SOAR (Kelley), the implicit Problem→Action→Result structure (Fry), and Bolles's 6-question story skeleton all became **one** story template (file 05).
- ARTS objection-handling (Kador), the Sandwich Technique (Kelley), and "answer the underlying concern" (Fry/LaCivita) became **one** pivot structure (file 03).

## The files

| File | Purpose |
|---|---|
| `01-PITCH-60-SEC-FRAMEWORK.md` | Fill-in-the-blank formulas for your 60-second "tell me about yourself" pitch |
| `02-THREE-PILLARS.md` | How to pick the 3 core messages you drive home all interview, regardless of question |
| `03-UNIVERSAL-ANSWER-SUPERSTRUCTURES.md` | 4 reusable answer shapes that cover any question type |
| `04-QUESTION-BANK-CHEAT-SHEET.md` | 8 meta-categories of questions, each with 1 structure + 1 example |
| `05-STORY-BANK-TEMPLATE.md` | Template for building 5-6 reusable STAR-style stories |
| `06-CONTROL-BRIDGING-TACTICS.md` | Exact phrases for redirecting, buying time, and taking control |
| `07-LLM-MASTER-PROMPT.md` | Paste-ready prompt: feed this folder + your resume + a JD to any LLM |
| `08-ONE-PAGER.md` | Single-page cheat sheet — print this, glance at it in the elevator |

## How to use this system

1. **Once, ahead of any interview season:** work through `02` (pick your 3 pillars) and `05` (bank 5-6 stories). This is the reusable core — do it once, reuse everywhere.
2. **Per job application:** open `07-LLM-MASTER-PROMPT.md`, paste it into an LLM along with this folder's contents, your resume, and the job description. It will generate a tailored pitch, tailored pillars, and tailored answers.
3. **Night before / morning of:** skim `08-ONE-PAGER.md` and `06-CONTROL-BRIDGING-TACTICS.md`.
4. **Mid-interview, if stuck:** fall back on `03-UNIVERSAL-ANSWER-SUPERSTRUCTURES.md` — every question, however novel, is one of those 4 shapes.
