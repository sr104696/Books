# LLM Master Prompt

Copy everything in the box below into a fresh LLM conversation, then attach/paste: (1) all files from this folder, (2) your resume, (3) the job description you're targeting. Replace the bracketed placeholders.

---

```
You are helping me prepare for a specific job interview. I'm giving you three inputs:

1. A folder of distilled interview-guidance frameworks (files 00 through 08,
   already attached/pasted below or in this conversation).
2. My resume (attached/pasted below).
3. The job description I'm applying to (attached/pasted below).

Using ONLY the frameworks in the guidance folder (don't invent new frameworks
or fall back on generic interview advice not present in these files), do the
following:

STEP 1 — THREE PILLARS
Using 02-THREE-PILLARS.md, read my resume and the job description and propose
3 pillar messages (Competence / Fit / Differentiator), each run through the
REV filter (Relevant to THIS job posting, Exceptional/not generic, Verifiable
against something specific in my resume). For each, cite the specific resume
line or bullet that proves it. Flag if my resume doesn't have strong enough
material for one of the pillars, and tell me what info you'd need from me to
fill the gap.

STEP 2 — 60-SECOND PITCH
Using 01-PITCH-60-SEC-FRAMEWORK.md and the 3 pillars from Step 1, draft a
250-350 word pitch for "tell me about yourself," tailored to this job
description specifically (the company-research hook should reference real,
specific things from the job description — mission, product, team structure,
stated priorities — not generic praise). Give it to me as a talking-points
outline (per Kelley's rule in file 01), not a verbatim script to memorize.

STEP 3 — STORY BANK
Using 05-STORY-BANK-TEMPLATE.md, ask me for raw material if you don't already
have it from my resume (use the "Take 12" mining questions), then draft 5-6
stories in the Situation/Obstacles/Action/Result template, each tagged to
one of my Three Pillars and to the specific skills this job description
emphasizes. Include a 15-second compressed version of each.

STEP 4 — ANSWERS TO ALL 8 QUESTION CATEGORIES
Using 04-QUESTION-BANK-CHEAT-SHEET.md and 03-UNIVERSAL-ANSWER-SUPERSTRUCTURES.md,
generate one tailored example answer for each of the 8 meta-categories
(Opener, Proof/Behavioral, Negative/Weakness, Motivation/Fit,
Objection/Underqualified, Illegal/Personal, Salary/Logistics, Curveball/
Stress), built from my actual resume material and pillars — not generic
placeholder answers. For any category where my resume is visibly thin
against this specific job description (e.g., I'm underqualified on a stated
requirement), use the Objection/Underqualified structure from file 03
explicitly and be honest about the gap rather than papering over it.

STEP 5 — CONTROL PLAYBOOK
Using 06-CONTROL-BRIDGING-TACTICS.md, give me the 3-5 tactics from that file
most likely to matter for THIS specific interview (e.g., if the job
description suggests I may be underqualified on paper, prioritize the
Preemptive Question and the underqualified-gap script; if it's a senior
role, prioritize the closing control sequence and salary ladder).

STEP 6 — ONE-PAGE SUMMARY
Compress everything above into the format of 08-ONE-PAGER.md, filled in
with my actual material, so I have a single page to glance at right before
the interview.

Ask me clarifying questions about anything in my resume or the job
description that's ambiguous before you draft final answers — don't guess
at facts about my background.
```

---

## Notes on using this prompt

- If the LLM doesn't have file-attachment support, paste the contents of files `00` through `06` and `08` directly into the conversation before the prompt above.
- Re-run this per job application — the pillars and pitch are meant to be re-tuned per job description (see file 02), even though your underlying story bank stays mostly stable.
- If you're prepping for a second-round interview at the same company, tell the LLM which stories/answers you already used in round one so it can avoid repeats (Kelley's warning: interviewers compare notes across rounds).
