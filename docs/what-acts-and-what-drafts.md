# Which skills act, and which only draft

The short version: **one of the twenty-two can send something. The other twenty-one write
files and hand them to you.**

This page exists so you can check that rather than take our word for it.

---

## The one that can act

### `enquiry-reply`

It can send an email reply to someone who has contacted your business, using whatever mail
connector is already on your account.

Before it sends anything, every single time, it must:

1. Show you the **exact message body** as it will go out — not a summary of it
2. Show you the **exact recipient address**, on its own line
3. Ask, and wait — *"Send this to name@example.com?"*
4. Send **that one message**, and then tell you what went where

And it will not:

- **Send in a batch.** Four replies means four separate drafts, four separate confirmations
  and four separate sends. There is no "send the rest the same way".
- **Treat your approval of a draft as approval to send it.** Those are two decisions.
- **Treat one approval as covering the next message.** Every send is its own confirmation.
- **Work around a missing connector.** If you have no mail connector it writes the reply,
  tells you plainly that nothing was sent, and stops.

If anything is ambiguous — two possible addresses, an unclear instruction — it asks rather
than guessing.

---

## The twenty-one that only draft

Every one of these writes a file and tells you where it put it. None of them send, post,
publish, book or submit anything.

`business-brief` · `launch-campaign` · `ad-creative-lab` · `market-research` ·
`content-calendar` · `social-post-writer` · `video-script` · `sales-script` ·
`objection-handler` · `proposal-writer` · `sop-writer` · `role-scorecard` ·
`workflow-designer` · `financial-summary` · `pricing-strategy` · `job-description` ·
`onboarding-plan` · `client-report` · `website-copy` · `landing-page` · `email-sequence`

That includes the ones where sending would be convenient. `proposal-writer` will not email
your proposal. `client-report` will not send your report. `email-sequence` will not load
your sequence into anything. `social-post-writer` will not post.

The reasoning: a wrongly-saved file is deleted in ten seconds. A wrongly-sent proposal is a
price a client holds you to, and a wrongly-posted post is a screenshot.

---

## Why the line is drawn there and not somewhere else

We did consider letting more of them act, and decided against it on cost of a mistake
rather than on principle.

A reply to someone who has just contacted you is low-stakes and high-frequency — you would
have written it in two minutes anyway, and if it is wrong you send a correction. A proposal
is neither. It goes out once, it contains a number, and it is the document a disagreement
gets settled against six weeks later.

So `enquiry-reply` acts and the rest draft. "One skill can send, and it asks first, every
time" is a promise we can keep, which is more use to you than either extreme.

---

## What none of them will do

- **Invent a fact.** Not a price, a client name, an award, a turnaround time or a
  statistic. Where something is missing you get a marked gap.
- **Give regulated advice.** `financial-summary` will not advise on tax.
  `onboarding-plan` and `email-sequence` will not state employment or consent law as fact.
  They say the question is regulated and tell you who to ask.
- **Manufacture urgency.** No invented deadlines, countdowns, stock levels or slot counts.
  `objection-handler` will refuse to write the manipulative version and tell you why.
- **Claim credit that is not earned.** `client-report` will say a month was quiet rather
  than padding it with activity counts.

---

## Checking this yourself

The skills are plain text. Open any `SKILL.md` in `skills/` and read it — there is nothing
hidden, no code, and no network calls. The rules above are written in the files themselves.

If you find a skill behaving differently from this page, that is a bug and we want to know:
https://github.com/BACDC843/operator-skills/issues
