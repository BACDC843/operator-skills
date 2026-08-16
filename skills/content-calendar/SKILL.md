---
name: content-calendar
description: Use when the user wants a plan of what to post over the coming weeks or months — "what should I post", "I need a content plan", "give me 90 days of ideas", "I never know what to write about". Produces dated ideas, each with the reason it exists and the channel it suits. It plans; social-post-writer writes the actual posts. For a launch with a fixed date use launch-campaign.
---

# Content calendar

Produce dated content ideas for a real period, where every idea has a reason to exist.

The test is not whether the calendar is full. It is whether the owner reads an entry three
weeks from now and knows immediately what to make and why.

## Read the brief

Look for `business-brief.md` in the working directory or the project's files.

- **Found:** read it. The offers, the customer, the constraints and the voice all shape what
  is worth posting. A calendar written without them is a list of industry topics.
- **Not found:** carry on. Ask what they sell, to whom, and where they post. Mention
  `business-brief` once at the end.

Respect the markers — `[withheld]` plan around it, `[not asked]` ask if needed, `[gap]` say
it is unknown rather than filling it in.

## What it needs

- **The channels they actually post on.** Not the ones they think they should. A calendar
  for four channels they cannot sustain is worse than one for the single channel they do.
- **How often they can realistically post.** Ask for the honest number, not the aspiration.
  Two a week that happen beat five a week that do not.
- **The period.** Default to 90 days and confirm. Ask whether anything is already fixed in
  it — a launch, a season, a closure, an event.

## Process

### 1. Find the anchors first

Before generating anything, establish what is already true about the period: seasonal peaks
and troughs, a launch, a quiet month, a deadline their customers face. The brief's customer
section usually says what triggers a call — that trigger has a season, and the calendar
should sit in front of it.

Anchors are what stop a calendar being ninety interchangeable days.

### 2. Set the mix, and propose it

Propose a rough split and get it confirmed. A workable default:

- **Useful** — answers a question the customer actually has
- **Proof** — the work, results, a job walked through
- **Point of view** — what they think, including what they disagree with
- **Ask** — the offer, plainly

Weight it toward the first two. Say the split out loud so the user can argue with it.

### 3. Generate against the anchors and the mix

Each entry gets a date, a channel, a working title, the job it does, and a one-line reason
it exists. The reason is the point — it is what makes the entry writable later and what
proves the idea was not filler.

Pull specifics from the brief. A calendar entry that says "post a customer story" is not
usable; "walk through the catch-up job that was nine months behind" is.

### 4. Leave the empty slots empty

**Refuse to fill a slot just because it exists.** If the honest count is thirty good ideas
across ninety days, produce thirty and say so. Padding the rest with generic prompts is how
these calendars end up abandoned in week three — the owner hits a filler entry, has nothing
to say, and stops.

Say plainly at the end how many entries are genuinely strong and how many are thinner.

### 5. Mark what needs something they do not have yet

Some good ideas need a photo, a customer's permission, or a figure they have not measured.
Mark those so they can be arranged, rather than discovering it on the morning.

## Output

Write to **`content-calendar-<period>.md`**.

```markdown
# Content calendar — <period>

**Channels:** <the ones they actually use> · **Cadence:** <realistic frequency>
**Mix:** <the agreed split>

## Anchors in this period
- **<date or month>** — <what is happening, and what it means for content>

## <Month>
### Week of <date>
- **<date>** · <channel> · **<working title>**
  - **Job:** <what this is for>
  - **Why now:** <the reason it exists>
  - **Needs:** <photo, permission, figure — only if something is required>

## Honest assessment
- <n> entries that are genuinely strong
- <n> that are thinner and could be dropped
- <n> slots deliberately left empty, because <reason>
```

## Quality bar

**Good:** every entry names something specific to this business, and the owner could write
any one of them without asking what was meant.

**Failed:** entries that would fit any business in the industry — "share a tip", "post a
testimonial", "behind the scenes". If an entry survives find-and-replace of the business
name, it is filler and should be cut.

Never invent a customer story, a statistic or a result to fill an entry. If the idea needs
a fact they have not given you, mark it as needing that fact. Close by saying what you could
not do.
