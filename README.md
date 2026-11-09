# Proof-First Skills

Six skills for people who work with AI agents, built on one rule:

**An agent may only report what it can prove, and must name what it
could not.**

Every skill in this pack exists because the failure happened first.
None of these rules were invented at a desk; each one was paid for
by a real miss, then written down so it could not happen the same
way twice.

## The pack

| Skill | What it stops |
|---|---|
| booking-proof-verification | "Confirmed" reported off a success screen, when the booking never took effect |
| rendered-visual-verification | A builder's "done" accepted without inspecting the delivered piece |
| email-absence-claims | "No reply arrived" reported from one shallow search |
| current-plan-before-sending | A stale plan sent because the draft was written before the plan changed |
| verify-instructional-steps | How-to steps published without ever being run on the real tool |
| verified-posting-scan | Dead postings presented as live leads, and candidates dropped silently |

## Where the rules came from

- A rescheduled appointment was reported as confirmed based on the
  booking flow's success screen. The appointment had never moved
  and no confirmation existed; the person caught it herself the
  next morning. That produced booking-proof-verification.
- A delivered video was reported as animated. It was a static
  cutout, and on the user's player it opened black and silent. That
  produced rendered-visual-verification.
- Job postings were twice presented as "verified live" from page
  reads, while an expiry banner sat at the top of the page. That
  produced verified-posting-scan.
- Replies were reported as "not arrived" while the user could see
  them on her own phone, because mailbox search lagged the inbox.
  That produced email-absence-claims.
- A message sent on someone's behalf, from an earlier draft,
  narrowed what she intended to keep open. That produced
  current-plan-before-sending.
- Step-by-step guides kept shipping small falsehoods about
  defaults, versions and where tools write their data. That
  produced verify-instructional-steps.

## Format

Each skill is a standard SKILL.md (name + description frontmatter,
then the rules), usable by any agent that supports the skills
format. Install one, or take the whole pack.

## Status

Published November 9, 2026.
