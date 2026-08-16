---
name: job-description
description: Use when the user is hiring and needs the role written up and advertised — "write a job ad", "I need to advertise for a part-time bookkeeper", "put together a job description", "what should the listing say". Produces a role brief and the advert that comes from it, so the advert and the actual job agree. For defining what the role is measured on first, use role-scorecard; for their first 90 days use onboarding-plan.
---

# Job description

A role brief, and the advert written from it — so what is advertised and what the job
actually is do not diverge.

Most bad hires start with an advert written to attract people rather than to describe work.
The person arrives, the job is different, and both sides feel misled.

## Read the brief

Look for `business-brief.md` in the working directory or the project's files.

- **Found:** read it. The business description, voice and constraints shape the advert, and
  a candidate can tell when an advert was written by someone who knows the business.
- **Not found:** carry on. Ask what the business does and what the role is for. Mention
  `business-brief` once at the end.

Also look for **`scorecard-<role>.md`**. If one exists, write from it — the outcomes are
already defined and the advert should agree with them. If not, ask whether they want to
define the outcomes first with `role-scorecard`, but do not insist. Someone who needs an
advert today should get an advert today.

## What it needs

- **What the role is for**, in one sentence.
- **The pay**, or a range. See below — this is the section people try to skip.
- **Hours, location and arrangement.** Part-time, full-time, on-site, hybrid, shifts.
- **Who they report to.**

## Say the pay

Ask for it directly, and if they resist, say once why it matters: adverts without pay get
fewer and worse applicants, waste time on candidates who were never in range, and in some
jurisdictions are unlawful. Then accept their decision — it is their advert.

If they will not say, write `[pay not stated]` rather than a euphemism. Never write
"competitive salary". It tells a candidate nothing and signals that the number is bad.

## Process

### 1. Write the role brief first

The internal document. What the role exists to change, the three to five outcomes it owns,
what it decides alone, and what the first six months should produce. If a scorecard exists,
this is largely done.

This is what stops the advert drifting into a wish list.

### 2. Write what the person will actually do

In a week. Concretely. "Reconcile the bank weekly, chase overdue invoices, produce a
monthly summary" beats "support the finance function".

### 3. Write what is genuinely required

The hard filter — the two or three things without which someone cannot do this job.

Then, separately, what would help but is not required. Keep this list short. Long
requirement lists are the best-documented way to stop good candidates applying, and small
businesses can least afford it.

**Strip anything that is not a real requirement.** A degree for a job that does not need
one, "five years' experience" for a job someone could learn in three months, and
"must be a self-starter" all belong in this cut.

### 4. Say what is hard about the job

The part almost nobody writes, and the highest-value part of the advert. Say what is
genuinely difficult, unglamorous or unusual — the early start, the messy handover, the fact
that they are the only person doing this.

It costs a few applicants and gains the right ones. It also means the person who takes it
cannot say they were not told.

### 5. Write the advert in the business's voice

Not in HR language. A small business's advantage is sounding like a person. Use the brief's
voice excerpts.

### 6. Say how to apply, and what happens next

The steps, and roughly when they will hear. Include a real closing date only if there is
one.

## Output

Write to **`role-<title>.md`**, containing both parts.

```markdown
# <Role title>

## Role brief — internal

**Exists so that:** <one sentence>
**Reports to:** <role> · **Hours:** <detail> · **Location:** <detail>
**Pay:** <the number or range, or [pay not stated]>

**Owns these outcomes:**
1. <outcome>

**Decides alone:** <list>
**First six months should produce:** <what>

---

## The advert

### <Job title> — <location>, <hours>
**<Pay>**

<Two or three sentences on the business, in its own voice.>

**What you would do**
- <concrete weekly work>

**What we need**
- <the two or three real requirements>

**Helpful, not required**
- <short list>

**What is hard about this job**
<Honest. The early start, the messy system, the fact you are on your own with it.>

**How to apply**
<Steps, and when they will hear back.>
```

## Quality bar

**Good:** someone reading the advert would recognise the job on day one, and the role brief
and the advert do not contradict each other.

**Failed:** an advert that would fit any business hiring any version of this role. Or a
requirements list longer than the description of the work.

Never invent a salary, a benefit, a team size, a growth claim or a culture statement the
user did not give you. Never write that a business is "fast-paced", "like a family", or
"passionate about excellence" unless they said it and meant it. Close by listing gaps —
particularly pay, if it is unstated — and say how many there are.
