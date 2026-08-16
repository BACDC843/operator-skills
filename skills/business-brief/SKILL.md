---
name: business-brief
description: Use when the user wants Claude to learn their business once and remember it — "set this up for my business", "stop asking me the same questions", "tell Claude about my company", "get you up to speed". Runs a short interview and writes a business-brief.md that every other skill in this pack reads, so the user never explains their business from scratch again.
---

# Business brief

Interview the owner once and produce `business-brief.md` — the file every other skill in
this pack reads before it does anything.

Fifteen minutes of their time. Not fifty questions.

## Read first

Look for an existing `business-brief.md` in the working directory or the project's files.

- **Found:** do not start over. Show them what it currently says in a short summary, and
  ask whether they want to update a section, add something new, or replace it entirely.
  Most returns to this skill are a price change or a new offer, not a rewrite.
- **Not found:** carry on below.

## What it needs

Nothing. This skill is the one that gathers everything, so it starts from a blank page.

If they have a website, ask for the URL early — reading it answers a chunk of the questions
before they are asked, and demonstrates the point of the whole exercise. If they paste
existing material (a brochure, an about page, an old brief), read it and treat every
question it answers as answered.

Know which chunk, because it is always the same one. A website reliably gives you what the
business is, what it sells, and roughly who for. It almost never gives you the price of a
B2B or service offer, which offer they most want to sell, what makes someone finally pick
up the phone, or a single word they refuse to use. Spend the time saved on those, not on
re-asking what the site already told you.

Two rules when reading a site:

- **If it contradicts itself, do not choose.** Sites carry two prices for the same thing
  more often than you would think. Record both, mark it, and ask which is current. Quietly
  picking one puts a wrong number into every quote every other skill ever writes.
- **If you cannot read it, say so.** A site that returns nothing useful is not a business
  with nothing to say. Tell them plainly that you could not read it, ask them to paste the
  about page or a brochure, and carry on with the interview. Never proceed as though the
  site were empty.

## Process

Five phases. Work through them in order and confirm each before moving on. Aim for eight
to twelve decisions total across all five — if it is running longer than that, you are
asking things you could infer.

Open by telling them what this is and how long it takes. Something like: *"I'll ask you
about a dozen things and write them into a file the other skills read. Fifteen minutes,
and you never have to explain your business again. If you have a website, give me the
address and I'll do some of it myself."*

If their answers start coming back vague — *"professional but friendly"*, *"we care about
quality"* — show them [references/worked-example.md](references/worked-example.md) instead
of asking the same question again more slowly. A finished brief moves people faster than
another question does, and it shows them the level of specificity that is actually wanted.

### Phase 1 — What the business is

Name, what it does in one sentence, where it operates, how long it has been going, how
many people.

If they gave a website, read it first and **propose** these back rather than asking. "Your
site says you do X for Y in Z — is that still right?" is a better question than "what does
your business do?", and it shows the tool is paying attention.

### Phase 2 — What it sells

The offers, and the price of each. This matters more than anything else in the brief —
`sales-script`, `proposal-writer`, `pricing-strategy` and `landing-page` are all much worse
without real numbers.

- Get the actual prices. If they will not say, record the price as `[withheld]` rather than
  leaving the field blank — that tells other skills to work around it. A price you simply
  have not asked about yet is `[not asked]`, which tells them to ask. The two are not the
  same instruction and must not both come out as `[gap]`.
- Ask which offer they most want to sell more of. Several skills default to it.
- Record what is **not** included as well as what is. Proposals fail on exclusions.
- **Cap it at about five offer blocks.** A business with twelve services has offer
  families, not twelve offers; group them and say so. Any grouping you invented is a guess
  about their business — mark it and get it confirmed, because every other skill will sell
  from it.

### Phase 3 — Who it is for

The customer, in their own words. The problem the customer has before they call. What
usually triggers the call.

Ask what a **bad** fit looks like too. Knowing who to turn away is more useful to the
other skills than another paragraph about the ideal client, and most owners have a much
sharper answer for it.

### Phase 4 — Voice

The hardest thing to get from questions, so mostly do not ask — collect evidence instead.

- Ask for two or three pieces of writing they were happy with: a post, an email, an about
  page. Real examples beat any description of a tone.
- Ask for words and phrases they never want used. Almost everyone has a list, and it is
  immediately actionable.
- Ask one question about formality — do they write to customers the way they'd speak in a
  meeting, or more carefully than that?

Do not ask them to describe their brand voice in the abstract. Nobody can, and the answer
is always "professional but friendly", which is worth nothing.

Most businesses write in two voices — the one on the sales page and the one in their FAQs
or their own emails. They are rarely the same, and the sales page is rarely the better of
the two. When the excerpts disagree, do not average them and do not pick silently: show
them both and ask which one a customer should hear. Whichever you record is inherited by
every other skill in the pack.

### Phase 5 — Proof and constraints

- **Proof:** real results, named clients they may reference, numbers they can stand
  behind. Only what is genuinely true and genuinely usable — this section exists so other
  skills stop inventing statistics, so anything shaky is worse than nothing.
  Anything lifted off their website needs a date against it or a note to verify. An award
  from 2017 recited as current is not something you invented, and it is just as wrong in
  front of a customer.
- **Constraints:** what they do not do, regulated claims they must avoid, capacity limits,
  anything a document must never say.

Close by writing the file, telling them where it is, and saying in one sentence what to do
with it — keep it in the folder or project they work in, and the other skills will find
it. Mention that they can come back and change it any time. Then stop; do not pitch the
rest of the pack.

## Output

Write to **`business-brief.md`** in the working directory, following
[references/brief-template.md](references/brief-template.md).

Then tell them, briefly:

- where the file is
- how many markers are left in it, and how many of those are `[not asked]` — those are the
  ones they can close in a two-minute follow-up, and worth separating from the rest
- the one section most worth improving later, and why

## Quality bar

**Good:** another skill can read the file and write a sales script with a real price in
it, in this business's actual voice, without asking a single question.

**Failed:** the file is full of generalities that would fit any business in the industry.
"We pride ourselves on quality service" is a sign the interview did not push hard enough —
go back and ask for the specific instead.

Two rules that override the desire for a complete-looking document:

- **Never fill a section by inventing.** A `[gap]` is a correct answer. An invented price,
  client name or statistic gets copied into a proposal three weeks later and read by a
  customer.
- **Their words, not yours.** Where they described something well, quote them. A brief
  written entirely in your prose loses the thing it exists to capture.

Close by saying what you could not do — a website you could not read, a section they did
not want to answer, anything you had to infer and mark for confirmation.
