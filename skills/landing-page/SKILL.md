---
name: landing-page
description: Use when the user needs one page to convert one offer — "a landing page for this promotion", "a page to send my ads to", "a sign-up page for the workshop", "where should this ad point". Produces a single page with one offer, one action and nothing competing with it. For copy across a whole site with several pages, use website-copy.
---

# Landing page

One page, one offer, one action.

Separate from `website-copy` because it has a different job. A site page helps someone
find their way around. A landing page removes every way out except the one you want.

## Read the brief

Look for `business-brief.md` in the working directory or the project's files.

- **Found:** read it. The offer, price, exclusions, customer, proof and voice all go
  straight onto this page.
- **Not found:** carry on, but ask for the offer, the price and who it is for. A landing
  page without a price converts badly and is worth saying so.

## What it needs

- **The one offer.** If they name two, ask which — two offers on a landing page is the
  commonest reason they do not convert.
- **The one action.** Buy, book, enquire, or sign up. One.
- **Where the traffic comes from.** A page for a paid ad, an email list and a QR code on a
  van are written differently, because the reader arrives knowing different amounts.

## Process

### 1. Match the entry point

The first line must connect to whatever they just clicked. If the ad promised something,
the page's first line delivers on it in the same words. A mismatch here loses most of the
traffic before the second section, and no amount of good copy below recovers it.

If `ads-<offer>-<platform>.md` exists in the working directory, read it and match the
winning promise.

### 2. Lead with the specific promise

What they get, for whom, and what it costs. Not a headline about the industry. Specific
beats clever — "Books caught up in a fortnight, fixed price" beats anything with a pun.

### 3. Structure it to one decision

A workable order:

- **The promise** — headline and one supporting line
- **What it is** — plainly, in a short list
- **The price** — and what is not included
- **Proof** — only what the brief supports
- **What happens next** — the steps after they click, which removes the fear of clicking
- **The action** — repeated, same wording as the first time

### 4. Say the price

On the page. If the user resists, say once that a landing page without a price mostly
collects tyre-kickers and wastes the ad spend that sent them. If they still decline, write
what qualifies people instead — a range, a starting-from, or who it is not for.

### 5. Handle the two biggest objections, briefly

Not a full objection list — the two that stop this specific purchase, answered in a line
each. If they need more than that, point at `objection-handler`.

### 6. Strip everything that competes

No navigation. No links out. No secondary offer, no newsletter box, no "you might also
like". Every element on the page either moves them toward the one action or is deleted.

Say explicitly what you have removed and why, because the instinct to add things back is
strong.

### 7. Say what it needs to work

The image, the form fields, where the button goes, and what happens after they click.
A page with no thank-you state is unfinished.

## Output

Write to **`landing-<offer>.md`**.

```markdown
# Landing page — <offer>

**One action:** <buy / book / enquire / sign up>
**Traffic from:** <where> · **Matching promise:** <the words they arrived expecting>

---

## <Headline>
<Supporting line.>

**[<Button text>]**

## What it is
- <specific>

## What it costs
**<Price>** — <what it includes>
**Not included:** <the exclusions>

## <Proof heading>
<Only what the brief supports.>

## What happens next
1. <step>

## <The two objections>
**<Objection>** — <one line>

**[<Button text — same words as above>]**

---

## Page notes
- **Image:** <what it shows>
- **Form fields:** <the minimum that works>
- **After they click:** <the thank-you state, and what is sent>

## Removed deliberately
- <element> — <why>
```

## Quality bar

**Good:** a stranger could read it in thirty seconds and know what it is, what it costs and
what to do — and there is nothing else on the page to do.

**Failed:** a page with a navigation bar and three calls to action. Or a headline that
could sit above any business in the sector.

Never invent proof, a guarantee, a countdown, a stock level or a customer number. False
scarcity on a landing page is both the most tempting and the most damaging invention in the
pack — it is public, it is measurable, and customers screenshot it. Only use urgency the
user has confirmed is real.

Close by listing gaps and saying how many there are.
