# Operational Support Portfolio

**Les' Aullian Achmad Argito** — S.T.P., Agricultural Engineering, Universitas Gadjah Mada, GPA 3.44/4.00.

[Open portfolio](https://lesaullianachmadargito.github.io/operational-support-portfolio/)

Application work sample for Operational Support Intern, Aviation Management Division, Sinar Mas Agribusiness and Food. Independent, not affiliated with or endorsed by the company.

## What is demonstrated
- Four fictional office-consumable records with editable quantities, closing balances, missing-input checks and exception flags.
- Six fictional document revisions with review-date and approval-reference checks.
- Four fictional follow-up actions with due-date and completion checks.
- A draft office-record [work instruction](assets/draft-work-instruction.md).
- Current material values can be downloaded as CSV. Document and action CSV links download fixed initial examples.

## Logic and scope
Closing = opening + received - issued, in each item's own whole unit. Mixed units are never totalled. Empty, negative and non-integer activity inputs are unavailable, not zero. A negative calculated closing balance stays visible as an exception. A balance equal to the review level is flagged. No order is placed automatically.

The default four balances are 12 reams, 3 rolls, -5 pieces and unavailable. Three material records need attention. Default review date is 20 October 2026; three document-review items and one overdue open action are flagged. Missing approval references and completion dates are not treated as successful evidence. Draft and superseded document states remain distinct.

Every material, quantity, action, owner label, document and date in the demo is fictional. This covers ordinary office supplies only, not aircraft parts, flight operations, maintenance or airworthiness. It has no backend, authentication, audit trail, transactional ledger or actual approval authority. Changes live only in the browser tab and reset on reload. Public contact is limited to professional email and LinkedIn; no candidate identity documents or participant faces are included.

Actual prior experience is presented separately: research data at SARC UGM, the GRIT inventory prototype using illustrative data, PKM-RE reporting, industrial internship and laboratory teaching. No aviation operating experience is claimed.

## Checks
Run `node test.mjs`. Tests cover default balances, valid zero, missing values, negative/non-integer inputs, review thresholds, dates, missing approval references and completion evidence. Static HTML/CSS/ES modules; no analytics or data submission.

Contact: lesargito@gmail.com · https://www.linkedin.com/in/lesaullianachmadargito
