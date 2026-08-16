---
name: market-research
description: Use when the user wants to find out what is actually true about a market, competitor, audience or trend — "is there demand for this", "who else does this in my area", "what are people charging", "should I move into X". Produces a report that labels every claim as evidence or inference and says plainly what could not be established. For pricing a specific offer use pricing-strategy.
---

# Market research

Research a market, audience, competitor or trend, and report what is **known** separately
from what is **inferred**.

The value is not the finding. It is that the buyer can tell which parts they can bet money
on and which parts are a reasonable guess.

## Read the brief

Look for `business-brief.md` in the working directory or the project's files.

- **Found:** read it, so the research is framed against their actual offer, geography and
  customer rather than the industry in general.
- **Not found:** carry on. Ask what they sell and where, because a market question is
  meaningless without both. Mention `business-brief` once at the end.

## What it needs

- **The actual question.** "Research my market" is not answerable. Turn it into one
  specific question before starting, and confirm it back. "Do enough people within twenty
  miles pay for monthly bookkeeping to support a second bookkeeper?" is answerable.
- **The geography**, where it matters. Most small-business questions are local, and
  national data will quietly mislead.

Say up front what you can and cannot reach. If you have web access, say you will search and
cite. If you do not, say so immediately and offer the alternative: work from what they
paste in, plus reasoning clearly labelled as reasoning. Never let a user believe a finding
was researched when it was recalled.

## Process

### 1. Fix the question

Restate the question in one sentence and get it confirmed. Break it into the two or three
sub-questions that would actually answer it. Research against those.

### 2. Gather, and record where each thing came from

For every substantive claim, keep the source. A finding without a source cannot be labelled
evidence later, and unlabelled findings are the failure this skill exists to prevent.

Where sources disagree, say so and give both. Disagreement between sources is a finding.

### 3. Sort every claim into one of three buckets

This is the core of the skill, and nothing may skip it:

- **Evidence** — something established, with a source and a date. Cite it.
- **Inference** — a reasonable conclusion drawn from evidence. Say which evidence, and how
  confident, in plain words rather than a percentage.
- **Unknown** — the question was asked and could not be answered. Say what would answer it.

An unknown is a real deliverable. A report with no unknowns in it has usually hidden them.

### 4. Answer the question

Directly, in the first paragraph, in one or two sentences. Then support it. A report that
makes the reader hunt for the answer has failed regardless of the research quality.

If the honest answer is that there is not enough evidence to say, that is the answer. Write
it plainly and say what would need to be found out.

### 5. Say what to do about it

Two or three concrete next steps, each tied to a finding. If the recommendation is to find
something out before committing money, say that — it is frequently the correct answer.

## Output

Write to **`research-<topic>.md`**.

```markdown
# <The question, as a question>

**Short answer:** <one or two sentences, no hedging beyond what the evidence requires>

**Researched:** <date> · **How:** <web search, with sources / from material the user
supplied / no sources reached — reasoning from the brief only>

## What the evidence shows
- **<Claim>** — <source, date>

## What can reasonably be inferred
- **<Inference>** — from <which evidence>. <How much weight it carries, in words>

## What could not be established
- **<The open question>** — <what would answer it, and how they could find out>

## What to do
1. <Concrete step tied to a finding>

## Where sources disagreed
- <Only if they did>
```

## Quality bar

**Good:** a reader can act on the evidence section without checking it, and knows not to
bet the business on the inference section. Every number has a source and a date attached.

**Failed:** confident prose with no sourcing, where a real finding and a plausible guess
are written in the same voice. That is worse than no research, because it will be believed.

Two rules that override the desire to produce a complete-looking report:

- **Never invent a statistic, a market size, a competitor's price or a growth rate.** If it
  was not found, it goes in "could not be established".
- **Never present recall as research.** If you did not look it up in this session, say so.
  A remembered figure may be years out of date and cannot be cited.

Close by saying what you could not do, and roughly how much of the report rests on
inference rather than evidence.
