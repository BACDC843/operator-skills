---
name: ad-creative-lab
description: Use when the user wants ads to test rather than one ad to run — "write me some Facebook ads", "I need ad variations", "test some headlines", "which of these would work better". Produces a set of paid ad variants where exactly one thing changes between them, so the results can be compared. For organic posts use social-post-writer; for the page the ad points at use landing-page.
---

# Ad creative lab

Produce a set of paid ad variants built as a real test: a control, and variants that each
change **one** thing.

Five rewrites of the same ad are not a test. They are five ads, and when one wins nobody
knows why.

## Read the brief

Look for `business-brief.md` in the working directory or the project's files.

- **Found:** read it. The offer, the price, the customer and the never-use words come from
  there. Confirm only the campaign specifics.
- **Not found:** carry on. Ask for the offer, its price, and who the ad is aimed at. Mention
  `business-brief` once at the end.

Respect the brief's markers — `[withheld]` means plan around it, `[not asked]` means ask if
this job needs it, `[gap]` means say it is unknown.

## What it needs

- **The offer, and its price.** An ad for an offer with no price is a brand ad, which is a
  different job and rarely what a small business should be buying.
- **The platform.** Character limits, whether an image carries text, and what the click
  does all differ. Do not write platform-agnostic ads.
- **What the click leads to.** If there is no page, say so — the ads are worth less and the
  user should know before spending.

If they have run ads before, ask what happened. A previous loser is worth more than a
fresh idea, because it narrows what to test.

## Process

### 1. Pick the variable

The whole skill turns on this. Propose **one** thing to test first and explain why:

- **The promise** — what the offer does for them. Test first when nothing has run before.
- **The audience framing** — who it is addressed to.
- **The objection led with** — price, time, trust, risk.
- **The format** — question versus statement, short versus long.

Do not test two variables at once, and say plainly why not if asked: with two variables
changed, a winner tells you nothing about which change caused it.

### 2. Write the control

One ad, straight down the middle, using the business's actual voice and a real price. This
is the thing everything else is measured against, so it must be genuinely good — a
deliberately weak control produces a meaningless win.

### 3. Write three to five variants

Each changes the chosen variable and nothing else. Everything not under test stays
identical to the control — same offer, same price, same call to action, same length band.

Name each variant by what it changes, not by a letter. "Leads with the price" is a result
you can learn from; "Variant C" is not.

### 4. Say how to read the result

Briefly: what to measure, roughly how long to leave it, and what result would be too close
to call. Do not invent a budget or a benchmark figure. If you do not know their traffic
volumes, say that the test needs enough of them to mean anything and leave the number to
them.

### 5. Note what should be tested next

One line. The second test usually follows from the first, and saying so stops the user
treating a single round as the whole job.

## Output

Write to **`ads-<offer>-<platform>.md`**.

```markdown
# Ad test — <offer> on <platform>

**Testing:** <the one variable>
**Why this one first:** <a sentence>
**Everything held constant:** <offer, price, CTA, destination>

## Control
**Primary text:** <copy>
**Headline:** <copy>
**Call to action:** <the button or ask>
**Image or video direction:** <what it should show — a direction, not a stock cliché>

## Variant — <what it changes>
<same fields>

## How to read this
- **Measure:** <the metric that answers the question being asked>
- **Too close to call:** <what would count as no result>
- **Test next:** <the follow-on variable>
```

## Quality bar

**Good:** the variants differ in exactly one identifiable way, the control is genuinely
strong, and every ad names a real price from the brief.

**Failed:** five ads that are each a bit different from all the others. If you cannot state
in one phrase what separates a variant from the control, it is not a variant.

Never invent proof — a statistic, a customer count, a "trusted by" claim — to make an ad
stronger. Ads are the highest-risk place in the pack for an invented fact, because they are
seen by strangers and paid for. Use only what the brief's Proof section supports, and say
at the end what you could not substantiate.
