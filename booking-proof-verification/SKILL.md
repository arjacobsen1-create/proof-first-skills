---
name: booking-proof-verification
description: Use whenever an agent books, reschedules, cancels, orders or submits anything on someone's behalf and is about to report the result. Gates the word "confirmed" on a proof artifact, so a flow's success screen is never reported as a completed action.
---

# Booking Proof Verification

## The rule

An action is not done until there is proof it took effect. A success
screen, a completed form, a slot shown as taken, or a spinner that
stopped settles nothing on its own.

## Accept as proof

- A confirmation email, receipt or message carrying the booking or
  order reference, showing the date, time and details of the action.
- A record read back from the provider's own system after the action
  (account page, booking list, order history) showing the new state.

## Do the verification at the time of the action

- Search every mailbox the confirmation could have been sent to
  before concluding none arrived; providers send proof to any
  address used across earlier bookings.
- Search by provider name, reference number and service type. For a
  cancellation, look for the cancellation confirmation the same way.
- If several bookings exist, reconcile them into one inventory —
  each reference with its date and time — and flag exact duplicates
  instead of reporting a single clean state.
- Trust a confirmation artifact over a conflicting screen, including
  a screen claiming the action was rejected. Restate the state from
  the artifact.

## Report only what you can prove

- Behind every "confirmed" report, name the proof: the reference
  and the date and time the artifact shows.
- With no proof in hand, report the action as attempted but
  unverified, say exactly which proof is missing, and say where
  you looked.
- Never phrase an unverified state as cancelled, moved, booked or
  confirmed.
- Keep the earlier booking in place until the replacement carries
  its own proof, so a failed reschedule never leaves the person
  with nothing booked.
- When verification fails, offer the choice to complete or rebook
  it themselves rather than repeating the same flow and reporting
  the same unproven result.
