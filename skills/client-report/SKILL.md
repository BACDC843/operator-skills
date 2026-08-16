---
name: client-report
description: Use when the user needs to tell a client what was done and what it produced — "write the monthly report for this client", "they want an update", "what do I send the client this month", "put together a summary of what we did". Produces a client-facing report built around outcomes rather than activity, which says plainly when a period was quiet. It drafts; the user sends.
---

# Client report

A report for a client on what was done and what it produced.

Activity reports are what agencies send when there are no results. Clients read them,
notice, and leave a quarter later. This one leads with outcomes and says so honestly when
there were none.

## Read the brief

Look for `business-brief.md` in the working directory or the project's files.

- **Found:** read it for voice and constraints. Anything the business must never claim
  applies double here — this is a document a client keeps.
- **Not found:** carry on. Ask what was done and for whom. Mention `business-brief` once at
  the end.

## What it needs

- **The period**, and what was actually done in it.
- **The numbers**, if any exist — before and after. Ask what the client cares about, which
  is rarely everything that was measured.
- **What was agreed** at the start of the period, if anything. A report is much stronger
  read against a commitment.

Never carry figures over from an earlier conversation as current. Ask for the numbers.

## Process

### 1. Lead with what changed, not what was done

The first section answers one question: what is different for this client now. If leads
went from 11 to 19, that is the opening line. Not "we published four blog posts".

Where nothing measurable changed, say that in the first section too. Which brings us to:

### 2. Say plainly when the period was quiet

The rule this skill exists for. If a month produced little, write that it produced little,
say why if the reason is known, and say what is being done about it.

Do not inflate a quiet month with activity counts. Clients can tell, and a report that
manufactures momentum destroys more trust than a quiet month ever did. A supplier who says
"this month was slow, here is why and here is the plan" is a supplier who gets kept.

### 3. Then say what was done

After the outcomes, not before. Grouped by what it was for, not listed chronologically.
Keep it short — the client is checking that the work matches the fee, not reading a diary.

### 4. Report the numbers honestly

- Show before and after, and the period compared.
- Never present a percentage without the underlying counts. "Up 300%" from one to four is
  misleading, and eventually somebody works it out.
- Where a number moved for a reason outside the work, say so. Claiming credit for a
  seasonal peak is a debt that comes due in the trough.
- Where something went backwards, report it, with what is being done.

### 5. Say what is next, and what you need from them

Next period's focus, in two or three items. Then anything you need the client to supply or
decide, with a date — this is the section that saves the next month.

### 6. Keep it short

One page for a normal month. A long client report is usually padding.

## Output

Write to **`client-report-<client>-<period>.md`**.

```markdown
# <Client> — <period>

## What changed
<The outcomes. Numbers where they exist. If little changed, say so here, plainly.>

## The numbers
| | Before | After | Change |
|---|---|---|---|
| <metric> | <count> | <count> | <count and %> |

<Anything that moved for reasons outside the work, noted.>

## What we did
**<What it was for>**
- <the work>

## What did not go to plan
<Only if something did not. Say what, and what is being done.>

## Next period
- <focus>

## What we need from you
- <item> — by <date>
```

## Quality bar

**Good:** the client finishes it knowing whether they are getting value, and would not be
surprised by anything in it.

**Failed:** a list of tasks with no outcome attached, or a percentage with no counts behind
it. If the report would look identical in a good month and a bad one, it is an activity
report.

Two rules:

- **Never invent or estimate a figure**, and never present a metric you were not given. If
  the number is not available, say it is not being measured yet and suggest it.
- **Never claim credit for something the work did not cause.** Where you cannot tell, say
  the movement is not attributable.

**This skill drafts. It does not send.** Say where the file is and that it is ready for the
user to review and send. Never offer to email it to the client.

Close by listing any gaps and saying how many there are.
