---
name: workflow-designer
description: Use when the user wants to design or fix a process that crosses several people, tools or stages — "how should this work end to end", "things keep falling through the cracks between us", "design the process for onboarding a client", "what should happen automatically and what shouldn't". Produces a workflow with triggers, stages, handoffs and an honest mark against every step that genuinely needs a human. For writing up one job someone already does, use sop-writer.
---

# Workflow designer

A repeatable workflow: what starts it, what happens, who hands to whom, and which steps
genuinely need a person.

The honest version of "runs without you". Most things can be automated; a few must not be,
and saying which is which is the whole value.

## Read the brief

Look for `business-brief.md` in the working directory or the project's files.

- **Found:** read it for constraints and capacity. Anything the business must never do
  becomes a hard stop in the workflow rather than a note at the bottom.
- **Not found:** carry on. Ask what the process is and who touches it. Mention
  `business-brief` once at the end.

## What it needs

- **The process, end to end, as it happens now** — including the parts that are somebody
  remembering. Those are usually where it breaks.
- **Everyone who touches it**, including the person who only gets involved when something
  goes wrong.
- **The tools already in use.** Design for what they have. A workflow that needs software
  they do not own is a purchase recommendation wearing a diagram.

## How this differs from `sop-writer`

Worth stating plainly, because the two get confused:

- **`sop-writer`** documents **one job, one person**, as instructions to follow.
- **This skill** designs **how work moves between people, stages and tools**.

If the answer is "one person does all of this", it is an SOP and you should say so rather
than inflating it into a workflow.

## Process

### 1. Name the trigger and the finish

What starts this, every time, without exception. If there are two triggers, there may be
two workflows. Where it ends, and what state things are in when it does.

### 2. Map what happens now, before improving it

Write the current process first, including the informal parts — the chase, the check, the
person who notices. Improving a process you have not described accurately produces a
workflow that describes nobody's job.

Ask where it currently breaks. That answer is usually the design brief.

### 3. Lay out the stages, with entry and exit conditions

For each stage: what must be true to enter it, what happens in it, who owns it, and what
must be true to leave. A stage with no exit condition is where work goes to sit.

### 4. Mark every handoff

Handoffs are where work is lost. For each: who hands to whom, how the next person knows,
and what happens if they do not pick it up within a stated time. "They'll see it" is not a
handoff mechanism.

### 5. Mark what needs a human, and be honest about it

Against every step, one of three marks:

- **Automatic** — no judgement, no consequence if done by a rule
- **Human check** — a rule does it, a person confirms before it goes further
- **Human decision** — genuinely needs judgement, and automating it would cause harm

Be honest in both directions. Marking everything human is the timid answer and produces a
workflow that saves nobody time. Marking a pricing exception, a complaint, or anything a
customer sees as automatic is the reckless answer. Anything a customer, prospect or supplier
would see gets at least a human check, however routine it looks.

### 6. Say what happens when it goes wrong

The exception paths: what happens to work that fails a stage, who owns stuck items, and how
long something can sit before someone is told.

### 7. Say what to build first

If the workflow implies changes, order them by what removes the most breakage for the least
work. One or two, not a programme.

## Output

Write to **`workflow-<process>.md`**.

```markdown
# Workflow — <process>

**Trigger:** <what starts it, every time>
**Ends when:** <the finish state>
**People involved:** <roles>
**Tools:** <what they already have>

## How it works now
<Short, honest, including the informal parts. Where it breaks today.>

## Stages

### <n>. <Stage name> — *<owner>*
- **Enter when:** <condition>
- **What happens:** <the work>
- **Leave when:** <condition>
- **Human?** <Automatic / Human check / Human decision> — <why>

→ **Handoff to <role>:** <how they know> · **If not picked up in <time>:** <what happens>

## When it goes wrong
| Fails at | What happens to the work | Who owns it |
|---|---|---|

## Build first
1. <change> — removes <the breakage>
```

## Quality bar

**Good:** every stage has an exit condition, every handoff has a mechanism and a timeout,
and the human marks would survive an argument with someone who wanted more automation.

**Failed:** a flowchart in prose. If the workflow does not say what happens when someone
does not pick something up, it describes a good day rather than a process.

Never invent a tool's capability, an integration that may not exist, or a volume figure. If
you do not know whether their system can do something, say so and mark it to check. Close
by saying what you could not do.
