---
name: role-scorecard
description: Use when the user wants to define what a role is for and how it will be judged — "what should this person be responsible for", "how do I measure this role", "I don't know if my ops manager is doing a good job", "how do I tell if they're doing well". Produces outcomes with numbers and review points, not a list of duties. For the advert that goes out to candidates use job-description; for a new hire's first 90 days use onboarding-plan.
---

# Role scorecard

What a role is **for**, what good looks like as a number, and when it gets reviewed.

Most job definitions list activities and never say what good is. Then nobody can tell
whether the person is doing well, including the person.

## Read the brief

Look for `business-brief.md` in the working directory or the project's files.

- **Found:** read it for capacity, constraints and what the business actually sells — the
  outcomes for any role should trace back to one of those.
- **Not found:** carry on. Ask what the business does and what this role exists to change.
  Mention `business-brief` once at the end.

## What it needs

- **Why the role exists.** Not the title. What would be different in six months if it were
  done well, and what is going wrong now without it.
- **What they can actually measure.** Ask what numbers the business already has. An outcome
  measured by a number nobody collects is not measurable, and pretending otherwise is how
  scorecards get abandoned.
- **Who they report to**, and what they can decide alone.

## Process

### 1. Write the purpose in one sentence

"This role exists so that ___." If it takes more than one sentence, the role is two roles
and it is worth saying so — badly split roles are one of the most expensive small-business
hiring mistakes.

### 2. Write three to five outcomes, not duties

The distinction the whole skill turns on:

- **Duty:** "manages the inbox"
- **Outcome:** "every enquiry gets a real reply within one working day"

An outcome is a state of the world that someone else could verify. Three to five. More than
five and none of them are priorities.

### 3. Put a number and a date on each

For each outcome: the measure, where the number comes from, what good looks like, and by
when. If no number exists, say so and propose the nearest thing that is actually
collectable — including "counted by hand each Friday", which is a legitimate answer for a
small business.

**Never invent a benchmark.** "Industry standard is 20%" is exactly the kind of confident
fabrication that gets copied into a review conversation.

### 4. Say what they decide alone

Three or four decisions this role owns without asking, and the two or three that always
come back. Ambiguity here is what makes a good hire look slow.

### 5. Say what a bad quarter looks like

Concrete and early: the signals that would show, in the first eight weeks, that this is not
working. This is the part that protects both sides — it makes an honest conversation
possible before it becomes a dismissal.

### 6. Set the review rhythm

When it is reviewed, by whom, against what. A scorecard reviewed once a year is a document,
not a management tool.

## Output

Write to **`scorecard-<role>.md`**.

```markdown
# Scorecard — <role>

**Exists so that:** <one sentence>
**Reports to:** <role> · **Reviewed:** <rhythm>

## Outcomes

### 1. <Outcome, as a state of the world>
- **Measure:** <the number>
- **Source:** <where the number comes from — including "counted by hand">
- **Good looks like:** <the target> by <date>

## Decides alone
- <decision>

## Always escalates
- <decision>

## A bad quarter looks like
- <early, visible signal>

## Review
**<Rhythm>**, <who>, against the outcomes above.

## Gaps
- <any measure with no number available, and what would be needed>
```

## Quality bar

**Good:** the person in the role and the person who hired them would independently give the
same answer to "is this going well?"

**Failed:** outcomes that are duties with a verb changed. If nobody could verify it from
outside the person's own account of their week, it is not an outcome.

Never invent a target, a benchmark or a market rate. If the user does not know what good
looks like yet, write `[gap]` and say that the first quarter's job is to find out — that is
an honest and useful answer. Close by saying how many measures have no data source yet.
