# Wildflower Therapy Ops target state

## Existing base that must remain
- Patients
- Providers
- Scheduling month/week/day
- Payers
- Imports
- Referral intake base

## Missing or incomplete items to add without erasing the above

### Referrals
- Parse real pasted referral text better.
- Support shorthand like DOB:06062017, phone; 9046909954, insurance: cms, dx: 985.1, pt eval.
- Parse one-line address into full street address, apt/unit, city, state, zip.
- Street address must include house number.
- Notes box for office staff.
- Received documents checklist.
- Approval or denial status.
- Queue that shows where referral is in process.
- Patient auto-fill from referral.
- Carry handoff into schedule.

### Intake
- Cleaner layout.
- Actual intake items to check off.
- Notes section.
- Show what has been received and what is missing.

### Providers
- Keep NPI data visible and editable.
- Keep blocked times.

### Schedule
- Keep original schedule views.
- Eval slot suggestions grouped by date.
- More times option.
- Clear handoff when scheduling from referral.

### Billing
- CPT helper.
- Visible CMS-1500-style preview, not just a text placeholder.

### Parent portal
- Parent/caregiver message threads.
- Staff replies.

### Reports
- Usable counts and workflow visibility.

## Constraints
- Single-file HTML app is acceptable.
- Must actually render content on every page.
- No blank screens.
- No hidden logic without frontend controls.
