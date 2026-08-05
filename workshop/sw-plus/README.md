# SW+ AI Discovery Workshop — working set

SeamonWhiteside (SW+). 2.5 hours, in person. Discovery session, not a demo.

This directory is the working context for planning, live capture, and post-meeting
synthesis. Read `00-brief.md` first if you have five minutes. Read `02-run-of-show.md`
if you have one.

| File | When you use it |
| --- | --- |
| `00-brief.md` | Tonight. The objective, the constraint, the three conversations in the room. |
| `01-room.md` | Tonight. Who is there, what each of them is actually measuring, the first question you ask each by name. |
| `02-run-of-show.md` | In the room. Clock-anchored, with the whiteboard choreography and the exact lines for the three hard moments. |
| `03-question-bank.md` | In the room, when a lane goes quiet. Questions with follow-up ladders. |
| `04-capture.md` | In the room. Blank, tagged, ready to fill. Copy to `04-capture-FILLED.md` before the session. |
| `05-synthesis.md` | Within 24 hours after. Turns capture into a proposed pilot in their words. |
| `06-failure-modes.md` | In the room, when it goes sideways. Seven ways this room goes wrong and the recovery line for each. |

Three things govern all of it, and they are worth carrying in even if you read
nothing else. **Follow energy, not the agenda** — the sheet protects the outcome, not
the clock. **Never say the section names out loud** — the room should experience one
continuous conversation that changes altitude four times, not a five-part agenda.
**Score every topic 0–5 for energy as it happens** — the pilot comes from the
highest-energy topic, not necessarily the biggest problem.

## One structural note before anything else

The five parts in the brief sum to exactly 150 minutes. A 2.5-hour in-person session
does not have 150 minutes of session in it. There is arrival, there is a break people
will take whether you schedule it or not, and there is a close. Run the brief's
timings as written and you lose the close — which is the only part that produces the
next meeting.

`02-run-of-show.md` fits the same arc into the real 150 with a scheduled break at
T+60 and a 13-minute close. Nothing in the arc is cut. Part 4 and Part 5 each give up
about eight minutes, which they can afford because by then the room is doing the
talking.

The break is not downtime. It is the highest-yield twelve minutes of instrumentation
in the session: who walks up to you, and what they say when leadership is not in the
conversation. Capture it. `04-capture.md` has a slot for it.

## Handling

This directory names real people at a real client and records a read on internal
political dynamics. The repository root is a published site (`echology.dev`, GitHub
Pages, `.nojekyll`). Anything merged to `main` is served publicly, including `.md`
files at their path.

**Do not merge this branch into `main`.** It lives on
`claude/sw-plus-discovery-workshop-59cfo3` and should stay there, or move to a private
repo. Nothing in here is written for an external reader.

## Using Claude during and after

**During** — keep a session open on this directory. Useful in-flight asks:

- "Landen just asked about MCP. Give me the two-sentence answer that does not open a
  rabbit hole." → see the rabbit-hole guard in `06-failure-modes.md`
- "They keep saying *[phrase]*. Is that the third time? What have they attached to it?"
- "York described something in Part 4. Does it match anything we actually built?"

**Immediately after, same day, before the memory decays** — paste the filled capture
in and ask for:

1. Theme extraction across all three lanes, with counts. Repeated is signal; said
   once by the VP is also signal. Both, labeled differently.
2. The vocabulary ledger, ranked by frequency. Their words are the pilot's interface.
3. Alignment moments — where an attendee described a capability that already exists,
   unprompted. These are quoted verbatim in the follow-up, attributed to them.
4. Two or three candidate pilots, scored against the feasibility fields in
   `05-synthesis.md`.

The discipline that makes the follow-up land is the one on the field-notes page:
write down what would make the pilot a failure *before* it runs. See the close in
`02-run-of-show.md`.
