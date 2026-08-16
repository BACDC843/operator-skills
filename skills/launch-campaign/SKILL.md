---
name: launch-campaign
description: Use when the user is launching something new and wants a dated plan for it — "we're launching a new service next month", "plan the launch", "we're opening a second location, what do I do and when", "how do I get the word out before we open". Produces a launch plan sequenced backwards from the launch date, with dependencies, blockers and a post-launch follow-up most people forget. For ongoing content with no launch date use content-calendar; for paid ad variants use ad-creative-lab.
---

# Launch campaign

Produce a dated launch plan for one specific thing, sequenced so the work happens in an
order that actually works.

Most people can write launch assets. Almost nobody gets the order right, and the order is
what decides whether a launch lands.

## Read the brief

Look for `business-brief.md` in the working directory or the project's files.

- **Found:** read it. Take the offer, its price, the customer and the voice from there and
  confirm only what this launch needs beyond it.
- **Not found:** carry on. Ask only for what a plan cannot be built without: what is
  launching, to whom, and the date. At the end, mention once that `business-brief` would
  remove those questions permanently.

Respect the brief's markers. `[withheld]` means do not ask again — plan around it.
`[not asked]` means ask, if this launch needs it. `[gap]` means unknown; say so in the plan
rather than filling it in.

## What it needs

Three things, and it cannot proceed without them:

1. **What is launching** — a specific offer, product, location or change. "The business"
   is not a launch.
2. **The launch date**, or the week. Everything is sequenced backwards from it.
3. **Where they can actually reach people** — the channels they already have. A plan built
   on a mailing list they do not have is fiction.

Everything else, propose and confirm. If they do not know their audience size, ask for a
rough number rather than leaving it open — the plan changes shape at 200 people and 20,000.

## Process

### 1. Establish the spine

Confirm the launch date and work out the four fixed points backwards from it: when
announcing starts, when the offer opens, when it closes if it closes, and when follow-up
happens. Propose these and let them adjust. Do not ask them to invent a schedule.

If there is no close date, say so plainly — an open-ended launch is a different plan and
usually a worse one, and it is worth one sentence of pushback before accepting it.

**Check capacity before sequencing anything.** Read the brief's Capacity line, or ask. If
the business is already at or near full, say so before writing the plan — driving demand
into a business with no room to serve it damages it, and the answer may be a waiting list
or a price rise rather than a campaign. Raise it once, plainly; if they want the launch
anyway, build it and note the constraint in the risks.

### 2. Work out what has to exist before anything is announced

The dependency pass, and the reason this skill exists. Before the announcement there is
usually a page to point at, a price decided, a way to take money, and someone briefed to
answer questions. List them, and mark anything that is not yet done as a blocker with the
date it must be finished by.

A launch plan that schedules an announcement before the thing being announced can be bought
is the most common failure here. Check for it explicitly.

### 3. Sequence the run-up

Phase the weeks before launch. Each entry gets a date, a channel, a job it does, and what
it depends on. Do not schedule an activity because a slot exists — if a week has nothing
worth saying, leave it empty and say why.

### 4. Launch week

Day by day. Say what goes out, where, and in what order. Where two things must happen in
sequence on the same day, say which comes first.

### 5. Post-launch follow-up

The part that gets cut and should not be. Include: what happens to people who looked and
did not buy, what happens to people who did, and a dated review of what the launch actually
produced. Put a real date on the review.

### 6. Say what could go wrong

Two or three specific, foreseeable risks with what to do about each. Not a risk register —
the two or three that would actually derail this launch.

## Output

Write to **`launch-plan-<offer>.md`**.

```markdown
# Launch plan — <what is launching>

**Launch date:** <date>
**Offer:** <name, and price if known>
**Audience:** <who, and roughly how many are reachable>

## Before anything is announced
- [ ] <blocker> — needed by <date> — <owner>

## Run-up
### Week of <date>
- **<date>** · <channel> · <what goes out> · <the job it does> · depends on: <what>

## Launch week
### <day, date>
- <what, in order>

## After
- **<date>** — <follow-up for people who did not buy>
- **<date>** — <follow-up for people who did>
- **<date>** — Review: <what to measure>

## What could go wrong
- **<risk>** — <what to do>

## Gaps
- <anything marked [gap], and what would close it>
```

Keep it to the length the launch needs. A one-channel launch to 300 people is a page. Do
not pad it to look like a campaign.

## Quality bar

**Good:** someone could work from this plan without asking a question, and the order
survives scrutiny — nothing is announced before it can be bought, and nothing depends on
something scheduled after it.

**Failed:** a list of assets with dates attached. If the plan would read the same with the
dates shuffled, the sequencing work was not done.

At the end, say briefly what you could not do — a figure you were not given, a channel you
could not assess, an audience size that was guessed.
