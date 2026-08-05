# 02 — Run of show

150 minutes, clock-anchored from T+00 at the first word, not from the calendar
invite. Write the actual start time in the margin when you begin.

| | | |
| --- | --- | --- |
| T+00 | **Part 1 — Why we are here** | 12 |
| T+12 | **Part 2 — The engineering organization** (whiteboard) | 30 |
| T+42 | **Part 3 — Current AI reality** | 18 |
| T+60 | **Break** — instrumented, not downtime | 8 |
| T+68 | **Part 4 — Live thought experiment** | 37 |
| T+105 | **Part 5 — Build together, then the reveal** | 32 |
| T+137 | **Close — what would this look like inside SW+** | 13 |

Two checkpoints. **T+40: has recognition landed?** — has at least one person said a
version of *that is exactly what happens here*. **T+105: do you have two circles on
the board?** If either is no, go to `06-failure-modes.md` before continuing.

Bring: three marker colors (black, red, gold or green), a phone for photographing the
board, and one printed copy of `04-capture.md`. If someone else is taking notes, hand
them the printed copy and the tag list before the session, not during it.

---

## Part 1 — Why are we here (T+00, 12 min)

The first ninety seconds set whether this is a vendor meeting or something else.
Nothing about Echology, nothing about AI, no credentials.

**Opening, roughly:**

> "I want to be clear about what this is, because it will save us all two hours.
>
> I did not bring a demo. There is no software in this room today.
>
> What I do is study how engineering organizations actually work — where work really
> begins, where knowledge disappears, what makes a senior engineer different from a
> capable one with six years less. I have opinions about that. I would rather have
> yours, because mine are not about SW+.
>
> So: I am going to ask a lot of questions. Some of them will have obvious answers
> and I will ask anyway, because the obvious answer is usually where two of you find
> out you have been doing it differently for years.
>
> If at the end of this you have learned something about your own organization that
> you did not know this morning, this was worth your time regardless of whether we
> ever work together."

Then the frame, out loud, because the room needs permission to be honest:

- No judgment, and nothing said here is a commitment.
- Disagreement is the most useful thing that can happen. If two of you disagree about
  how something works, that is the finding.
- If I ask something naive, correct me. I do not know your business; you do.

**Then go around the room.** Not titles — everybody knows the titles. Ask each
person: *"What is one thing that, if it worked better, would change your week?"*

Write every answer on the board verbatim. Do not paraphrase. Do not group them yet.
Leave them up all session; you will come back to them at T+137, and the fact that
they are still there, in their words, is most of the close.

**Do not:** describe Echology, mention the champion or the $15k, or explain why AI
matters.

---

## Part 2 — The engineering organization (T+12, 30 min)

The instrument is the board and it is drawn in three passes. This is the only build
in the session and it is entirely made of their sentences.

### Pass one, black — the lifecycle (about 14 min)

**"Where does work actually begin?"**

The first answer will be a contract, a notice to proceed, or a project number. Push
back once, gently: *"That is where it becomes billable. Where does it actually
begin?"* The real answer is earlier — a call, a relationship, a pursuit, a
conversation about a parcel two years ago. Where they place the true origin tells you
what they think they are in the business of.

Build left to right from there, in their words, using their internal names for the
phases. If they call it something specific, write that. Their vocabulary is the
interface for anything you build later; the moment you translate it into your own
words you have started designing a generic product.

Keep it to eight or ten boxes. This is a map, not a process document.

Then, still in black, place people on it: who touches each phase, and where handoffs
occur. Handoffs are where the rest of the session lives.

### Pass two, red — where it breaks (about 10 min)

Same drawing, second color, three marks. Hand markers to other people for this pass.
The moment an attendee is holding a marker, the map becomes theirs.

- **X** — where knowledge disappears. *"Where does something get known and then
  stop being known?"*
- **Clock** — where delays originate. Press on this: the place delay is *felt* is
  almost never the place it *originates*. Ask both, mark both, connect them with a
  line. That line is often the most valuable object on the board.
- **Diamond** — where decisions are actually made. Then the follow-up that matters:
  *"And where is the record of why?"* If the honest answer is an email, someone's
  memory, or a markup that got superseded, mark it. Say nothing about it yet.

### Pass three, gold — the senior-engineer circles (about 6 min)

Two questions, then two circles.

**"What makes your senior engineers different? Not experience — what do they do
differently on a Tuesday?"**

**"If you cloned your best engineer, what exactly would you be duplicating?"**

The answers cluster: they know what will fail before it fails, they know who to ask,
they remember the last time this went wrong, they know which standard is real and
which is aspirational, they catch the thing on page four.

Circle in gold the two places on the map where a senior person is the only reason it
works. Only two. The constraint forces prioritization and the argument about which
two is itself the finding.

**Those circles are the pilot candidates.** Everything from here builds toward them,
and because the room drew them, the pilot arrives already owned.

**Photograph the board before erasing anything. Every pass. Three photos minimum.**

### Lane check

Executive gets the shape of the firm and the delay chain. IT gets the systems and
handoff boundaries. Practice gets its daily friction on a wall, in its own words,
with leadership in the room reading it. That last one is worth more to the practice
leads than anything you could say.

---

## Part 3 — Current AI reality (T+42, 18 min)

**"What are people actually using today? Not what is approved — what is actually
happening."**

The framing has to make honesty costless, and it must be said with leadership sitting
right there:

> "I am not asking to catch anyone. Every firm I talk to has people quietly using
> whatever works, and the ones that pretend otherwise are the ones with the real
> exposure. What is actually in use?"

Expect: Claude, ChatGPT, Copilot, Civil3D add-ins, LISP routines, Python scripts,
Excel doing things Excel should not do, personal workflows nobody has documented.

Ask Landen his question here: *"What have you already automated that nobody asked you
to?"*

Then York: *"What have you written in LISP or C# that you wish you had not had to
write?"*

Then the one nobody expects, and it is the most valuable question in this part:

**"What did you try that did not work?"**

Failed AI attempts tell you the shape of the real problem better than successes do,
and asking for failure signals that failure is reportable here. That is a small
governance argument made by demonstration rather than assertion.

Capture per item: who uses it, whether IT knows, whether it touches project data,
whether it survives its author leaving. Do not editorialize about shadow IT. Robert
and David are already doing that arithmetic and they do not need help.

**Do not** evaluate any tool they name. Not one. The moment you rank their tools you
become a vendor.

---

## Break (T+60, 8 min)

Say: *"Eight minutes. I will be right here."* Then stay at the board and do not look
at your phone.

People will come to you. What they say standing at a whiteboard with no executive
listening is different from what they said sitting down, and it is usually the
truest thing you hear all day. Write it down the second they walk away —
`04-capture.md` has a break slot.

Watch who talks to whom. The clustering tells you where influence actually sits.

---

## Part 4 — Live thought experiment (T+68, 37 min)

Still nothing about Echology. This is the hardest discipline in the session and it
is the whole reason the reveal works.

**Frame:** *"Forget constraints for twenty minutes. Not budget, not software, not
whether it exists. I want to know what changes."*

Four questions. Roughly eight minutes each. Ask, then wait. The silence after each
one is where the answers come from — do not fill it.

1. **If every engineer had perfect memory of every project this firm has ever done —
   what changes?**
2. **If every decision on a project could explain itself — who decided, when, on what
   evidence — what changes?**
3. **If every lesson learned persisted forever, past the person who learned it — what
   changes?**
4. **If every project taught every future project — what changes?**

Write every answer on the board, verbatim, and cluster them as you go. The clusters
will assemble themselves into observation, knowledge, relationships, context, and
institutional memory without you naming any of those words. That is the point.

If the room stalls, restate as loss rather than gain: *"Put it the other way — what
does it cost you today that this is not true?"* Loss is more articulable than gain,
every time.

If Christopher answers first, good. Let him. He gives the rest permission.

**Listen hard for alignment moments** — an attendee describing, in their own words,
something that already exists. Mark it `[ALIGN]` with the exact quote and who said
it. These are the load-bearing sentences of the follow-up, and they are quoted back
attributed, never paraphrased into your vocabulary.

**The trap in Part 4:** someone will ask *"does this exist?"* Do not answer yet.

> "Hold that. Ask me again in twenty minutes and I will give you a straight answer —
> including the parts that do not work yet."

That is a promise. Keep it in Part 5, including the second half.

---

## Part 5 — Build together, then the reveal (T+105, 32 min)

### Assemble (about 18 min)

Now move from the wish list to the architecture, using only what is on the board.

> "Look at what you just described. If you had to build that — not the software, the
> capability — what does it need?"

Let them assemble it. Guide only by asking what is missing. They will produce, in
some order and in their own words:

- something that observes what actually happens, rather than what is reported
- a record that survives the person
- relationships between things, not just the things
- context that travels with the work
- some way to know a conclusion is trustworthy
- a person who decides, at the end

If they miss the last one, ask directly: *"Who decides?"* The answer will be *a
person, always* — and it is much stronger arriving from them.

### The reveal (about 6 min)

Understated. One sentence, no transition, no build-up.

> "So — I owe someone a straight answer. What you have drawn is essentially the
> architecture we have been building for the last year."

Then, immediately, before anyone can ask what it costs, the second half of the
promise. Lead with a failure. This is the credibility move and it is aimed at Robert
and David specifically:

> "The first thing we did with it was point it at ourselves. Nine-month-old codebase,
> one person, who wrote nearly all of it. It found that about a quarter of the files
> should not have existed — duplicates, stale copies, archives still in the working
> tree. Nobody could see it from inside, including the person who wrote it.
>
> And we have run tests it failed. We had a claim that a certain measurement could
> predict what a system would do next. It did not survive its own test. It is written
> down as null and it is still on the site, next to the ones that worked."

Then stop. Say nothing else about the product.

If they push for more, the honest frame:

> "It perceives, and a person decides. It is a lens, not an oracle. Anything it
> concludes, you can trace back to what it observed — and if you cannot trace it, you
> should not act on it."

**Governance:** only if raised. One line, then stop — see Robert's card in
`01-room.md`.

**Automation:** if raised, go to their ground. Plugins, Civil3D, Python, APIs,
existing investment. The correct posture is extension of what York and Landen already
built, not replacement.

**Executives:** if the VP asks anything, answer in decision quality, risk reduction,
organizational capability, speed of learning, knowledge retention, operational
visibility. Not technology. Not once.

### Never say

*This is our product.* *This is what we sell.* Any price. Any timeline you cannot
defend. Any number you cannot source in the room.

---

## Close — what would this look like inside SW+ (T+137, 13 min)

Return to the two gold circles and the verbatim answers from Part 1, both still on
the board.

> "Two hours ago I asked what would change your week. Those are still up there. And
> in the middle you circled two places where the whole thing works because one person
> is standing there.
>
> I am not going to guess at what to build. Here is what I would want to look at to
> answer that honestly — and here is the part I think matters more."

**Then propose the discipline, not the deal.** This is the differentiating move and
it should be the last substantive thing said:

> "If we do something together, I would want to write down what would make it a
> failure before it starts. What we are measuring, what result would mean it did not
> work, and who judges. In writing, before the first run.
>
> Because otherwise, in eight weeks, we will find a way to call whatever happened a
> success. Everybody does. It is much harder to do that when the criteria were set
> before anyone knew the answer."

That is a sentence nobody else has said in that room this year. Robert will
recognize what it is. David will recognize what it protects him from. The VP will
recognize a way to spend money without buying a story.

**Then the ask, and it is small:**

- who to talk to for one hour each about the two circled workflows
- what would need to be true for a narrow pilot to be allowed to touch real project
  data — asked to IT directly, in the room
- one workflow someone volunteers

**Last thing you say, before logistics:**

> "I will send you the map you drew today, in your words, not mine. If I got anything
> wrong, tell me — because if the map is wrong the rest of it will be too."

Then stop talking and let the room fill the space. If the arc worked, someone asks
what this would look like inside SW+, and you have already answered it without
quoting a price.

---

## Immediately after

Before leaving the parking lot, five minutes, in `04-capture.md`:

- the sentence you would not have predicted
- who surprised you
- who did not speak, and whether that was evaluation or absence
- the two circles, exactly as worded on the board
- anyone who said a version of *this is different from the AI conversations we have
  been having* — verbatim, with attribution

Then `05-synthesis.md`, same day. Memory of a room decays faster than anyone
believes, and the specific words are the entire asset.
