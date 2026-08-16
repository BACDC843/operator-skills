---
name: sop-writer
description: Use when the user wants a specific job or process written down so someone else can do it — "write an SOP", "document how we do X", "write this up so Dave can do it", "I need to hand this over", "what do I give a new starter for this task". Produces a followable SOP for one process, with owners, steps, failure modes and a review date. For designing a process that crosses several people or systems, use workflow-designer.
---

# SOP writer

One process, written so the person doing it can follow it without asking.

Written for the person doing the job, not for a binder. The test is whether someone who has
never done it gets to the end without a question.

## Read the brief

Look for `business-brief.md` in the working directory or the project's files.

- **Found:** read it for constraints, capacity and anything the business must never do —
  those become checks inside the steps.
- **Not found:** carry on. An SOP needs the process, not the business. Mention
  `business-brief` once at the end.

## What it needs

- **The process, walked through once.** Ask them to talk it through as they actually do it,
  not as they think it should be done. The gap between the two is where SOPs fail.
- **Who does it**, and what they are assumed to already know. An SOP for an experienced
  team member and one for a first-week starter are different documents.
- **What "done" looks like.** If nobody can say, the process has no definition of finished
  and that is the first thing to fix.

If they describe branching — "unless it's a Friday", "if it's a big client" — capture the
branches. Those are the parts people get wrong.

## How this differs from `workflow-designer`

Worth checking before starting, because the two get confused:

- **This skill** documents **one job, one person**, as instructions to follow.
- **`workflow-designer`** designs **how work moves between people, stages and tools**.

If what they describe involves three people handing work to each other, it is a workflow.
Say so and point them there rather than writing an SOP that only one of the three can use.

## Process

### 1. Fix the boundaries

State where the process starts, what triggers it, and where it ends. Confirm both.
Most unusable SOPs are unusable because they start halfway through.

### 2. Write the steps as instructions

Numbered. One action each. Start with a verb. Name the actual tool, screen, form or person
— not "the system".

Where a step needs judgement rather than an action, say what to weigh and what a good
decision looks like. Do not pretend judgement is a click.

### 3. Mark who owns each step

Where more than one person is involved, name the role against each step and mark handoffs
explicitly. A handoff nobody owns is where the process stops.

### 4. Write the failure modes

The part that separates this from a numbered list. For each step likely to go wrong: what
goes wrong, how to tell, and what to do about it.

Get these from the user — ask what actually goes wrong, and what they have had to fix
before. Their answers are worth more than anything predicted. If they say nothing ever goes
wrong, ask what they check before calling it done; that reveals the same thing.

### 5. Say what must never happen

Where the brief's Constraints or the process itself has a hard line — a claim never made, a
discount never given, a thing never sent without a check — put it in a box of its own, not
buried in a step.

### 6. Put a review date on it

A real date, and who owns the review. An SOP with no review date is out of date within a
year and nobody knows which parts.

## Output

Write to **`sop-<process>.md`**.

```markdown
# SOP — <process>

**Owner:** <role> · **For:** <who does this> · **Review by:** <date>
**Starts when:** <trigger> · **Done when:** <the definition of finished>

## Before you start
- <what you need to hand — access, information, tools>

## Steps

**1. <Verb-first instruction>** — *<role, if it varies>*
   <Detail only where needed. Name the actual tool.>

**2. <Instruction>**
   > **Judgement call:** <what to weigh, and what good looks like>

   → **Hand off to <role>**

## When it goes wrong

| What happens | How you know | What to do |
|---|---|---|
| <failure> | <the signal> | <the fix, or who to ask> |

## Never
- <the hard line>

## Review
**By <date>**, <role> checks this still matches how the job is done.
```

Aim for one page. Two if the process has more than about eight steps. Do not pad a
three-step process into a document.

## Quality bar

**Good:** someone who has never done this could follow it start to finish without asking a
question, and would know what to do the first time something went wrong.

**Failed:** a description of the process rather than instructions for it. If a step says
"ensure the invoice is processed correctly", nobody can follow it — say what to click, what
to check, and what correct looks like.

Never invent a step, a tool name, a threshold or an approval limit. If the user did not say
what the discount ceiling is, mark it `[gap]` rather than choosing a number — an invented
limit in an SOP gets followed. Close by listing the gaps and saying how many there are.
