---
name: email-sequence
description: Use when the user wants a series of emails that go out in order — "a welcome sequence for new subscribers", "follow-up emails after someone enquires", "a nurture sequence", "emails to win back old customers". Produces an ordered sequence where each email has a job and a reason to exist, with real personalisation marked rather than faked with a first name. For one email reply to a person, use enquiry-reply.
---

# Email sequence

A sequence where each email has a job, a reason to exist, and a reason to arrive when it
does.

Most sequences are one message stretched over five sends. The reader notices by email two
and stops opening.

## Read the brief

Look for `business-brief.md` in the working directory or the project's files.

- **Found:** read it. Voice, offer, price, exclusions and the customer's trigger all shape
  the sequence — especially what the customer is worried about before they buy.
- **Not found:** carry on. Ask what the offer is, who the list is, and what should happen at
  the end. Mention `business-brief` once at the end.

## What it needs

- **Who is receiving it, and how they got there.** A new subscriber, an unconverted
  enquiry, and a customer who lapsed two years ago need completely different sequences.
- **What should happen at the end.** One outcome.
- **What they already know.** Someone who has had a quote knows the price; repeating it
  wastes an email.

## Process

### 1. Give each email one job

Write the job list before writing any email. If two emails have the same job, cut one. A
four-email sequence where every email is needed beats a seven-email one with padding.

Typical jobs, depending on the sequence: set expectations, answer the biggest doubt, show
it working, make the offer, close it off.

### 2. Decide the spacing, and say why

Not "day 1, 3, 5, 7" because it looks tidy. Space against what the reader is doing —
tighter when they have just enquired and are actively comparing, wider for a nurture list
with no live intent.

Say the reasoning in one line. If the user wants it faster, tell them what that costs.

### 3. Write the subject lines as promises the email keeps

The subject is the only part most people see. Specific, short, no fake urgency, no "Re:" on
an email that is not a reply, no first name in the subject as a trick.

Give one alternate per email so they have a choice.

### 4. Mark real personalisation, and refuse the fake kind

The rule this skill turns on. `{{first_name}}` is not personalisation, it is a mail merge,
and everyone knows what it is.

Mark the places where **real** personalisation would change the email: the thing they
enquired about, the size of their business, the problem they described, how long they have
been a customer. For each, say what data is needed and where it comes from.

Where the data does not exist, say so and write the email to work without it. Never write a
sentence that reads as broken when the field is empty — that is the single most common
failure in small-business email.

### 5. Write each email short, with one ask

Most sequence emails should be under 150 words. One ask per email, the same ask, in the
same words. Two links compete.

### 6. Write the exit

What happens to someone who does not act by the end: moved to a normal list, left alone, or
one final honest "shall I close this off?" — which is often the best-performing email in
the sequence.

Include the unsubscribe expectation, and note that consent and marketing rules apply and
vary by jurisdiction. Never state a legal requirement as fact; say to check.

## Output

Write to **`sequence-<purpose>.md`**.

```markdown
# Email sequence — <purpose>

**Who gets this:** <and how they arrived>
**Ends with:** <the one outcome>
**Length:** <n> emails over <n> days

## The jobs
| # | Send | Job | Why then |
|---|---|---|---|

---

## Email 1 — <job>
**Subject:** <line>
**Alternate:** <line>

<body — under 150 words>

**Ask:** <the one action>

**Real personalisation:**
- `<what>` — <the data needed, and where it comes from>
- <Works without it: yes / rewrite this line if unavailable>

---

## Exit
<What happens to someone who does not act.>

## Data needed to run this
- <field> — <where it comes from, or [not available]>
```

## Quality bar

**Good:** every email could be deleted only by losing something, and the sequence reads as
one person writing rather than a funnel.

**Failed:** emails that differ only in how they restate the offer. If email three would
still make sense as email one, the sequence has no shape.

Never invent scarcity, a deadline, a discount, a customer result or a testimonial. Never
write "I noticed you..." about something you did not notice — false observed-behaviour
openers are the fastest way to lose a list. Close by listing what data is needed and how
many gaps there are.
