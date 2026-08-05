# 06 — Failure modes

Six ways this room goes wrong, and the recovery line for each. Read once tonight so
you recognize them without looking.

---

## 1. The room wants a demo

**Symptom:** within the first twenty minutes, someone asks to see it. Then someone
else. The questions turn into feature questions before the map is drawn.

**Why it happens:** it is the format they expect, and answering it is the path of
least resistance for everyone including you.

**Recovery:**

> "I will show you something at the end, and it will be more useful to you if I
> understand how you work first. Otherwise I would just be showing you a demo built
> for somebody else's firm — and you have seen those."

Then a question, immediately, so the silence does not become an invitation to press.

**If it happens a third time,** the room has decided. Give them ninety seconds of the
operational-legibility version from Part 5 — the things you do not know you do not
know, surfaced on your own operation — then hard-pivot back: *"That is what it made
visible in our own house. What I do not know is what it would make visible in yours,
and that is what the next hour is for."*

---

## 2. Recognition has not landed by T+44

**Symptom:** the map is on the board, but nobody has said a version of *that is
exactly what happens here*. Answers are polite and general. Nobody has picked up a
marker.

**Why it happens:** you are drawing their process instead of their reality. A process
map produces agreement; a reality map produces recognition, and the difference is
usually one degree of specificity.

**Recovery — get specific and get personal:**

> "Let me try a harder version. Christopher — the last time a drawing got to QC with
> something on it that should have been caught two weeks earlier. What happened?"

Named person, specific incident, recent. General questions produce general answers
all day. One concrete story reframes the whole board, and the rest of the room will
start supplying their own.

**If it still has not landed by T+58,** abandon the abstraction entirely for the rest
of the session and run on incidents only. Every question becomes *tell me about the
last time*. It is a less elegant session and a more useful one.

---

## 3. One voice dominates

**Symptom:** the VP or one practice lead answers everything. Others defer. You are
getting one perspective at high volume.

**Why it matters:** the deferring people have the daily reality, and you will leave
with an executive summary of a firm rather than a map of one.

**Recovery — structural, not confrontational.** Change the unit of response:

> "I want to try something. Same question, but everyone writes one line first, then
> we go around. Thirty seconds."

Written-first is the reliable de-dominator and it costs almost nothing. Alternatively
route by name: *"Jacob, from Charlotte — is that how it works there too?"* — which
also surfaces office divergence.

**If the dominant voice is the VP,** do not shut it down. Convert it: *"That is the
view from where you sit — I want to check it against where they sit. Same question,
practice side."* He will usually be interested in the answer, and the comparison is
more useful than either answer alone.

---

## 4. The rabbit hole

**Symptom:** Landen asks about MCP, or Robert asks about model architecture, or York
asks about the plugin API, and forty-five minutes of the session are now at risk.

**Why it matters:** it is a genuinely good conversation and it will lose the other
nine people in the room, including the one who signs.

**Recovery — answer in two sentences, then park it visibly and by name:**

> "Short answer: [two sentences]. Longer answer is worth its own conversation and I
> would rather have it with you directly — can I get thirty minutes with you next
> week? I am writing your name down so I do not forget."

Then write the name on the board. The visible parking is the mechanism: it converts
being cut off into being prioritized, and it produces the follow-up conversation you
wanted anyway.

**Two-sentence answers to have ready:**

- **MCP / integration:** "It is a standard way for a system to expose its tools and
  data to a model without hardcoding either side. The reason it matters to you is
  that it makes what you already own extensible rather than replaceable."
- **Which model:** "Whichever one is best at the specific task, and it changes; the
  architecture assumes it will change. What does not change is that a deterministic
  layer decides what the model is even allowed to look at."
- **Hallucination:** "The model only gets to narrate what a non-model layer already
  found. If it cannot be traced to something observed, it does not ship as a
  conclusion."
- **Where does data go:** "That is a real question and I do not want to hand-wave it
  — it is exactly the kind of thing we would write down before a pilot, not after."

---

## 5. The AI-fatigue objection

**Symptom:** someone — often the most senior technical person — says a version of
*we have heard a lot of this*, or *everybody says that*. The temperature drops.

**Why it matters:** it is correct, they have, and any defensive response confirms
their read. It is also the best opportunity in the session if handled right.

**This is the designated home for the null-result material.** It is deliberately not
in the main line of Part 5 — leading with a failure spends your best evidence on a
room that has not yet asked the question it answers, and it frames you negatively at
the moment you should be handing them something. Held until someone challenges you,
the same fact is the strongest thing you say all afternoon.

**Recovery — agree completely, then differentiate by evidence rather than claim:**

> "You should be tired of it. Most of what has been in front of you was a confident
> claim with nothing behind it.
>
> So here is the only thing I will assert today: we ran a test on our own product
> that we expected to pass, and it failed. It is written down as a null result and it
> is still published, next to the results that worked. I would rather show you that
> than a capability slide.
>
> What would you need to see to believe a claim like this at all?"

The last question is the actual move. It converts a skeptic into a specification
author, and whatever they answer is a requirement you can meet or honestly decline.

If the skeptic is Robert, this is also where his question belongs: *what evidence
would convince you we were not fooling ourselves?* Same move, his framing.

**Do not:** list differentiators, name competitors, or say *we are different*. Saying
you are different is what everybody says.

---

## 6. Someone asks what it costs

**Symptom:** at any point, usually from the executive lane, usually earlier than you
want.

**Why it matters:** answering converts the session into a procurement conversation
and the remaining time will be spent on scope rather than discovery. Refusing to
answer looks evasive.

**Recovery — answer the shape, not the number:**

> "I do not know yet, honestly, because I do not know what we would be building. What
> I can tell you is the shape: the first thing is small, scoped to one workflow, and
> designed so that if it does not work we both know within weeks rather than
> quarters. I would rather size it after today than guess in front of you."

If pressed a second time, that is a real buying signal, not an obstacle:

> "Give me the two conversations I asked for and I will come back with a number and
> what it buys. I do not want to price something I would have to re-price after I
> understand it."

**Never** quote a figure in the room. Never reference the $15k, and never reference
the champion's argument — repeating an internal advocate's reasoning back to the room
spends their capital for them, in public, without asking.

---

---

## 7. You are twenty minutes behind because something real happened

**Symptom:** the room got into something at a 5 on the gauge — an argument about how
a handoff actually works, a story that pulled four people in — and it ran long. You
are now behind and the reflex is to compress your way back onto the clock.

**Why the reflex is wrong:** you came for exactly this. A high-energy divergence is
the session working, and cutting it to protect a schedule tells the room that the
agenda mattered more than what they were saying. They will not offer you the next
one.

**Recovery — pay for it deliberately, from the right place:**

| Take it from | How much | Cost |
| --- | --- | --- |
| Part 4, one question | up to 12 min | Low. Four questions is generous; three works. |
| Part 5 assemble | up to 6 min | Low if the board is already rich. |
| Part 3 | up to 8 min | Medium — you lose shadow-tooling detail. |
| The break | 0 | Do not. It is instrumentation, and people will take it anyway. |
| The close | 0 | Never. It is the only part that produces the next meeting. |

Say nothing about being behind. Announcing it makes the room feel responsible for the
best twenty minutes of the afternoon.

**The rule:** follow energy, not the agenda. The sheet protects the outcome, not the
clock. Spend one deliberate detour — and if a second one appears, name it out loud as
a follow-up conversation rather than taking it, because two detours is no longer a
session with a shape.

## Two things to remember when it is going badly

**Silence is not failure.** Five seconds after a question feels like thirty from the
front of a room. The honest answer lives on the other side of it. Count.

**The map is the deliverable, regardless.** Even in a session that never reaches the
reveal, if you leave with their lifecycle in their words, with the red marks and the
gold circles on it, you have something no other vendor in that room has ever
produced. Send it. It will restart the conversation on its own.
