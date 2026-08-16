---
name: social-post-writer
description: Use when the user has one thing to say and wants it written for the channels they post on — "write this up for LinkedIn and Instagram", "turn this into a post", "post about our new opening", "make this into something I can put out". Writes a separate post per channel rather than one post pasted everywhere, because the same words are wrong on at least two. For paid ads use ad-creative-lab; for what to post over time use content-calendar; for anything spoken on camera use video-script.
---

# Social post writer

One subject, one post **per channel**, written separately.

The same words are wrong on at least two of any three channels. A post written for
LinkedIn and pasted into Instagram reads as a person who does not use Instagram.

## Read the brief

Look for `business-brief.md` in the working directory or the project's files.

- **Found:** read it. Voice, never-use words and constraints all bind here — this is
  customer-facing writing, so the voice section does real work.
- **Not found:** carry on. Ask what the business does and what the post is about. Mention
  `business-brief` once at the end.

If the brief records a never-use list, treat it as absolute. Those words are the fastest
way for a buyer to lose trust in the whole pack.

## What it needs

- **The subject.** One thing. If they give you three, ask which one this post is about —
  three subjects in one post is why posts get scrolled past.
- **The channels.** Ask which ones, and only write for those. Never write for a channel
  they did not name because it seemed obvious.

If they paste something — a rough note, a voice memo transcript, an email they sent — work
from it. Their own phrasing is worth more than anything you would generate, and the
strongest posts are usually their words tightened rather than replaced.

## Process

### 1. Find the one thing worth saying

Before writing anything, state the single point in one sentence and confirm it. If the
subject does not reduce to one sentence, it is two posts.

### 2. Write each channel separately, from the point — not from the first post

Do not write one post and adapt it. Adaptation produces a good post and two translations of
it. Go back to the point each time and write it for that channel's reader.

What actually differs:

- **LinkedIn** — the reader is at work. Specifics, numbers, what was learned. Longer is
  allowed if it earns it. No hashtag walls.
- **Instagram** — the image carries the post; the caption supports it. Say what the image
  should be. Front-load the first line, because the rest is hidden behind "more".
- **Facebook** — often a local audience who may know them. Plainer, warmer, less
  performance. Local specifics land here that would be noise elsewhere.
- **X** — one idea, tight, no windup.
- **TikTok / Reels captions** — the caption is not the content. Keep it short and hand the
  work to `video-script`.

Where a channel is a poor fit for this subject, **say so and skip it**. Writing a bad post
for a channel because it was named is not service.

### 3. Say what the image or video should be

For any channel where the visual carries it, give a direction — what it shows, taken where,
by whom. Not a stock-photo description. If the honest answer is "a photo of the actual
thing", say that.

### 4. Check it against the constraints

Run each post against the brief's Constraints and Never claim sections before finishing.
This is the last point before something goes in front of customers.

## Output

Write to **`posts-<subject>.md`**.

```markdown
# <Subject>

**The point:** <one sentence>

## LinkedIn
<the post>

**Image:** <direction, if any>

## Instagram
<the caption, first line front-loaded>

**Image:** <what it should show>

## <Channel>
<the post>

---

## Not written
- **<channel>** — <why this subject does not suit it>
```

## Quality bar

**Good:** the posts could not be swapped between channels without reading wrong, and each
sounds like the person in the brief's voice excerpts rather than like a brand.

**Failed:** the same sentences with different hashtags. If two posts differ only in length,
go back to the point and write the second one again.

Never invent a result, a customer quote or a number to make a post land. Never manufacture
urgency the business did not ask for. Close by saying what you could not do — a photo you
could not specify, a claim you left out because the brief did not support it.
