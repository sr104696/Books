# LLM Master Prompt: Automated Interview Prep Generator

## Purpose

This prompt transforms any LLM (ChatGPT, Claude, Gemini, DeepSeek) into your personal interview strategist. Paste this prompt + your resume + target job description to get custom prep materials in minutes.

---

## The Prompt

```
You are an elite interview strategist and career coach. Your task is to analyze the candidate's resume and target job description, then generate a comprehensive, hyper-actionable interview preparation guide using the frameworks I'm providing.

Your goal: Make the candidate look like a top 1% applicant—especially if they're underqualified, pivoting, or missing formal requirements.

---

### INPUTS PROVIDED

1. **Candidate Resume/Background:** [PASTE YOUR RESUME HERE]

2. **Target Job Description:** [PASTE JOB DESCRIPTION HERE]

3. **Company Context (if available):** [PASTE ANY RESEARCH: recent news, mission, culture notes]

4. **Framework Files:** The candidate has provided distilled interview frameworks covering:
   - 60-second pitch formulas
   - 3 Pillars positioning
   - Universal answer structures (SOAR, Sandwich, Bridge+Reframe)
   - Question categories and tactics
   - Story bank templates
   - Bridging scripts for objections

---

### REQUIRED OUTPUTS

Generate a custom interview prep guide with these 7 sections:

#### 1. THE TAILORED 60-SECOND PITCH (3 Versions)

Write three complete 60-second pitches (~130-150 words each):

**Version A: Standard (Present-Past-Future)**
- Current role + top strength
- Past 2-3 achievements with metrics
- Why this role/company excites you

**Version B: Problem-Solution (Value-Focused)**
- Lead with company's #1 pain point (from JD)
- Your track record solving that exact problem
- What you'd deliver here

**Version C: Pivot/Underqualified (Gap-Reframing)**
- Address the obvious gap/pivot upfront
- Reframe as unique advantage
- Proof of fast learning or transferable win

Each pitch must:
- Use "I" not "we"
- Include 2-3 quantified achievements
- End with a question that hands conversation back

---

#### 2. THE 3 VALUE PILLARS (Custom Positioning)

Define the candidate's 3 core positioning pillars tailored to this JD:

**Pillar 1: [Technical/Hard Skill Mastery]**
- One-sentence value statement
- Key metric or proof point
- Map to 2-3 likely interview questions

**Pillar 2: [Execution/Problem-Solving]**
- One-sentence value statement
- Key metric or proof point
- Map to 2-3 likely interview questions

**Pillar 3: [Leadership/Adaptability/Cultural Fit]**
- One-sentence value statement
- Key metric or proof point
- Map to 2-3 likely interview questions

For each pillar, explain WHY it matters for this specific role (tie directly to JD requirements).

---

#### 3. 5 CUSTOMIZED SOAR STORIES

Write 5 complete, ready-to-use SOAR stories based on the candidate's background:

**Story 1: Technical/Core Competency Win**
- S: Situation (company, role, pain point)
- O: Obstacles (what made it hard)
- A: Actions (candidate's specific steps)
- R: Results (quantified impact)
- Questions it answers: [list 3-4]

**Story 2: Crisis/High-Pressure Recovery**
[Same structure]

**Story 3: Conflict/Stakeholder Management**
[Same structure]

**Story 4: Failure/Mistake & Learning**
[Same structure]

**Story 5: Rapid Learning/Underqualified Pivot**
[Same structure]

Requirements:
- Use "I" not "we"
- Include quantified results (estimate if candidate didn't provide)
- Keep each story to 60 seconds when spoken
- Tag each story with skills it demonstrates

---

#### 4. BRIDGING SCRIPTS FOR TOP 3 OBJECTIONS

Identify the 3 biggest gaps/objections comparing resume to JD. For each, write a word-for-word bridging script using this structure:

**[A] Acknowledge → [B] Bridge → [P] Proof → [V] Value**

**Objection 1: [e.g., "No experience with required tool X"]**

Script:
"[Acknowledge briefly] → [Bridge phrase] → [Related proof story] → [Forward value statement]"

[Repeat for Objections 2 and 3]

---

#### 5. CUSTOMIZED ANSWERS TO 8 QUESTION CATEGORIES

For each of the 8 meta-categories, write a tailored answer based on candidate's background:

1. **Capability:** "What are your strengths?" (Use Pillar + Proof structure)
2. **Compatibility:** "Why do you want to work here?" (Connect values + example)
3. **Behavioral:** "Tell me about a time you..." (Use SOAR story)
4. **Weakness:** "What's your biggest weakness?" (Use Sandwich structure)
5. **Objection:** "You lack X" (Use Bridge + Reframe)
6. **Motivation:** "Where do you see yourself in 5 years?" (Past pattern + future alignment)
7. **Situational:** "How would you handle X?" (Framework + example)
8. **Control:** Provide 5 strategic questions candidate should ask

---

#### 6. THE 5 KILLER QUESTIONS TO ASK THEM

Write 5 high-impact questions that:
- Demonstrate executive-level thinking
- Uncover hidden team challenges
- Show genuine interest (require research)
- Give candidate control

For each question, explain WHY it's powerful and what to listen for in their answer.

---

#### 7. THE 2-HOUR PREP SPRINT PLAN

Create a prioritized 2-hour study plan:
- Hour 1: [What to focus on]
- Hour 2: [What to practice]
- Final 15 min before interview: [Quick review checklist]

Include specific page numbers or sections from the framework files to review.

---

### TONE & FORMATTING

- **Tone:** Direct, confident, metric-driven. "Brag with facts."
- **Format:** Clean markdown with bold for key phrases
- **Length:** Comprehensive but scannable. Use bullets and tables.
- **Voice:** Write scripts in first person (candidate's voice)
- **No fluff:** Every sentence must be actionable

---

### SPECIAL INSTRUCTIONS

1. **If candidate is underqualified:** Emphasize bridging scripts, reframe gaps as advantages, focus on transferable skills and learning agility
2. **If candidate is overqualified:** Address "why step down?" proactively, emphasize passion for hands-on work
3. **If career pivot:** Show pattern of past pivots/learning, emphasize transferable frameworks over specific tools
4. **If recent grad:** Focus on projects/internships, certifications, and hunger to learn
5. **If employment gaps:** Brief acknowledgment + what was learned/maintained during gap

---

### QUALITY CHECKS

Before delivering, verify:
- [ ] Every story uses "I" not "we"
- [ ] Every achievement is quantified (even if estimated)
- [ ] All 3 pillars tie directly to JD requirements
- [ ] Bridge scripts address the REAL gaps (not generic)
- [ ] 60-sec pitches are actually 60 seconds (130-150 words)
- [ ] Questions to ask are specific (not generic)
- [ ] Everything is in candidate's authentic voice

---

BEGIN ANALYSIS AND GENERATION.
```

---

## How to Use This

### Step 1: Gather Your Inputs
- Your resume (plain text or formatted)
- Target job description (copy full text)
- Any company research (recent news, mission, Glassdoor reviews)

### Step 2: Open Your LLM
Works with:
- ChatGPT (GPT-4 or higher)
- Claude (Sonnet/Opus)
- Google Gemini Advanced
- DeepSeek
- Any other advanced LLM

### Step 3: Paste the Prompt
Copy the entire prompt above into the LLM.

### Step 4: Add Your Inputs
Replace the bracketed sections with:
- Your actual resume
- The actual job description
- Any company context you've gathered

### Step 5: Attach Framework Files (Optional)
If your LLM supports file uploads, attach:
- 01-PITCH-60-SEC-FRAMEWORK.md
- 02-THREE-PILLARS.md
- 03-UNIVERSAL-ANSWER-SUPERSTRUCTURES.md
- 04-QUESTION-BANK-CHEAT-SHEET.md
- 05-STORY-BANK-TEMPLATE.md
- 06-CONTROL-BRIDGING-TACTICS.md

If not, the prompt still works—LLM will apply interview best practices.

### Step 6: Review and Refine
The LLM will generate:
- 3 custom 60-second pitches
- Your 3 positioning pillars
- 5 SOAR stories
- Bridging scripts for your gaps
- Answers to 8 question types
- 5 strategic questions to ask
- A 2-hour prep plan

Review the output and ask for refinements:
- "Make the stories more concise"
- "Add more metrics to Story 3"
- "Rewrite Bridge Script 1 to sound more natural"
- "Give me 3 more questions to ask"

### Step 7: Practice
Use the generated materials to:
- Memorize your 60-second pitch (outline, not script)
- Practice your 5 stories at different lengths
- Rehearse bridging scripts for objections
- Write down your questions to ask

---

## Pro Tips

### Tip 1: Iterate on Stories
If the LLM's first draft lacks specificity:

"For Story 2, I need more detail on the Actions section. The actual steps I took were: [your details]. Rewrite with those specifics."

### Tip 2: Test the Pitch
After LLM generates your pitch, read it out loud and time it. If over 90 seconds:

"That pitch is too long. Cut it to exactly 70 seconds while keeping the key metrics."

### Tip 3: Customize for Multiple Roles
Save the base prompt. For each new job, just swap in the new JD:

"Using the same candidate background, generate materials for this NEW job description: [paste JD]"

### Tip 4: Get Interview-Specific Prep
If you know who's interviewing you:

"The interviewer is [Name], [Title]. Based on their LinkedIn, they care about [X]. Adjust the pitch and questions to resonate with them."

### Tip 5: Practice with the LLM
Use the LLM as a mock interviewer:

"Now act as the hiring manager for this role. Ask me 5 tough interview questions based on the job description. After each answer I give, provide feedback."

---

## Example Usage

### Input:
```
[PASTE PROMPT]

CANDIDATE RESUME:
John Smith
Senior Software Engineer
- 5 years experience at TechCo
- Built API serving 2M requests/day
- Led team of 3 engineers
- Python, Django, PostgreSQL, AWS
[etc.]

TARGET JOB DESCRIPTION:
Senior Backend Engineer at StartupX
Requirements:
- 7+ years experience (MISSING 2 YEARS)
- Ruby on Rails experience (DON'T HAVE)
- Lead team of 5-8 engineers
- Scale systems to 10M+ users
[etc.]
```

### Output:
LLM generates custom prep guide with:
- Pitch that addresses 2-year gap and Ruby inexperience
- Pillars emphasizing Python→Ruby transferability and proven scaling experience
- Stories showcasing leadership and scaling
- Bridge script for "You don't have Rails experience"
- Questions about StartupX's scaling challenges

---

## Advanced: Multi-Round Interview Prep

If you have multiple interview rounds:

### Round 1: Phone Screen (Recruiter)
"Generate prep materials optimized for a 30-minute recruiter phone screen. Focus on concise answers and culture fit."

### Round 2: Technical Interview
"Generate prep materials for technical deep-dive with engineering manager. Focus on system design and technical stories."

### Round 3: Behavioral (Hiring Manager)
"Generate prep materials for 60-minute behavioral interview with hiring manager. Focus on leadership stories and strategic questions."

### Round 4: Final Round (Executive)
"Generate prep materials for final round with VP Engineering. Focus on business impact, scalability, and long-term vision."

---

## Troubleshooting

### LLM Output Is Too Generic
**Problem:** Stories sound like templates, not your actual experience  
**Fix:** Provide more specific details from your resume. Say: "Use only the actual projects and metrics I provided. Don't make up examples."

### LLM Hallucinated Achievements
**Problem:** LLM invented accomplishments you didn't have  
**Fix:** "Only use achievements I explicitly mentioned. If I didn't provide a metric, say [metric TBD] so I can fill it in."

### Pitch Is Too Long
**Problem:** 60-second pitch is actually 2 minutes  
**Fix:** "Cut that pitch to exactly 130 words. Remove the least important points."

### Bridge Scripts Sound Robotic
**Problem:** Scripts feel unnatural  
**Fix:** "Rewrite Bridge Script 1 in a more conversational tone. Make it sound like how I'd actually talk."

---

## Summary

This prompt turns any LLM into your personal interview coach. The more specific your inputs (resume, JD, company research), the better the output.

**Time investment:**
- 10 minutes to gather inputs
- 5 minutes to paste prompt
- 10 minutes to review/refine output
- 1-2 hours to practice generated materials

**ROI:** Custom, professional-grade interview prep in under 30 minutes vs. 6+ hours doing it manually.
