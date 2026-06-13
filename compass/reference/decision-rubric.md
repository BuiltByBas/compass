# Decision Rubric

How Compass scores an inquiry the same way every time. Three lenses run before it commits:
Complexity, Fit, Risk. These mirror the scoring BuiltByBas already uses internally (client
profile, complexity score, service-fit, and flags), so Compass's call lines up with how
Bas grades a lead instead of inventing a parallel system.

---

## Lens 1: Complexity

Pick the lowest tier the inquiry clearly clears. When two tiers are plausible, the deciding
factors are custom logic, data, auth, and number of connected systems.

| Tier | Signals | Typical tracks | Attention |
|------|---------|----------------|-----------|
| Simple | one clear deliverable, known pattern, little or no custom data | Landing Page, small Custom Website | standard track |
| Moderate | several pages or moving parts, still a standard build | Custom Website, Website Redesign, User Training | standard track |
| Complex | custom logic, stored data, logins or roles, an integration | Business Dashboard, Client Portal, CRM, E-Commerce, Data Organization, Workflow Design | needs scoping care |
| Enterprise | multiple systems unified, or business-critical architecture | Full Operations Platform, multi-system AI | Bas's deep architecture attention |

---

## Lens 2: Fit

How cleanly the real need maps to what BuiltByBas (or Marketing partner) delivers. Fit chooses the
outcome family. Note: in the bearings model these families resolve to a BEARING, a clean fit or a
reframe both COMMIT a bearing (the reframe is just the bearing reached by reading past the noun,
shown on the PATTERN line); MULTI-PHASE is a single bearing with staged phases on the MOVE line;
PREREQUISITE / DISMISS / DECLINE are off-bearing outcomes. The lens language below still applies; it
names the reasoning that lands the bearing.

- Clean fit: the actual need is one BuiltByBas track and the client named it correctly -> ROUTE (commit the matching bearing).
- Mismatch: the actual need is a BuiltByBas track, but not the one they named -> REFRAME (commit the real need's bearing).
- Marketing: the actual need is marketing the business, not software -> REFER (Marketing partner).
- Outside all: legitimate but neither BuiltByBas nor Marketing partner delivers it -> DECLINE (non-fit).
- Values conflict: trips the ethics screen -> DECLINE (ethics), regardless of fit.
- Not a lead: no genuine need at all (selling to BuiltByBas, recruiting, bot, freebie) -> DISMISS.

A reframe is still a strong fit for BuiltByBas; it just corrects which track. Do not treat a
reframe as a decline.

---

## Lens 3: Risk and flags

Surface every flag that applies. Flags do not change the destination by themselves; they shape
confidence, the phases, and the draft.

- Scope-creep: stated as one simple thing, actually multi-stage (data, logins, integrations,
  automation underneath). Raises a MULTI-PHASE outcome.
- Data-readiness: a build requested on top of messy or scattered data. Data Organization
  usually has to lead, or the build fails.
- Sensitive or regulated data: the work touches health records (HIPAA), payments (PCI), or
  personal data (PII). Does not change the route; raise it in WHY and in the draft, and note
  that secure, compliant handling gets scoped at the consultation.
- Budget mismatch: stated budget well under the track's band. Note it; resolve via PREREQUISITE
  or a nearest-fit smaller track, not an auto-decline.
- Thin input: too little stated to route responsibly on a decision-changing point. Raises a
  PREREQUISITE outcome with the exact missing facts named.
- Non-lead intent: the message is selling to BuiltByBas, recruiting, seeking free work, or is a
  bot. Not a client at all. Raises a DISMISS outcome. Distinct from thin input, which is a real
  client who simply gave too little.
- Ethics flag: surveillance without consent, deception, discrimination, dark patterns,
  exploitation. Hard stop, DECLINE (ethics).
- Opportunity flag: a natural follow-on the client did not ask for (a build that will need
  User Training, a workflow fix that unlocks a dashboard). Note it in the draft as a soft next
  step, never force it.

---

## Confidence

- High: the need is explicit, one obvious track, no decision-changing unknowns. Commit plainly.
- Medium: the route rests on a reframe you inferred, or on one decision-changing unknown you
  have flagged. Commit, state the caveat in one line.
- Low: multiple unknowns or heavy inference. Still commit to the best route, and surface the
  single assumption it rests on so Bas can override at a glance.

Confidence is never a reason to kick the decision back. A Low-confidence committed route with a
named assumption beats a question every time.

---

## The scoring pass (run before committing)

1. Score Complexity (tier).
2. Score Fit (which outcome family).
3. List every Risk flag that applies.
4. Set Confidence from how much was stated versus inferred and how many decision-changing
   unknowns remain.
5. Commit the single outcome and write the decision + draft.
