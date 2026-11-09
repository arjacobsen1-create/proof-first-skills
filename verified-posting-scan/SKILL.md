---
name: verified-posting-scan
description: Use when scanning job boards, listing sites or tender portals for opportunities and reporting what is open. Requires verifying each candidate on the source's own page, reading for expiry or closure notices before calling anything live, and accounting for every candidate and every source so nothing is dropped silently.
---

# Verified Posting Scan

## The rule

A readable page is not a live posting. Some platforms keep the full
description rendered on postings that have expired or closed, so a
page that reads perfectly can be dead. And a scan that drops
candidates silently is worse than a smaller scan that accounts for
every one.

## Fan out and time-box the sources

- Split the sources into independent tracks: trackers, aggregator
  discovery, direct source pages, watchlists. Run them in parallel
  where possible, with one shared output shape.
- Give each source a hard time budget. When it expires, record the
  source as incomplete instead of letting one slow source hold the
  whole run.
- When a source shows a verification challenge or a login wall you
  are not authorised to solve, skip it for this run and record the
  skip and the reason.
- Deliver partial results when some tracks finish and others time
  out, and state the coverage plainly so a partial scan never reads
  as a complete one.

## Verify on the source's own page

- Verify each candidate on the owner's own posting page. Never
  present an aggregator, board or search-result link as the source
  link; carry every discovery hit back to the original posting.
- Read the whole page for an expiry or closure notice before
  calling anything verified, including any banner saying the
  posting has expired, is closed or is no longer accepting
  applications. For platforms known to keep full text on dead
  postings, confirm there is no expiry banner and that an active
  apply or submit control is present.
- If a notice exists, the candidate is excluded with "expired" or
  "closed" as the reason, even when the rest of the page still
  reads like an open role.
- Check and state the posting date, the closing deadline and the
  key eligibility facts for every candidate you present.

## Account for every candidate

- Place every plausible candidate in exactly one outcome:
  verified; unverified, with the missing deciding fact named;
  relisted, with the new reference or date shown; or excluded,
  with the exclusion rule named.
- Never drop a plausible candidate silently because one field is
  missing. That silence is how good candidates surface later by
  accident.
- Cross-check candidates against the applied or already-seen list
  before verification, and keep those out of the new results.
  Label any carry-over as a carry-over, not as new.
- Apply the campaign's own priority gates (freshness, fit,
  eligibility route) before presenting anything as a priority, and
  name an unknown gate as unknown instead of leaving it unstated.
  Fit alone does not make a candidate a priority.

## Recheck at delivery time

- Cross-check the final list against the current tracker or
  applied list again at delivery time, not only at the start.
- Repeat that recheck when the output is delivered later or on
  another surface, and hold or rewrite any item the tracker now
  shows as applied, closed or superseded.
- State that the delivery-time recheck ran when reporting results
  prepared earlier.

## Report the scan

- Order verified results by the campaign's priority, then by
  closing deadline, soonest first, and flag anything closing
  within seven days as urgent, with its exact date.
- Put unverified and relisted items in their own labelled sections,
  each with the one fact that decides whether it is worth a look.
- When nothing new qualifies, say so, and name the sources that
  were skipped or timed out so the empty result can be trusted.
