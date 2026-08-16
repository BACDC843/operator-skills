# Installing on claude.ai

For anyone using Claude in a web browser or the desktop app. No technical knowledge needed.

**Time:** about two minutes for the first skill, ten for all twenty-two.
**You need:** a Claude account. Any paid plan works.

---

## The short version

Claude → **Customize** → **Skills** → **+** → **Upload a skill** → pick a `.zip` → toggle it on.

Repeat for each skill. That is genuinely all of it.

---

## Step 1 — Download and unzip

Download `operator-skills-v1.0.0-all-skills.zip` and unzip it.

Inside you will find **22 separate zip files**, one per skill, plus a README.

> **Do not upload the big zip.** Claude takes one skill at a time, so you upload the small
> zips inside it. Leave them zipped — you upload them exactly as they are.

**On Windows:** right-click the downloaded file → *Extract All*.
**On Mac:** double-click it.


---

## Step 2 — Open your Skills settings

In Claude, look at the **bottom left** of the window and click **Customize**.

Then choose **Skills**.



---

## Step 3 — Upload your first skill

Click the **+** button, then **Upload a skill**.

Choose **`business-brief.zip`**.

**Start with this one.** It interviews you about your business and writes a file the other
twenty-one skills read. Installing the others first works, but they will have to ask you
things this one would have already answered.


---

## Step 4 — Turn it on

After uploading, find the skill in your list and **toggle it on**.

A skill that is uploaded but switched off does nothing. This is the single most common
reason people think the pack has not worked.


---

## Step 5 — Run it

Start a new conversation and type:

> set this up for my business

Claude should start asking you about what you sell. It takes about fifteen minutes and you
only ever do it once.

When it finishes it produces a file called `business-brief.md`. **Keep that file.** See
[Where to keep your brief](#where-to-keep-your-brief) below.

---

## Step 6 — Install the rest

Repeat steps 3 and 4 for each of the other twenty-one zips.

You do not have to install them all. Install what you will use — you can always come back
and add more later.

If you are not sure where to start, these four earn their keep fastest for most businesses:

| Skill | Use it when |
|---|---|
| `enquiry-reply` | Someone contacts you and you need to reply |
| `sales-script` | You have a call coming up and freeze on the price |
| `proposal-writer` | A client asks you to "send something over" |
| `social-post-writer` | You have one thing to say and three places to say it |

---

## Where to keep your brief

`business-brief.md` is the file that makes the whole pack feel like it knows your business.
The other skills look for it in whatever conversation or project you are working in.

**The easiest thing that works:** create a Project in Claude for your business, and add
`business-brief.md` to that project's files. Then start your work conversations inside that
project. Every skill will find it.

Several skills also read files that other skills write — a landing page will use the ad test
you built earlier, and a new starter's onboarding plan will use the role scorecard. Keeping
your work in one project is what lets them find each other.

---

## If something is not working

**"Claude ignored the skill."**
Check it is toggled **on**. Then try wording your request the way the skill's description
does — for a proposal, "write a proposal for this job" rather than "help me with a client".

**"The wrong skill ran."**
Say which one you want by name: "use proposal-writer for this". Then tell us — the
description probably needs fixing, and that is a real bug worth reporting.

**"It asked me questions I already answered."**
Your `business-brief.md` is probably not visible in that conversation. Put it in a Project
and work inside the project, or paste it in.

**"The upload was rejected."**
Make sure you are uploading one of the 22 small zips, not the big bundle, and that you have
not unzipped the small one first — Claude wants the `.zip`.

**Still stuck?** https://github.com/BACDC843/operator-skills/issues — tell us what you typed and what
happened.

---

## Things worth knowing

- **Skills upload to your account**, so they work in every conversation on claude.ai. They
  do not sync to Claude Code or the API — those install separately.
- **Only one skill in this pack can send anything.** `enquiry-reply` can send a reply, and it
  shows you the message and the address and asks first, one at a time. See
  [Which skills act and which only draft](what-acts-and-what-drafts.md).
- **Nothing here needs Code execution.** If Claude asks you to enable capabilities, it is
  for something else.
