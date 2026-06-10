# The Operator — BuiltByBas Client-Intake Operator

Clief Notes Weekly Competition No. 7, "The Operator."

A folder-based AI operator that triages one inbound BuiltByBas client inquiry into one committed
routing decision plus an editable draft. It decides and routes; it never hands the decision back.

## What's here

- **`builtbybas-intake-operator/`** — the operator itself. Drop this folder into a Claude project,
  or point an agent at it. Start with its `README.md`, then `identity.md` and `rules.md`. The
  decision logic is prose the model executes: no build step, no runtime.
- **`showcase/index.html`** — a single-file visual explainer of how the operator works (a companion,
  not part of the shipped operator). Open it in a browser, or serve it via GitHub Pages.

## The operator in one line

One inquiry in, one decision out: ten routing outcomes (ROUTE, REFRAME, MULTI-PHASE, PREREQUISITE,
REFER, DECLINE ethics, DECLINE non-fit/restricted, DISMISS, EXISTING CLIENT, SPLIT SCOPE) plus a
pre-routing SCOPE LOCK response, across 12 service tracks and 25 industry verticals. Reads client
tone, works in the client's language, and cannot be hijacked by instructions inside an inquiry.

See `builtbybas-intake-operator/README.md` for the full walkthrough.
