---
name: website-copy
description: Use when the user needs copy for a whole website or several pages of one — "write the copy for my new site", "my website says nothing, rewrite it", "I need words for all these pages", "redo my about and services pages". Works page by page against a real sitemap so the pages do not all say the same thing. For a single conversion page for one offer, use landing-page.
---

# Website copy

Copy for a whole site, written page by page against a real sitemap.

The failure this exists to prevent: five pages that each say the business is experienced,
customer-focused and quality-driven. Pages need different jobs or they need deleting.

## Read the brief

Look for `business-brief.md` in the working directory or the project's files.

- **Found:** read it. Offers, prices, customer, voice, proof and constraints all feed
  directly into pages. This skill is much weaker without it — say so if it is missing.
- **Not found:** carry on, but ask for the offers and at least one real price before
  writing a services page. Mention `business-brief` once at the end.

## What it needs

- **The pages.** Either their current sitemap or an agreed one. Do not start writing before
  the page list is settled.
- **What each page is for.** Established in step 1 if they have not thought about it.
- **Whether prices go on the site.** A real decision with consequences, and worth asking
  outright rather than assuming.

## Process

### 1. Agree the sitemap and give every page one job

Before any copy. For each page, one sentence: who lands here, and what they should do next.

If two pages have the same job, say so and propose merging them. Most small-business sites
are two or three pages too long, and cutting one is worth more than writing it well.

Propose a default structure and let them adjust — home, one page per offer, about, proof,
contact is a workable shape for most.

### 2. Write the home page last

It is the hardest and it summarises the others. Writing it first means writing it twice.

### 3. Write each page to its job, and keep them apart

Work through the pages one at a time. Before finishing each, check it against the ones
already written: if a paragraph could move to another page without anyone noticing, it is
not doing this page's job.

- **Offer pages** — what it is, who it is for, what it costs or how pricing works, what is
  not included, what happens next. The exclusions matter; they filter out bad fits before
  they take up an hour on the phone.
- **About** — why this business exists and who runs it. The single most-read page after
  home on a small-business site, and usually the worst written. Use the owner's own words
  from the brief.
- **Proof** — only what the brief's Proof section supports. If it supports nothing, do not
  create the page.
- **Contact** — what happens after they get in touch, and how quickly. Say the real
  response time.

### 4. Write the page furniture

For each page: the title tag, the meta description, and the heading structure. Not
decoration — for most of these businesses this is their only SEO work.

Write for the words a customer would actually search, from the brief's customer language.
Never stuff keywords, and never write a title tag that misrepresents the page.

### 5. Say what is missing

Photos, a case study, a figure they need to measure, a decision about prices. List it at
the end — the copy usually cannot ship without two or three of them.

## Output

Write to **`website-copy.md`**, all pages in one file, in sitemap order.

```markdown
# Website copy — <business>

## Sitemap and page jobs
| Page | Who lands here | What they do next |
|---|---|---|

---

## <Page name>

**Title tag:** <under ~60 characters>
**Meta description:** <under ~155 characters>

### <H1>
<copy>

#### <H2>
<copy>

**Call to action:** <the words, and where it goes>

---

## Before this can go live
- <missing photo, figure, decision>

## Pages I recommend cutting
- **<page>** — <why, and where its content goes instead>
```

## Quality bar

**Good:** every page has a job it alone does, and a stranger could work out what the
business sells and roughly what it costs within one page.

**Failed:** pages that could be shuffled without loss. Or an about page that describes an
industry rather than a person.

Never invent proof, client names, years in business, team size, accreditations or
statistics. A website is permanent, public and indexed — it is the worst place in the pack
for a confident invented detail. Use only what the brief supports and mark the rest.

Close by listing every gap and saying how many there are.
