---
name: sales-script
description: Use when the user wants to know what to say to sell a specific thing — "what do I say on the call", "I freeze when they ask the price", "give me a script for selling X", "how do I pitch this", "someone's coming in tomorrow to talk about a job". Produces a call script for one offer at one real price, in the business's voice. For handling specific pushback in depth use objection-handler; for a written proposal use proposal-writer.
---

# Sales script

A script for one conversation, about one offer, at one real price.

Generic sales scripts fail on the same line every time: the price. This one reads the real
number from the brief and says it out loud without flinching.

## Read the brief

Look for `business-brief.md` in the working directory or the project's files.

- **Found:** read it. The offer, the price, the customer, the bad-fit answer and the voice
  all come from there. This skill is close to worthless without it, so if the brief exists
  but has no price, say so before writing.
- **Not found:** carry on, but ask for the offer and its price first. If they will not give
  a price, say plainly that the script will have a hole in exactly the place scripts fail,
  and write it with the gap marked.

Markers bind here. `[withheld]` means the script must handle the price conversation without
naming a number — say so explicitly rather than inventing one. `[gap]` means say it is
unknown.

## What it needs

- **Which offer.** One. A script covering three offers is a brochure.
- **The price**, or an explicit acknowledgement that there is not one.
- **The situation.** An inbound enquiry, a referral, a quote visit and a renewal are
  different conversations with different openings.

## Process

### 1. Establish what the call is actually for

Propose the outcome and confirm it. Most small-business sales calls should end in one of:
booked, quoted, or a clear no. Deciding which one this call is for changes everything that
follows.

A call aiming at "build the relationship" is a call with no script, and it is worth one
sentence of pushback.

### 2. Open by earning the next two minutes

Short. What they enquired about, what you do, and a question. Not a pitch. If the brief
records what triggers the call, name it — "you said the VAT deadline's in a fortnight"
does more work than any introduction.

### 3. Ask before telling

Three or four questions that establish whether this is a fit and what they actually need.
Write the questions out. The brief's **bad fit** section is the source here — the questions
worth asking are the ones that surface a bad fit early, because a fast no is worth more
than a slow maybe.

### 4. Say the price plainly

The centre of the script. Give the exact words, including the number. No softening, no
burying it mid-sentence, no "it's an investment of". State it, say what it includes and
what it does not, then stop talking.

Write the silence in as a direction. The instinct to fill it is what discounts the price.

### 5. Handle the two or three most likely responses

Only the ones this offer actually attracts, taken from the brief and the price point. Keep
each answer short. For anything that needs real depth, point at `objection-handler` rather
than writing a second skill inside this one.

### 6. Close by agreeing the next step, with a date

Not "I'll send something over". A date, a time, and who does what. Include the words for a
clean no — a script that cannot end a call politely is a script that wastes their week.

## Output

Write to **`sales-script-<offer>.md`**.

```markdown
# Sales script — <offer>

**Situation:** <inbound / referral / quote visit / renewal>
**Aiming for:** <booked / quoted / a clear no>
**Price stated:** <the real number>

## Opening
> <the words>

## Questions to ask
1. <question> — <what the answer tells you>

## The offer, and the price
> <the words, including the number, and what is not included>

**Then stop talking.** <one line on why>

## If they say…
**"<the response>"**
> <the answer, short>

## Closing
> <the words, with a date>

## If it is a no
> <the words>
```

## Quality bar

**Good:** the owner can read the price paragraph aloud without adding a word, and the
questions would surface a bad fit inside two minutes.

**Failed:** the price appears once, softened, near the end. Or the script sounds like a
salesperson rather than the person in the brief's voice excerpts — most owner-operators
sell better as themselves than as anyone else.

Two rules that override the desire for a persuasive script:

- **Never invent a number, a client name, a result or a scarcity claim.** "Only two slots
  left" said untruthfully is the fastest way to lose a referral market, which is where most
  of these businesses live.
- **Never write a line that would embarrass them.** If the owner would not say it to a
  neighbour, cut it.

Close by saying what you could not do — a price you were not given, an objection you could
not anticipate without knowing the market.
