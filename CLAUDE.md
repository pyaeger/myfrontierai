# CLAUDE.md — Frontier / MyFrontierAI

Guidance for any Claude session working in this repository or on the Frontier
project. Last updated 2026-09-20.

## What this repository is

The public MyFrontierAI website and the published Frontier Constitution.
Frontier is Patrick Yaeger's independent personal AI project. The canonical
governing source is Patrick's private knowledge system; GitHub is a public
distribution venue, not the system of record.

Related: `pyaeger/frontier-constitution` holds the charter, license, release
history and adaptation guidance.

## Hard constraint: the Constitution is frozen

**Never edit the constitutional text in `constitution.html`.** Version 1.0 was
published 2026-08-03 and frozen 2026-08-13 under CC BY-SA 4.0. Article XIII
permits amendment only by an explicit, dated, versioned decision carrying a
statement of purpose.

Editing the frozen text would break the project's own audit trail — the thing
it exists to demonstrate. If language genuinely needs to change, it becomes a
new version alongside v1.0, never a silent edit. Page layout, styling, and
surrounding material are fine to change; the charter is not.

## Established origin facts — do not re-derive or estimate

These were reconstructed from primary records in August 2026 and are settled.
Use them; do not guess adjacent dates, and do not restate a date this list does
not contain.

| Date (America/New_York) | Event | Class |
|---|---|---|
| 2025-03-20 | "AI Build Deep Researched" — oldest located ancestor | B |
| 2025-11-09 | DGX Spark evaluated against a custom build | B |
| 2025-11-20 | First recorded sighting of the MS-S1 Max | C |
| 2025-12-21 15:03 | Drive folder taxonomy created (00 INTAKE … 99 ARCHIVE) | B |
| 2026-01-09 21:34 | Jetson Orin Nano considered — last alternative | C |
| 2026-01-16 14:14 | MS-S1 Max ordered (Friday) | A |
| 2026-01-19 00:50 | Shipped | A |
| 2026-01-19 13:59 | Delivered (Monday) | A |
| 2026-01-19 14:35:02 | Photograph of the sealed box, EXIF-stamped | A |
| 2026-01-26 08:24 | Firmware documentation read | B |
| 2026-01-27 18:09 → 2026-01-28 06:34 | The genesis session | B |
| **2026-01-28 02:25** | **"The Frontier Personal AI Ecosystem" — the name first appears** | **B** |
| 2026-02-15 03:04 | "Frontier Physical Architecture v1.1" | A |
| 2026-02-18 | Crucial P310 4TB ordered | A |
| 2026-07-06 07:00 | First commit to this repository | A |
| 2026-08-03 / 2026-08-13 | Constitution v1.0 published / frozen | A |

The name was not assigned. It surfaced in lowercase prose inside the 2026-01-28
research document — "seeking to inhabit the frontier of this new field" — then
became a section heading, then the title.

All times are America/New_York, converted from UTC at the offset in effect on
each date, calibrated against two independent device/server anchors.

## Evidence discipline

Every historical claim about Frontier carries an evidence class:

- **A — Transactional.** Third-party-issued records: email headers, git commits,
  order receipts, camera EXIF. State plainly.
- **B — Server metadata.** Drive `createdTime`. State plainly.
- **C — Attention log.** Forum digests, assistant request receipts. Shows
  interest on a date, never a decision. Frame as context.
- **D — Recollection.** Memory with no artifact. Mark as recollection.
- **Derived.** Calculated from a source. Usable only with the arithmetic shown.

Rules: never state a D item as fact; never promote C to a decision; if a fact is
not in the ledger, it is not established — say so rather than filling the gap.

This mirrors the site's own capability-status table (added 2026-09-14), which
separates Operational / Built and tested / Designed / Proposed with a dated
evidence basis per row. Apply the same separation everywhere: **a written policy
is not evidence that a control is enforced.**

## Canonical records

Held in Patrick's Google Drive, in the canonical-source folder (access required):

- **Frontier Provenance Ledger** — the full dated chronology, evidence classes,
  negative findings, and drafting rules. Safe to quote and to share.
- **Frontier Ledger — Private Notes** — credentials, sensitive content guidance,
  and purchase figures. **Never quote, paste, or reproduce this.**

If asked to write anything about Frontier's history, read the ledger first.

## Never publish

- Purchase amounts and order numbers for any hardware.
- Home address; payment card digits. Both appear in invoice PDFs in Drive.
- Personal content in the 2026-01-28 genesis document — it contains health and
  financial detail written as a private brief. Its architecture sections are
  quotable; the rest is not. Screenshots of it are the specific risk.
- Any credential. A Telegram bot token was found in plaintext in Drive in
  August 2026; treat that document as a credential file.

## Open site items — verify current state before acting

As of 2026-09-20 these were still true; check before reporting them:

- **No `og:image` on either page.** `og.svg` exists but LinkedIn and Facebook do
  not render SVG link previews. A ~1200×630 PNG is needed before any social post.
- **Fonts load from `fonts.googleapis.com` on both pages.** A site arguing for
  local-first sovereignty and governed delegation leaks visitor IPs to a third
  party on every page view. Self-hosting resolves it.

## Naming

**Frontier** is the project. **MyFrontierAI** is the public site.

The private knowledge system that serves as the canonical governing source has
an internal codename. **Do not write that codename into any public file, page,
commit message, or comment.** Refer to it as "the canonical source" or "Patrick's
private knowledge system". The same applies to Hermes and other component names:
internal unless Patrick introduces them publicly himself.

If you find the codename in public material, treat it as an exposure to report,
not as evidence that publishing it was intended.

## Tone

Patrick wants reality over reassurance. If something cannot be done, say so
directly rather than proposing a mechanism that probably will not work. If a
system is unlikely to prevent a recurring failure, say that plainly instead of
implying the failure is solved.
