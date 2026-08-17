# Executive partner briefing, motion edition

The deck: **https://angel-software-solutions-llc.github.io/top-spirit-motion/**

Prepared by Angel Software Solutions LLC for a discussion on 17 August 2026.
This repository is the whole of it. Nothing is minified, nothing is fetched
from a third party at view time, and the source of every slide is one file you
can read top to bottom.

## If you are reviewing this on the client side

You are welcome to. That is why the repository is public rather than a PDF in
an email. Four things are worth checking, and all four are checkable without
asking us anything.

**1. Every external claim carries a source, a date and a grade.** The grades
are printed on slide 1 and used consistently:

| Grade | Meaning |
|---|---|
| A | statute or audited filing |
| B | company or association reported |
| C | trade press citing named people |
| D | vendor published |
| E | our own offer or inference |

Exactly two claims on the deck are graded A. Both are statute and you can open
them yourself: the Austrian excise change in BGBl. I Nr. 62/2026, and the
articles of Regulation (EU) 2024/1689. Everything we could not stand behind at
grade C or better was removed rather than softened.

**2. The deck states what it does not claim.** Several slides carry an
explicit "not stated" or "we have not sized" line. Those are not hedges added
for tone. They mark the exact boundary of what we checked, including one place
where the arithmetic of a tax change is public and certain while its incidence
on any particular group is not, and we say so rather than implying otherwise.

**3. There is no price anywhere.** No fee, no saving, no duration, no day
rate, and no benchmark of anyone else's rates. We do not quote a number before
seeing one bounded extract, so quoting one here would be inventing it.

**4. There are no competitor case studies.** Not an oversight. When we traced
the widely circulated figures in this industry, most of them did not survive
being checked, so none of them are here. Ask us about any figure on the deck
and you will get its source or an admission that we do not have one.

## The commit history is part of the evidence

You will find that this deck was rebuilt and then corrected repeatedly over a
short period, and that several commits describe defects in our own work: a
chart drawn on a non-linear time axis, two sources graded above what the key
allows, a claim about tax incidence that overstated what our research
supported, an answer to a licensing question that belongs to the licence
holder rather than to us, and a label that crossed the very line it annotated.

That record is left intact deliberately. The full claim ledger, including the
claims we removed and why, is in [EVIDENCE.md](EVIDENCE.md). A deck that argues for evidence gates
and stop rules should be able to show its own, and the useful part of an audit
trail is the part where something was caught. If you would rather judge the
artifact than the process, read only the rendered page; if you want to know
how we work, the history is the honest answer and we would rather you had it.

You will also see ordinary commercial shorthand in some of those messages.
They were written as working notes between engineers, not as client-facing
copy, and we have not gone back to smooth them.

## Using it

Arrow keys, swipe, or click to move. Eleven slides. The transitions between
them are generated video, so the deck is roughly 100 MB and is best on a
reasonable connection.

Pressing **T** makes transitions instant. That is worth knowing if you are
watching over a shared screen and a clip stalls, and it is remembered for the
rest of the session.

**Printing** gives one landscape page per slide with the charts resolved and
the citations legible, which is the better format for checking sources at your
own pace.

## What is in here

| Path | What it is |
|---|---|
| `index.html` | the entire deck: markup, styles, charts and player |
| `media/slide-bg-*.webp` | the photographic background of each slide, with no text |
| `PartnerDA*.mp4` / `.webm` | the ten transitions, one per adjacent pair of slides |
| `fonts/` | the typeface, self-hosted so nothing is requested from elsewhere |

The charts are hand-built inline SVG. No charting library, no analytics, no
trackers, no external requests of any kind. You can verify that last claim by
opening the network tab, which is faster than taking our word for it.

## How the motion works, since it is unusual

Each slide is real HTML text over a text-free photograph. The video clips
carry only the photography, never the words: a clip begins on one slide's
background and is sealed onto the next slide's background, so fading the video
in reads as the text dissolving and fading it out reads as the next slide's
text arriving. The text never passes through a video encoder, which is why it
stays sharp, why it can be selected and read by software, and why the
citations are live text rather than pixels.

---

Angel Software Solutions LLC. Questions about any figure on the deck are
welcome, and the honest answer to some of them is that we do not know yet.
