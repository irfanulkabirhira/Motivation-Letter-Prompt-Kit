# Motivation Letter Prompt Kit

A step-by-step prompt workflow for getting a large language model (ChatGPT, Gemini, Claude, etc.)
to write tailored motivation letters for scholarships, traineeships and jobs.

Works best when you apply to many programs one after another.

---

## How it works (overview)

1. Give the model your materials (CV, past letters, a guide to good structure).
2. Give it your rules (tone, honesty, format, contact details).
3. Paste one posting at a time. It returns one letter per posting.
4. Refine with short follow-up prompts.
5. Run the checklist before you submit.

---

## Step 0: Prepare your materials

Have these ready to upload or paste:

- [ ] Your CV
- [ ] 1-3 motivation letters you wrote or applied with before
- [ ] A guide to a strong structure (see Step 2)
- [ ] A facts sheet about you (see Step 3)

---

## Step 1: Start the session (role and rules)

Paste this first:

```text
You will help me write motivation letters for scholarships, traineeships and jobs.
I will apply to many programs one by one. For each, I will paste the posting
and you will write a letter tailored to it.

Rules for every letter:
1. Output plain text I can copy and paste. Do not create a document file.
2. Use only facts from my CV, my past letters and my facts sheet. Never invent
   experience, skills, tools, grades, publications or certificates.
3. If the posting asks for something I do not have, say so honestly in the letter
   in one short sentence, then show the closest real experience I do have.
4. Write in a natural, human voice: specific details, varied sentence length,
   no generic filler such as "passionate", "hardworking" or "I am the perfect
   candidate". Avoid a template feel.
5. Follow the structure in the guide I will give you.
6. Respect any word limit in the posting. Tell me the approximate word count.
7. Use my current contact details and result format (given in my facts sheet).
8. After each letter, add a short "Before you submit" list: gaps to fill with
   real experience, claims I must verify, and anything uncertain.

Reply "Ready" and wait for my materials.
```

---

## Step 2: Give it the structure guide

Paste this (edit if your guide differs):

```text
Every letter should follow one connected thread:
Past experience -> current interest -> this specific program -> future goal.

Cover these parts, in this order, adapted to the posting:
1. Clear goal: why I am applying, stated directly (no childhood stories).
2. Prior preparation: degree and training, each tied to "why this makes me ready".
3. Depth of experience: for key projects, say the problem, my role, the methods,
   the result and what I learned. Show, do not list.
4. Program fit: specific reasons this unit/program fits me, matched to the
   posting's own tasks. Not generic prestige.
5. Future plan: realistic, and a direct continuation of the above.
6. One connected thread running through every paragraph. If a paragraph does not
   connect to it, cut it.

Mistakes to avoid: turning my CV into sentences, sending the same letter
everywhere, naming the wrong program or unit, unsupported adjectives,
ignoring the posting's word limit or format rules.
```

---

## Step 3: Give it your facts sheet

Fill in the brackets. Keep this file private.

```text
FACTS SHEET (use only these facts)

Name: [FULL NAME]
Contact line: [CITY, COUNTRY] | [PHONE] | [EMAIL]
Degree: [DEGREE, UNIVERSITY, MONTH YEAR]
Result: [HOW YOU WANT IT SHOWN, e.g. 91.5%]
Language of study: [e.g. English]

Research / projects:
- [Project 1: what it was, your role, methods, outcome]
- [Project 2: ...]
- [Dataset or publication details, stated exactly: accepted / submitted / in preparation]

Work and volunteering:
- [Role, organisation, what you did]
- [Role, organisation, what you did]

Training and courses:
- [Course, provider]
- [Course, provider]

Tools and skills I can honestly claim:
- [e.g. Python, SQL, SPSS, Power BI, Matplotlib]

Languages:
- [Language: level]

Things I must NOT claim (not true or not verified):
- [e.g. "no SAP experience", "no ITIL certificate"]
```

---

## Step 4: One posting at a time

Use this template for each application:

```text
Write a motivation letter for this posting.

Extra instructions:
- Length: [about 450-500 words / maximum 600 words / about two pages]
- Style: [balanced / more confident and assertive]
- Address it to: [unit, directorate, organisation]
- Reference line: [reference number, place, start date]
- Date: [date]

POSTING:
[paste the full text: who we are, tasks, requirements]
```

Tip: always paste the tasks and requirements, not just the header. The model
matches your experience against those.

---

## Step 5: Useful follow-up prompts

```text
Make it longer (about two pages) and more confident, but do not invent anything.
```
```text
Shorten it to under [N] words. Keep the strongest examples.
```
```text
Rewrite so it sounds more like me. Here is a paragraph I wrote myself: [paste].
```
```text
Which claims in this letter are weakest or riskiest if the committee checks them?
```
```text
Remove all generic phrases and replace them with specific evidence from my facts sheet.
```
```text
Change my result to [new format] and my email to [new email] everywhere.
```
```text
Write a different version of the second paragraph focused on [skill].
```

---

## Step 6: Checklist before you submit

- [ ] Reference number and unit name match the vacancy page exactly
- [ ] No duplicate application for the same reference
- [ ] Contact details and result are current
- [ ] Every claim matches my CV (dates, roles, publications, tools)
- [ ] "Accepted" vs "submitted" vs "in preparation" stated correctly
- [ ] Gaps filled with one real example where I have one
- [ ] Word limit respected
- [ ] A few phrases changed into my own words, then read aloud once
- [ ] File named clearly, e.g. `Firstname_Lastname_Motivation_Letter.pdf`
- [ ] Extra upload rules followed (e.g. letter + diploma + transcript in one PDF)
- [ ] Declaration questions (prior contracts, relatives, disability) answered truthfully by me

---

## Notes

- **AI detectors are unreliable.** They can flag human writing and miss AI writing.
  No prompt guarantees a "0%" result. The best protection is specific, true detail
  and your own final edit.
- **Never let the model invent experience.** A false claim can end an application
  or a placement after selection.
- **Keep your facts sheet updated** whenever your email, results or publications change.
- **Do not put personal data in a public repo.** Use placeholders or keep it private.
