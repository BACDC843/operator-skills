---
name: financial-summary
description: Use when the user pastes in figures and wants to know how the business is actually doing — "here's my numbers for the month", "how did we do last week", "read my P&L", "am I actually making money on this". Produces a plain-English read-out with three judgements that stop the numbers flattering you. It reads figures the user supplies; it does not connect to their accounts.
---

# Financial summary

A weekly or monthly read-out from figures the owner pastes in, in plain English, with the
judgements that stop a good-looking month from being fiction.

## Read the brief

Look for `business-brief.md` in the working directory or the project's files.

- **Found:** read it for the offers and their prices, so revenue can be read against what
  they actually sell rather than as one number.
- **Not found:** carry on. Mention `business-brief` once at the end.

## What it needs

Figures the user supplies — pasted, uploaded, or typed. A period, and ideally the period
before it for comparison.

**This skill does not connect to anything.** If they have a bookkeeping tool, ask them to
export or paste. Never imply you have read their accounts, and never carry a figure over
from an earlier conversation as though it were current.

If the figures are incomplete, say what is missing before analysing. A summary built on
half a month is worse than no summary, because it gets believed.

## The three judgements

These are not optional, and they are the reason this skill exists. Apply all three before
saying anything about performance:

1. **Drafts are not owed.** A draft invoice is not revenue and not a receivable. It is a
   sentence someone wrote. Exclude drafts entirely and say how many were excluded.
2. **Refunds and credit notes come off revenue.** Not a separate line further down where
   they are read past. Off the top, in the headline number.
3. **An undated invoice is never late.** If there is no due date, it cannot be overdue.
   Report it as undated, which is a different and more useful problem — someone has to fix
   the invoice, not chase the customer.

State when each one changed the picture. "Revenue is £14,200, not the £18,900 on the
dashboard, because four drafts and two credit notes" is the most valuable sentence this
skill produces.

## Process

### 1. Say what you were given, and what you were not

One line. The period, what was included, what was missing. Sets the boundary before any
number is discussed.

### 2. Apply the three judgements, visibly

Show the adjustment, not just the result. The owner needs to see why the number differs
from the one their software showed them, or they will trust the software.

### 3. Report the headline in plain words

Revenue, costs, what is left, and whether that is better or worse than the period before.
No jargon, no ratios they did not ask for. If margin cannot be worked out from what was
supplied, say so rather than estimating it.

### 4. Say the two or three things that actually matter

Not everything that moved. The two or three that would change a decision. Where something
moved a lot, say what caused it if the figures show it, and say you do not know if they do
not.

### 5. Flag what needs attention, with the number attached

Overdue money with the amount and how overdue. Undated invoices, counted. A cost that grew
faster than revenue. A customer concentration risk if one client is most of the income.

### 6. Say what you could not tell

Explicitly. Cash position without a bank figure, profitability without costs, seasonality
without last year. This section is what makes the rest trustworthy.

## Output

Write to **`financial-summary-<period>.md`**.

```markdown
# Financial summary — <period>

**Figures supplied:** <what> · **Missing:** <what>

## The headline
<Two or three sentences in plain English.>

## Adjustments made
- **Drafts excluded:** <n>, totalling <amount> — not revenue
- **Refunds and credits:** <amount> taken off revenue
- **Undated invoices:** <n> — reported as undated, not overdue

## The numbers
| | This period | Last period | Change |
|---|---|---|---|
| Revenue (adjusted) | | | |
| Costs | | | |
| Left over | | | |

## What matters
- <the thing, with the number, and the cause if known>

## Needs attention
- <item, amount, how urgent>

## What I could not tell you
- <the limit, and what would close it>
```

## Quality bar

**Good:** the owner finishes it knowing one thing they did not know before, and every
number traces to something they supplied.

**Failed:** a restatement of their figures with adjectives. Or worse, a number that cannot
be traced to the input — if a figure appears that was calculated on an assumption, the
assumption must be stated next to it.

Two rules that override everything:

- **Never estimate, extrapolate or fill a missing figure.** Not costs, not a run rate, not
  an annualised projection. If it was not supplied, it is not known.
- **Never give tax, regulatory or investment advice.** Say plainly that the question is for
  their accountant, and say what to ask them. This is a hard line regardless of how the
  question is phrased.

Close by saying what you could not do.
