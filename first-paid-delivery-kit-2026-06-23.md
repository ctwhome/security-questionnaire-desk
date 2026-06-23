# Security Questionnaire Desk — First Paid Delivery Kit (2026-06-23)

Purpose: make the first $99 launch-pack sale fulfillable immediately after an approved prospect replies. This is a **manual delivery kit**, not a compliance program. Do not send or request anything externally without Curi-approved sender/channel/copy.

## Sellable promise to confirm before payment

> For $99, I’ll turn one redacted customer security questionnaire into a reusable answer-library starter and a first-draft response map with `answered / needs owner / do not claim` confidence flags. I will not provide SOC2/compliance/legal/security advice, certify anything, or invent claims.

## Intake email after a prospect replies “questionnaire”

Subject: Redaction checklist + first questionnaire pack

Hi {{first_name}},

Great — the first pack is intentionally narrow: one redacted questionnaire -> answer-library starter + first-draft response map.

Before sending anything, please remove:

- customer names, contractual terms, account names, and contact info;
- secrets, API keys, credentials, IPs, network diagrams, and sensitive screenshots;
- employee/customer personal data;
- unreleased product/security details that should not leave your company.

Safe to include:

- question text and section headings;
- blank answer cells;
- generic answers you already send to prospects;
- policy/control statements your team is comfortable reviewing.

Quick checks before I take it on:

1. Is this blocking a current or near-term deal?
2. Roughly how many rows/questions/portal sections are there?
3. Do you already have any reusable answer library?
4. Who on your team must approve uncertain answers?
5. Do you want a first-draft map only, with `needs owner` / `do not claim` flags where truth is unclear?

If yes, send a redacted CSV/XLSX/doc export or sample rows. I’ll confirm scope before payment.

— Jesse / CTW

## Manual fulfillment workflow

1. **Scope check**
   - Accept only one questionnaire or a representative sample.
   - Reject/disqualify requests for SOC2 certification, legal/security advice, control monitoring, pen-test remediation, policy writing, or trust-center replacement.
   - Confirm the file is redacted before opening deeply.

2. **Normalize questions**
   - Copy rows into `answer-map-template.csv` shape.
   - Group by theme: company, access control, authentication, encryption, infrastructure, logging, backup/DR, incident response, privacy, subprocessors, compliance, other.
   - Preserve original question text; do not rewrite it into claims.

3. **Draft reusable answer-library starter**
   - Reuse only existing customer-provided answers or safe generic placeholders.
   - If truth is not known, mark `needs owner`.
   - If the questionnaire asks for a control/process the team does not have, mark `do not claim`.

4. **Create response map**
   - Columns: `source_question`, `theme`, `draft_answer`, `confidence`, `owner`, `do_not_claim`, `evidence_needed`, `reusable_library_entry`, `notes`.
   - Confidence values only: `answered`, `needs owner`, `do not claim`.
   - Add concise `evidence_needed` notes for owner follow-up.

5. **Delivery note**
   - State that the output is a first-draft answer map for internal review.
   - Tell the customer to have the relevant owner approve every answer before sending it to their customer.
   - Reiterate no compliance/legal/security advice.

## Acceptance criteria for the first paid pack

- Customer receives a clean CSV/XLSX-style answer map.
- Every row has a confidence flag.
- Unknowns are not smoothed over; they are visibly assigned to an owner or marked `do not claim`.
- At least 5 reusable library entries are extracted when source material permits.
- No secrets/customer data are retained in notes.
- Follow-up questions are limited to deal-unblocking facts, not broad compliance consulting.

## 48-hour delivery positioning

Use only if Curi approves the promise for the batch:

> Launch-pack turnaround target: 48 hours after receiving a redacted file and confirming scope. If the questionnaire is unusually large, I’ll quote the smallest useful slice first instead of pretending the $99 pack covers a full GRC cleanup.

## First-revenue gate

Ready to use after these are true:

- Curi approves sender identity, channel, batch size, and exact copy in `approval-request-2026-06-23.md`.
- Public artifacts are deployed or the email includes the redaction checklist inline.
- Prospect has a current questionnaire and agrees to the narrow first-draft response-map scope.
