# X55 AI — Stripe Legal Alignment Audit

Date: 26 September 2026

## Scope

This package aligns the public website with the four legal documents prepared for Stripe:

1. Terms & Conditions
2. Acceptable Use Policy (AUP)
3. Privacy Policy
4. Law Enforcement & Legal Requests Protocol

The Telegram bot source code was **not modified**.

## Changes made to the website

- Replaced the placeholder `agreement.html` with substantive Terms & Conditions.
- Replaced the placeholder `privacy.html` with a substantive Privacy Policy.
- Added `acceptable-use.html`.
- Added `law-enforcement.html`.
- Replaced the FAQ redirect with a substantive FAQ / Help Center page.
- Added links to all four legal documents in the main-site footer.
- Added safety, AI-processing, minors and reporting questions to the main-site FAQ.
- Disclosed the current bot's use of DeepSeek for AI-assisted processing in the Privacy Policy and FAQ.
- Added explicit prohibitions covering prostitution, commercial sexual services, trafficking, grooming, child sexual exploitation and other prohibited conduct.
- Added a public legal-request procedure and legal contact.
- Preserved the existing site pricing/duration text as requested; payment amount and access duration were intentionally not reconciled in this package.

## Remaining operator inputs before publication

The following placeholders must be completed by the operator:

- Legal entity name
- Registered address
- Registration number, if applicable
- Actual production retention periods
- Final production processor/subprocessor list and roles
- Applicable international-transfer safeguards, where required

## Important bot-side issues intentionally left unchanged

The current bot source contains legal/privacy wording that should be reviewed later against the website, especially the wording that states personal data is not transferred to third parties while the current implementation sends AI-related data to DeepSeek. This package does not modify that bot wording because the instruction was to leave bot code unchanged.

The bot also contains payment/access wording that is intentionally outside the scope of this alignment pass.
