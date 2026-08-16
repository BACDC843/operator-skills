---
name: pricing-strategy
description: Use when the user needs to set or change what they charge — "what should I charge for this", "am I too cheap", "I want to raise my prices but I'm scared", "how do I package this". Produces a price with the reasoning shown, so it can be defended in a room. For researching what competitors charge use market-research; for writing the price into a client document use proposal-writer.
---

# Pricing strategy

A price, and the reasoning behind it written out, so the owner can defend the number when
somebody pushes back.

The only test that matters is whether they can say the number out loud without discounting
it. That takes reasoning, not a formula.

## Read the brief

Look for `business-brief.md` in the working directory or the project's files.

- **Found:** read it. Current prices, what is and is not included, the customer, the bad-fit
  answer and capacity all bear directly on this.
- **Not found:** carry on. Ask what the offer is, what they charge now, and what it costs
  them to deliver. Mention `business-brief` once at the end.

## What it needs

- **What the offer actually includes**, and what it does not.
- **What it costs to deliver** — their time at minimum. Most underpricing traces to an
  owner who has never counted their own hours into the cost.
- **What they charge now**, if anything, and what happens when they say it.

If they do not know their delivery cost, work it out with them before pricing anything.
A price set without it is a guess, and this skill should say so rather than proceeding.

## Process

### 1. Establish the floor

What it costs to deliver, including the owner's time at a rate they would actually accept.
This is the number below which the work is a hobby. Say it plainly.

Do not skip this because they seem to want a market-based answer. Owners who cannot say
their floor are the ones who discount under pressure.

### 2. Establish what it is worth to the customer

Not what it costs — what changes for them. Where the brief describes the problem before
they call, price against that. A bookkeeping service that removes a deadline they are
quietly worried about is not priced by the hour.

Where you do not know the value, say so. Do not manufacture a figure to justify a markup.

### 3. Look at the alternatives honestly

What the customer would otherwise do: a competitor, doing it themselves, or nothing.
"Nothing" is the most common competitor and the most often ignored.

If they have real competitor prices, use them. If they do not, **do not invent them** —
say what is unknown and point at `market-research`.

### 4. Propose a price, and show the arithmetic

One number, or a small structure. Show how the floor, the value and the alternatives
produced it. The reasoning is the deliverable; the number without it cannot be defended.

Where a rise is warranted, say by how much and over what period. A rise the owner will not
actually implement is worth nothing — propose one they will.

### 5. Say what has to change for the price to hold

A higher price usually needs something to change: an exclusion enforced, a faster response,
a clearer scope. Say which. Raising a price while delivering the same thing the same way is
the version that fails.

### 6. Say what to do about existing customers

The part that stops people acting. Who moves, when, what they are told, and who stays on
the old price and for how long. Write the sentence they will send.

### 7. Say what would tell you it is wrong

Two signals: one that says it is too high, one that says still too low. Nobody wins every
quote, and a rise that loses nobody was too small.

## Output

Write to **`pricing-<offer>.md`**.

```markdown
# Pricing — <offer>

**Now:** <current price, or none> → **Proposed:** <the number>

## The floor
<Cost to deliver, including the owner's time. The number below which this is a hobby.>

## What it is worth to them
<What changes for the customer. From the brief where possible.>

## The alternatives
- <Competitor, or "doing it themselves", or "nothing">

## The price, and how it was reached
<The arithmetic, in plain words.>

## What has to change
- <the thing that must be true for this price to hold>

## Existing customers
- **Who moves:** <who> · **When:** <date> · **What they are told:**
> <the actual sentence>

## What would tell you this is wrong
- **Too high:** <signal>
- **Too low:** <signal>

## What I could not establish
- <unknowns — competitor prices, delivery cost, value>
```

## Quality bar

**Good:** the owner could be asked "why is it that much?" by a sceptical customer and
answer in two sentences without apologising.

**Failed:** a number with a percentage attached to the old one. If the reasoning would
justify any number equally well, no pricing work was done.

Never invent a competitor's price, a market rate, an industry margin or a willingness-to-pay
figure. These are the easiest numbers in the pack to fabricate convincingly and the most
damaging, because the owner will repeat them to a customer. Mark them unknown and say how
to find out.

Close by saying what you could not establish, and how much of the recommendation rests on
figures the user supplied versus assumptions you flagged.
