---
name: verify-instructional-steps
description: Use when writing, reviewing or publishing any step-by-step instructions, guides, runbooks or how-to documents. Requires executing every step against the real tool and version before the steps are treated as final, and labelling honestly what was rehearsed versus what was proven.
---

# Verify Instructional Steps

## The rule

Instructions are only as good as their last real run. A step that
reads correctly can still fail on the version the reader actually
has. If a step was not executed, it is not verified, and the
document must not pretend otherwise.

## Test against the real tool

- Build a clean test environment with the exact tool and version
  the reader will use, and record that version beside the draft.
- Run every command, menu path and configuration change in the
  order the reader will meet them.
- Keep the actual output or error text from each run; it is the
  evidence the draft stands on.
- Check every factual claim the steps depend on: whether a plugin
  ships by default, whether a free plan needs a card, what a
  default port or file location is, where the tool writes its
  data.
- Test the cheapest end-to-end path first with a small example, so
  a broken setup step is found before longer content is built on
  it.
- When a step fails, stop and fix the draft. Never soften a failed
  step into wording that hides the failure.

## Separate rehearsal from proof

- Label a run done with a stand-in model, a local substitute or a
  missing credential as a rehearsal, and name the exact check that
  still needs the real model, key or account.
- Leave account creation, payment entry and identity steps to the
  reader, and mark any step behind those as untested until the
  reader runs it or confirms the result.
- Present the result as reproducible only for the parts the test
  actually reproduced, and name the untested remainder in the
  delivery note.

## Propagate every correction

- When a test changes a shared fact, apply the correction to every
  document, earlier issue and generator script that repeats the
  wrong step, command or claim, and search the whole set for the
  old wording before calling the fix done.
- Recheck earlier drafted or published steps when a later test
  changes a fact they depend on.
- Keep a short test record for the set: the version tested, the
  steps run, what passed, what failed and what remains untested.
