# BuiltByBas Client-Intake Operator

An AI operator that triages inbound BuiltByBas client inquiries. You paste in a raw message
from someone who wants to work with BuiltByBas, and the operator reads it, figures out what the
person actually needs (not just what they asked for), commits to a routing decision, and hands
back that decision plus a ready-to-send draft. It decides and routes. It never asks you what to do.

## How to use it

Pick your environment, activate the operator, then paste a client inquiry as your message. The
operator returns one Routing Decision and an editable draft. No babysitting.

- Claude Code: open THIS folder as your workspace (the folder that holds CLAUDE.md). Claude Code
  auto-loads CLAUDE.md and becomes the operator. Note: if this folder is a subfolder of a larger
  repo, open the subfolder itself, a nested CLAUDE.md does not auto-load from a parent repo.
- Cursor, Windsurf, Codex, Gemini CLI: open this folder; they auto-load AGENTS.md.
- claude.ai Projects: create a Project, then copy the contents of PROJECT-INSTRUCTIONS.md into
  the Project's "Set project instructions" field. Uploaded files alone do NOT auto-activate a
  persona on claude.ai, the instructions field is what drives behavior. Upload the operator
  files to the Project knowledge for full detail.
- Any chat, no setup: paste "Act as the operator defined in these files," attach the folder, then
  paste the inquiry.

Then paste an inquiry and the operator decides and routes.

## What you get back

Every inquiry produces the same shape, so you can read the call in seconds and trust it:

```text
DECISION:       the committed outcome
ASKED FOR:      the surface request, their words
ACTUALLY NEEDS: the real underlying need (the reframe shows here)
ROUTE:          one track + path
SIGNALS:        complexity | urgency | scope-creep flag
CONFIDENCE:     High / Medium / Low (+ caveat)
WHY:            the reasoning that produced the call
NEXT ACTION:    what happens now
---
DRAFT:          a ready, editable message to send
```

## The ten outcomes

The operator commits to exactly one:

1. ROUTE, a clean fit to one of the 12 service tracks.
2. REFRAME, the real need differs from the stated request.
3. MULTI-PHASE, stated simple, actually multi-stage.
4. PREREQUISITE, too thin to route, names the exact missing facts (still a decision).
5. REFER, marketing work, warm handoff to Marketing partner.
6. DECLINE (ethics), fails the values screen.
7. DECLINE (non-fit), legitimate but outside scope, with an alternative.
8. DISMISS, not a real lead (spam, solicitation, recruiter, bot), protect the time.
9. EXISTING CLIENT, a returning client's change request, routed straight to Bas.
10. SPLIT SCOPE, one inquiry with a real build AND real marketing run for them, routes the build to Bas and refers the marketing to Marketing partner in a single decision.

## Try it (three sample inputs included)

Paste any file from `samples/` and judge the operator's call yourself. These are prompts only; the
expected outcomes are held by the author, outside this folder, so the operator decides blind.

- `01-fitness-studio.txt` (a new studio that wants its first website)
- `02-landscaping-app.txt` (a crew-scheduling "app" request)
- `03-candle-ads.txt` (an existing store that wants more sales)

For deeper worked decisions including the edge cases, see `examples.md`.

## What's inside

```text
identity.md     who the operator is, its one workflow, its one rule, the output contract
rules.md        the decision logic: the ordered procedure, criteria, edge cases
examples.md     ten worked decisions spanning the outcomes
reference/             the operator's knowledge library (loaded on demand)
  INDEX.md             the librarian: what's here and when to load each entry
  service-catalog.md   the 12 service tracks plus decline and referral, with boundaries
  routing-map.md       the ten outcomes and where each one goes
  decision-rubric.md   how complexity, fit, and risk are scored
  industry-profiles.md per-vertical business, data, compliance, and reframe tells
  regulations.md       each regulation: what it is, who it hits, what to flag
test-inputs/    three sample inquiries to paste in
README.md       this file
```

## Adapt it

The decision logic is generic; the business specifics live in `reference/`. To point this at a
different service mix or routing, edit `service-catalog.md` and `routing-map.md`. The operator
reads whatever is there.

## Scope

Built for text input: you paste an inquiry, you get a decision and a draft. Wiring it to a live
website form is a deliberate next step, kept out of scope so the decision-making is the focus.
