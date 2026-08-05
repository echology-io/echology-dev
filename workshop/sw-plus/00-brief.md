# 00 — Brief

## What this session is

An organizational discovery session, organized around one question stated in the
first two minutes: **what separates an AI deployment that works from one that fails?**

Everything else serves answering that for SW+ specifically. The subject is how their
engineering organization actually works; what we build appears in Part 5 as the
answer to a question the room has spent two hours asking.

Not a sales presentation. Not a software demonstration. But also **not a session that
opens by announcing what it is not** — see the framing rule below.

## Where the conversation already is

SW+ intends to deploy AI. What they do not have is the shape of a successful
deployment — what it costs, what it returns, what staffing looks like afterward, and
what has to be in place for it to work at all. Those are known unknowns, and they are
the reason for the meeting.

They have already been shown AI by someone who knows AI and does not know their
industry. That demo is the reference point everything today is measured against,
which is an advantage: the gap it left is exactly the gap you fill.

The champion — head of technology, and the reason this room exists — assembled it
deliberately across four levels: executive, IT and governance, technology deployment,
and practice. Your documentation has been circulating internally for about a month,
so a portion of the room has already read you before meeting you.

SW+ considered waiting for the next fiscal cycle. The champion argued against waiting,
on the reasoning that roughly $15k spent now to understand the opportunity lets
implementation be budgeted intelligently later.

That argument won. Read what it means:

- The question is no longer *should we*. It is *when*, and *what exactly*.
- The constraint is budget, not belief. Nobody in that room needs to be convinced
  that AI matters.
- The discovery is already funded. You are not selling discovery. You are performing
  it, in front of the people who paid for it, and the product of it is a specific,
  scoped, defensible next step.

**Consequence for the room:** do not spend a minute on why AI is important. It is
the one thing everyone present already agrees on, and re-arguing it will read as
either padding or as not having listened to the champion who spent political capital
on your behalf.

## Objectives, in priority order

**Primary — become remembered for clarity, not software.** The outcome you want is
SW+ referring to Kyle as the person who understands engineering organizations. That
is earned by the quality of the questions, not the quality of the answers.

**Secondary — surface their highest-value operational pain. Do not assume it.** You
will be tempted to. You have a working hypothesis about where knowledge disappears in
a multi-office civil firm. Hold it. If they name it themselves it becomes theirs, and
a pain they own is a pilot they defend at budget time. A pain you named for them is a
pain they can decline.

**Tertiary — leave able to build *their* prototype.** Not a generic demo with their
logo. That requires specifics most discovery sessions never collect: which workflow,
whose data, where it physically lives, who owns access, what "good" looks like, and
who judges it. `04-capture.md` forces those fields.

## The four conversations in the room

The champion assembled four levels, and they ask four different kinds of question.
Every part of the session has to satisfy all four simultaneously — you do not get an
executive segment and then an IT segment.

| Lane | The question they are silently asking | What satisfies it |
| --- | --- | --- |
| Executive | *What does this do for the business?* | Decision quality, risk, capability, retention, speed of learning. Cost, return, and what staffing looks like after. Not features. |
| IT & governance | *Can this be governed?* | Evidence, traceability, identity, boundaries. An honest "not yet" beats a confident yes. |
| Technology deployment | *How does this actually get rolled out?* | Integration with what exists, who administers it, what breaks, what it takes to support. |
| Practice | *Does this make engineers better?* | Their daily friction, named accurately by someone who has clearly seen it before. |

The deployment lane is the one most often collapsed into IT, and it should not be.
The people who roll something out have a completely different set of concerns from
the people who approve it — they are the ones who will be supporting it at 4pm on a
Friday, and they can kill an initiative quietly by declining to carry it.

A single well-chosen question can hit all four. "Where does organizational knowledge
disappear?" is a growth question to the VP, a records question to IT, a *who will
maintain this* question to deployment, and a *why do I answer the same question forty
times a year* question to a practice lead. Prefer questions with that property.
`03-question-bank.md` marks them.

**Say the four-lane structure out loud in Part 1**, framed as why the answers that
are not theirs are still worth their attention. Never as *be patient with me* — see
`02-run-of-show.md` Part 1, move 3.

## The hidden structure

The five parts are not five topics. They are one progression:

**Observe → Surface → Imagine → Construct → Answer**

That is the same order in which the thing being built actually works, which is why
the reveal lands as recognition rather than as a pitch. The room will have already
performed the architecture before it is named.

**Never say the section names out loud.** Do not announce "now we move to Part 3."
Do not say "current AI reality" or "thought experiment." A named agenda turns
participants into an audience waiting for the next item. Move from one to the next by
asking the first question of the next part as though it were the natural follow-up to
the last answer of the previous one — because it is.

The run sheet is for you. The room should experience one continuous conversation that
happens to change altitude four times.

## Core principle

Show. Never tell. Build, observe, ask, adapt.

**And the principle that governs the run sheet itself: follow energy, not the
agenda.** If the room discovers something important, stay with it. The run sheet
exists to protect the outcome, not the clock. Fifteen minutes spent on a live
breakthrough is worth more than three parts delivered on time, and the timings in
`02-run-of-show.md` are built with enough slack to absorb one such detour. Spend it
deliberately, once.

Applied to a room with no software in it: the thing you build is the whiteboard, and
you build it out of their sentences. When you write their words on the wall in their
vocabulary and the map turns out to explain something they had not articulated, that
is the demonstration. There is no other demo in this session.

## Credibility, stated rather than implied

The earlier version of this brief assumed credibility should be demonstrated through
the quality of the questions and never asserted. That is half right. The questions do
the deep work — but people decide in the first few minutes whether to spend attention
on you at all, and they decide it on whether you have sat where they sit. If you do
not tell them, the practice leads have no reason to believe the CAD question is
coming from someone who has managed CAD.

Say it plainly in Part 1, as a list of seats rather than a claim of expertise:

- owned an engineering practice
- worked as a designer
- worked as a CAD manager
- deployed AI inside the civil division of an ENR Top 200 firm
- came up through development and IT, governance included

That combination is the actual differentiator — not any one of them. Plenty of people
in this market know AI. Very few know AI *and* what a Tuesday looks like in a civil
practice, which is precisely the gap the demo they already saw left open.

The five seats also map onto the four lanes, which is why the room holds together:
you can answer each lane from having been in it.

## Tone

Curious. Collaborative. Low ego. High expertise.

**Positive framing, without exception.** This is the single most repeated note from
the review, and it applies everywhere:

| Do not say | Say |
| --- | --- |
| "I didn't bring a demo, there's no software here" | "What separates a deployment that works from one that fails?" |
| "I owe you a straight answer" | "Okay — here we are. Let me answer the questions you've been asking." |
| "Bear with me, this part isn't for you" | "This one is aimed at IT — stay with it, because it decides whether the drafting side gets what we just described." |
| "Here's what went wrong when we tested ourselves" | "Here's the category of problem nobody is positioned to see — and how it becomes visible." |
| "Who here has used an unsanctioned tool?" | "Have you had anyone using something that wasn't sanctioned, and it just worked?" |

Framing sets what the room listens through. A negative opener does not read as
humility, it reads as deficit, and every subsequent statement is heard inside it. The
goal is that people leave proud of their own organization and clear on their own
upside — not impressed by your candor about your own limitations.

Banned, out loud, no exceptions: *AI revolution*, *game changing*, *next generation*,
*transformative*, *unlock*, *leverage* as a verb, *journey*.

Default move when you do not know: "Let's explore." Second default: "I don't know
yet — what would we have to measure to find out?" That sentence is the entire
posture, and it is also the thing that separates you from every other vendor who has
been in that room this year.

## Emotional arc

Curiosity → recognition → participation → discovery → ownership → excitement →
invitation.

Recognition is the load-bearing step and it happens in Part 2. It is the moment
someone says *that is exactly what happens here* about a pattern you drew from their
own answers. If recognition does not land by T+44, the rest of the arc will not
carry, and `06-failure-modes.md` tells you what to do about it.

## What success looks like

Not applause. Applause is what a demo gets.

- Multiple attendees keep talking after the scheduled end.
- Practice leaders volunteer specific workflows, unprompted.
- IT asks how it would be governed and integrated, rather than whether it should be.
- An executive shifts vocabulary from *tool* to *capability*.
- A pilot candidate emerges from the room rather than from you.
- Someone says a version of: *this is different from the AI conversations we have
  been having.*
- **Every individual leaves knowing what they personally get out of it.** Not the
  firm — them. This is what the close's second move exists for, and it is the
  difference between a room that agrees and a room that advocates.

The last two are the real metrics. Log the quote verbatim, with attribution, if it
happens.

## What the room should be asking at the end

Not "can we buy this?"

"What would this look like inside SW+?"

The close in `02-run-of-show.md` is built to make that the natural next sentence, and
to have an answer ready that is neither a price nor a promise.

---

## What this session actually is

Worth holding in mind while facilitating, and worth never saying out loud.

This is not a discovery session with a whiteboard exercise in it. It is an experiment
in organizational self-observation, and the whiteboard is its output.

By the close, the room will have collectively witnessed and externalized knowledge
that existed only inside individual heads — where work really begins, which two
people the firm silently depends on, where the record of *why* stops existing. Nobody
had written that down before, and no software produced it. The room did, in one
afternoon, because it was asked the right questions in the right order.

That board is the first artifact. It demonstrates the underlying philosophy before
anyone sees a line of code, and it is a far stronger introduction than any demo,
because they cannot dismiss it as a vendor's claim — they made it.

Which is also why the map goes back to them within 48 hours, in their words, with the
disagreements left in. It is the proof that the session was what you said it was.
