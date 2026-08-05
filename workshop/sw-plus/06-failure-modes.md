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
honest version — the self-audit story from Part 5 — and then hard-pivot back:
*"That is what it found in our own house. What I do not know is what it would find in
yours, and that is what the next hour is for."*

---

## 2. Recognition has not landed by T+40

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

**If it still has not landed by T+55,** abandon the abstraction entirely for the rest
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

**Recovery — agree completely, then differentiate by evidence rather than claim:**

> "You should be tired of it. Most of what has been in front of you was a confident
> claim with nothing behind it.
>
> So here is the only thing I will assert today: we ran a test on our own product
> that we expected to pass, and it failed. It is written down as a null result and it
> is still published, next to the ones that worked. I would rather show you that than
> a capability slide.
>
> What would you need to see to believe a claim like this at all?"

The last question is the actual move. It converts a skeptic into a specification
author, and whatever they answer is a requirement you can meet or honestly decline.

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

## Two things to remember when it is going badly

**Silence is not failure.** Five seconds after a question feels like thirty from the
front of a room. The honest answer lives on the other side of it. Count.

**The map is the deliverable, regardless.** Even in a session that never reaches the
reveal, if you leave with their lifecycle in their words, with the red marks and the
gold circles on it, you have something no other vendor in that room has ever
produced. Send it. It will restart the conversation on its own.
