# 07 · LLM Prompts

**Setup:** start a new chat with any capable LLM. Attach or paste files 01–06 and 08 from this folder, then your **resume** and the **job description (JD)**. Add a short company dossier if you have one (website, news, notes). Then paste one of the prompts below.

| Prompt | When to use it |
|---|---|
| A · Master | Full preparation for a new job (use this first) |
| B · Quick prep | 15 minutes before a call |
| C · Live rescue | A question you didn't prepare for |
| D · Mock interview | Practice with feedback |
| E · Gap attack | You're underqualified on a requirement |
| F · Debrief | After each round |

## Choose your length (1, 3, 5 or 10 pages)

Prompt A takes a **LENGTH** setting. One page is about 450 words. The tiers are cumulative: each one includes everything in the tier below it.

| LENGTH | Words | Use it when | What you get |
|---|---|---|---|
| **1 page** | ~450 | Right before you walk in; phone screens | 3 pillars, 60-sec pitch as bullets, the 4 shapes and 8 types in one line each, your top 3 stories in 15-sec form, 6 power phrases, the "never" list |
| **3 pages** | ~1,350 | The night before | Adds: gap scan (top 3 gaps with scripts), the full spoken pitch, all 6 stories in 15-sec form, one short answer for each of the 8 types, 5 questions to ask, salary and closing lines |
| **5 pages** | ~2,250 | A final round or a job you really want | Adds: full story cards (S1–S6), two likely questions per type with spoken answers, an ARTS script for each gap, the full control plan, a thank-you note draft |
| **10 pages** | ~4,500 | Full preparation, or a senior or high-stakes role | Adds: the complete gap scan table, the fear map, pitch variants (20/60/90 sec), three likely questions per type with follow-up probes, a 90-sec version of each story, a 30/60/90-day plan, 8 questions to ask, a mock-interview question list, and a debrief template |

If you don't set a LENGTH, the LLM should default to **3 pages**.

---

## A · Master prompt
```
You are my interview coach. The attached playbook (files 01–08) is your ONLY
method. Do not import outside frameworks. Inputs: PLAYBOOK, RESUME, JD
(+ optional COMPANY NOTES).

LENGTH: <1 | 3 | 5 | 10> pages   (default 3; one page is about 450 words)

Length tiers are CUMULATIVE. Fit the whole answer to the LENGTH I chose,
and do not pad. Cut the lowest-priority material first.
- 1 page: 3 pillars; 60-sec pitch as bullets; 4 shapes and 8 types in one
  line each; top 3 stories in 15-sec form; 6 power phrases; the never list.
- 3 pages: add gap scan (top 3 gaps, each with a script); full spoken pitch;
  all 6 stories in 15-sec form; one short answer per type (Q1-Q8); 5
  questions to ask; salary and closing lines.
- 5 pages: add full story cards S1-S6; 2 likely questions per type with
  spoken answers; an ARTS script for every gap; full control plan; thank-
  you note draft.
- 10 pages: add the full gap scan table; the fear map; pitch variants
  (20/60/90 sec); 3 likely questions per type with follow-up probes; a
  90-sec version of each story; 30/60/90-day plan; 8 questions to ask;
  a mock-interview question list; a debrief template.
Start with a one-line contents list that shows the tier you are using.

Ground rules:
- Use only facts from my resume/notes. Never invent numbers, titles, or
  results. Where a number is missing, write [NEED: …] and ask me.
- Mirror the JD's language. Be concise. Spoken answers, not essays.
- Assume I may be underqualified; handle gaps head-on per files 03/06.

Produce the following, trimmed to the LENGTH tier above:

0. GAP SCAN — Table: each JD requirement → my best evidence (resume line)
   → Strong / Adjacent / Missing. List the 3 fears this employer will
   likely have about me (from the list in file 02).

1. THREE PILLARS (file 02) — PROVE / FIT / EDGE, one sentence each, REV-
   checked, each with its proof and the fear it disarms.

2. 60-SECOND PITCH (file 01) — 7 beats as bullet talking points, then the
   spoken version (150–250 words), plus a 20-second version.

3. STORY BANK (file 05) — Fill slots S1–S6 as story cards from my resume,
   each with a 15-second version, pillar tags, and JD skills it proves.
   Mark weak slots [NEED: …].

4. ANSWERS FOR ALL 8 TYPES (file 04) — For each type Q1–Q8: the 2 most
   likely questions for THIS role, the shape used, and a spoken answer
   (≤90 sec) built from my stories. For every "Missing" gap from step 0,
   add a gap script (PIVOT/ARTS + S4).

5. MY QUESTIONS (file 04 table) — 5 questions tailored to this company,
   ordered company → role → boss, including the criteria question and the
   objection question.

6. CONTROL PLAN (file 06) — The 5 tactics most important for THIS
   interview and the exact phrase I'll use for each, plus my salary line
   and closing script.

7. ONE-PAGER (file 08) — Filled in with my actual material.

Before step 1, ask me up to 5 short questions about missing facts, then
continue. If I say "skip", proceed using [NEED] placeholders.
```

## B · Quick prep (15 minutes before; same as the 1-page tier)
```
Using the playbook, resume and JD: give me only (1) my 3 pillars, one line
each; (2) a 20-second and a 60-second pitch; (3) the 3 most likely hard
questions with a 3-bullet answer each; (4) my top 3 questions to ask; and
(5) the opening question and the closing script. Keep the whole thing to
one screen.
```

## C · Live rescue (an unprepared question)
```
Question I got: "<paste>". Using the Loop in file 03: name the type (Q1–Q8),
the hidden fear, the shape, and the pillar. Then give me a spoken answer of
40 seconds or less using my stories, ending with one of the 4 landing
endings. Also give me a 10-second fallback version.
```

## D · Mock interview
```
Act as the hiring manager for this JD. Ask me one question at a time, mixing
all 8 types, with 2 follow-up probes on weak answers and at least one
objection about my biggest gap. After each of my answers, score it 1–5 on:
Shape used, Pillar landed, Specific proof (number), Length (≤2 min),
Ending (forward). Give me a one-line fix and a tightened version. After 8
questions, list the 3 things I most need to repeat or change.
```

## E · Gap attack
```
I'm short on this requirement: "<requirement>". Using files 03, 05 and 06,
give me: (1) adjacent evidence from my resume, (2) a fast-learner story
(S4), (3) the "name it first" script, (4) an ARTS response if they raise
it, and (5) a 30/60/90-day plan to close it, in 3 bullets I can say out
loud.
```

## F · Debrief (after each round)
```
Notes from this round: <who, the questions asked, the stories I used, where
I struggled, their concerns>. Update: (1) which stories I've now used with
whom, so I don't repeat them; (2) objections to pre-empt next round, with
scripts; (3) a thank-you note (same day, 3 short paragraphs, tied to
specifics they said, correcting any weak impression); (4) what to change
in my pillars or pitch for the next round.
```

---

**Tips**
- To move up or down a tier, re-run Prompt A with a different LENGTH. The tiers are cumulative, so the 3-page version contains the whole 1-page version.
- Re-run Prompt A for each job. Your stories carry over, but your pillars and pitch should be re-tuned to each JD.
- Rehearse the output out loud. Edit it into your own words; memorized scripts sound robotic.
