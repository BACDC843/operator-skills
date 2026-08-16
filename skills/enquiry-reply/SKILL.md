---
name: enquiry-reply
description: Use when someone has contacted the business and the user wants to reply — "someone enquired about a job, write them back", "reply to this enquiry", "what do I say to this customer", "draft a response to this email". Writes the reply in the business's voice and, if the user has a mail connector, can send it — showing the exact message and the exact recipient and asking first, one message at a time.
---

# Enquiry reply

Reply to someone who has just contacted the business, in the business's voice.

**This is the only skill in the pack permitted to send anything.** That permission is
narrow and comes with a confirmation pattern that is not optional. It is set out in full
under "Sending" below, and nothing about it is discretionary.

## Read the brief

Look for `business-brief.md` in the working directory or the project's files.

- **Found:** read it. Voice, prices, exclusions, capacity and constraints all bear on the
  reply. A reply quoting a real price in the owner's own voice is the whole point.
- **Not found:** carry on. Ask what the business does and what it charges for the thing
  being asked about. Mention `business-brief` once at the end.

Markers bind, and they bind harder here than anywhere else, because this goes to a
customer. `[withheld]` means do not quote a price — say how pricing works and offer a call.
`[gap]` means say you will confirm, never guess.

## What it needs

- **The enquiry itself.** Pasted, forwarded or summarised. Work from their actual words.
- **What the user wants to happen next** — book them in, quote them, ask a question, or
  turn them down politely.

## Process

### 1. Work out what they actually asked

Read the enquiry properly. People bury the real question in the second paragraph, and a
reply that answers the first sentence only reads as automated.

If they asked three things, answer three things.

### 2. Check it against the brief before writing

Three checks, every time:

- **Is this a good fit?** If the brief's bad-fit description matches this enquiry, the right
  reply is a polite no with a referral if possible. Say so to the user before writing a
  reply that chases work they do not want.
- **Is there capacity?** If the brief says they are full, the reply should say when, not
  imply immediate availability.
- **Is there a price for this?** Quote it if there is. If not, say how it is worked out and
  what happens next.

**A price that depends on a number they did not give is a gap, not a calculation.** If the
rate is per head, per payslip or per unit and they have not said how many, quote the rate
and ask for the number. Do not work it out from context — "six lads plus me" is not
obviously six or seven, and whichever you pick becomes a total the business is held to. The
same rule applies to a price band: if they sit between two, quote neither and say you will
confirm.

### 3. Write the reply

Short. Answer the question first, then anything else. In their voice, from the brief's
excerpts — not in customer-service language.

- Give the real price where there is one, and what it does not include.
- One clear next step, with a date or a way to book.
- No "thank you for reaching out". No "I hope this email finds you well".
- If something needs checking, say you will check and by when.

### 4. Show it, and stop

Show the user the draft. Do not send yet. Do not ask about sending yet. Let them read it
and change it.

## Sending

**Only after they have seen the draft and asked for it to go.**

### If there is no mail connector

Write the reply, say plainly that it was not sent and why, and tell them where the text is
so they can send it themselves. **Stop there.** Do not look for another way to deliver it,
do not suggest a workaround, and do not treat a missing connector as a problem to route
around.

### If there is a connector, the confirmation pattern

Every single time, without exception:

1. **Show the exact message body** as it will go out. Not a summary. Not "the reply above".
   The full text, again, at the point of sending.
2. **Show the exact recipient address**, on its own line, so it can be read at a glance.
3. **Ask, and wait.** Not "shall I proceed?" — name it:
   > Send this to `name@example.com`?
4. **Send that one message.** Then say what went where.

And the rules around it:

- **Never batch.** One confirmation per message. If there are four enquiries, that is four
  drafts, four confirmations and four separate sends. "I'll send the other three the same
  way" is exactly the failure this pattern prevents.
- **Never infer consent.** Approving a draft is not approving a send. Approving one send is
  not approving the next. A general "yes, send them" does not authorise a specific message
  the user has not seen at the point of sending.
- **If they decline**, say plainly that nothing was sent, and leave the draft.
- **If anything is unclear** — two possible addresses, an ambiguous instruction — do not
  send. Ask.

## Output

Write the draft to **`reply-<who>.md`** so it survives the conversation, and say where it
is.

```markdown
# Reply to <name> — <date>

**They asked:** <what they actually wanted, in one line>
**Fit:** <good fit / bad fit — and why, if bad>
**Price quoted:** <the number, or why none>

---

<the reply, exactly as it would be sent>

---

**Sent:** <yes, to address, at time — or "no, not sent">
```

## Quality bar

**Good:** it answers what they asked, in the owner's voice, with a real price and one clear
next step — and the owner would have sent it without editing.

**Failed:** a polite acknowledgement that answers nothing and asks them to book a call to
find out the price. That is the reply that loses the job.

Two rules that override the desire to be helpful:

- **Never invent a price, an availability date, a turnaround time or a credential.** This
  text goes to a customer and becomes something the business is held to.
- **Never send anything the user has not seen and confirmed at the point of sending.** Not
  a follow-up, not a correction, not a second message to the same person. One message, one
  confirmation.

Close by saying what you could not do, and whether anything was sent.
