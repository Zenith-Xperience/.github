<!--
=============================================================
  BEFORE YOU FILL THIS IN - READ FIRST
=============================================================
  FEATURE / BUG FIX PR → fill in all sections below.
  Sections marked * are mandatory.
  QUICK PR (typo fix, copy change, minor style tweak, config
  update with no functional impact) → Description* is
  a mandatory section. Remove other sections as required
  - titles, tables, and checklists included.
=============================================================
-->
## Issue Reference
- **Issue:** Relates to #[issue number]
<!-- Do NOT use "Closes #123" here - QA verifies after merge on main, and the issue should only close once QA confirms it. -->
## Description*
<!-- What does this PR do? Why is it needed? Keep it concise but complete. -->
## Implementation Checklist
<!-- List every distinct piece of work in this PR. This same list will be used by QA post-merge to verify on the live environment. -->
- [x] Item 1 - short description
- [x] Item 2 - short description
- [x] Item 3 - short description
## Dev Proof
<!-- Screenshots, screen recordings, logs, or links showing the implementation working locally/in dev. One per checklist item if possible. -->
| Checklist Item | Proof |
|---|---|
| Item 1 | [screenshot/video link] |
| Item 2 | [screenshot/video link] |
| Item 3 | [screenshot/video link] |
## Environment Variable Changes
<!-- Confirm whether this PR requires any changes to environment variables in dev/staging/prod. If it does, uncheck the box below, check the "requires" box instead, and fill in the tables so DevOps/QA can apply the changes before verification. -->
- [x] This PR does **not** require any environment variable changes
- [ ] This PR **requires** environment variable changes (list below)

### Current Production Env List
<!-- List the relevant env vars as they currently exist in production (leave blank if none exist yet). -->
| Variable Name | Current Value / Status |
|---|---|
|  |  |

### Release Env List (what to add / change in production)
<!-- What DevOps needs to add or update in production for this release. -->
| Variable Name | Purpose | Environment(s) Affected | New / Updated / Removed | Value to Set |
|---|---|---|---|---|
|  |  |  |  |  |
## Notes / Known Issues
<!-- Anything reviewers or QA should know - edge cases, follow-ups, things intentionally left out, etc. -->
