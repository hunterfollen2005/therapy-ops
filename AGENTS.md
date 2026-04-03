# Therapy Ops rules for Codex

You are patching an existing single-file HTML app named `therapy_ops_phase5_2.html`.

## Non-negotiables
- Keep the original working Phase 5.2 structure.
- Keep the sidebar navigation.
- Keep all original pages working and visible.
- Keep month, provider week, and provider day schedule views.
- Keep providers with NPI data.
- Keep patients, payers, referrals, schedule, and imports pages.
- Do not replace the app with blank placeholder pages.
- Do not delete working logic just because new pages are added.
- Do not ship broken navigation or empty render functions.
- Do not silently remove original data fields.
- Keep the app usable on desktop and phone widths.

## Build direction
This is a Wildflower-only office workflow tool. It is not meant to be generic SaaS.

## Required additions
- Better referral parser for messy pasted office text.
- Full street address parsing and display, including house number.
- Referral processing statuses, received document tracking, approval/denial, and notes.
- Auto-create or update patient from referral.
- DX and CPT helpers.
- Intake workflow page.
- Authorization tracking page.
- Parent portal messaging page.
- Billing page with visible CMS-1500-style preview.
- Reports page with actual counts.

## Implementation preference
Prefer patching the existing file instead of rewriting from scratch.
If a new file is created, keep the old file intact and clearly label the new one.
