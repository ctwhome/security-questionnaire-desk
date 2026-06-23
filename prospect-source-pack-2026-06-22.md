# Security Questionnaire Desk — Prospect Source Pack (2026-06-22)

Purpose: give Curi an approval-ready first revenue batch without sending anything. Use this to manually find founders/operators already talking about customer security questionnaires, then approve one sender/channel/copy before outreach.

Worksheet artifact: `first-batch-prospect-worksheet-2026-06-22.csv` turns the queues below into 10 fill-in no-send slots with fit checks, disqualifiers, channel/draft mapping, and contact-note fields. Approval artifact: `approval-request-2026-06-23.md` contains the exact sender/channel/copy request and first-reply script for Curi to approve before any outreach.

## Batch thesis

Target people who show a live or recent trigger: early B2B SaaS sales, customer security review, vendor questionnaire, SOC2-readiness pressure, or founder/engineer time spent on spreadsheets. The offer is not a GRC platform: it is one redacted questionnaire turned into an answer-library starter + first-draft response map for $99.

## Highest-signal source queues

| Priority | Source / query | Why this source is relevant | Manual qualification step | Suggested channel | Draft to use |
|---|---|---|---|---|---|
| 1 | HN item `36488436` — `https://news.ycombinator.com/item?id=36488436` | Original pain: small startups facing 100+ question client security assessments. | Check commenters/profiles for founders or operators with public contact info; do not scrape private data. | HN reply only if recent/appropriate, otherwise warm/manual email from public site. | HN soft mention or founder email. |
| 2 | HN item `15430123` — `https://news.ycombinator.com/item?id=15430123` | Early SaaS team asking how to prepare for customer security review / pen-test / policies. | Identify comparable current teams via keywords in thread, not by reviving stale pain as if current. | Email/LinkedIn to current comparable teams. | Founder email. |
| 3 | HN item `26513040` — `https://news.ycombinator.com/item?id=26513040` | Stacksi launch proves questionnaire answering is a paid category. | Look for commenters who mention doing questionnaires manually or selling B2B. | HN soft mention only with approval. | HN soft mention. |
| 4 | HN item `25793503` — `https://news.ycombinator.com/item?id=25793503` | Dumb-questionnaire discussion validates mismatch/annoyance. | Filter for vendors who receive questionnaires, not buyers issuing them. | HN reply/manual email. | HN soft mention. |
| 5 | HN Algolia query: `security questionnaire startup SaaS` | Current query returned 2025/2026 SOC2/compliance-startup chatter plus direct older pain. | Re-run before outreach; capture only public profiles. | Manual email/LinkedIn. | Founder email. |
| 6 | HN Algolia query: `vendor security questionnaire startup` | Finds vendor-questionnaire language and startup context. | Exclude compliance-tool vendors unless they are a possible partner/channel. | Manual email/LinkedIn. | Founder email or partner note. |
| 7 | Google query: `"security questionnaire" "founder" "SaaS"` | Likely to surface blog posts, founder posts, and LinkedIn snippets. | Confirm current company, B2B product, and public contact. | Email/LinkedIn. | Founder email / LinkedIn DM. |
| 8 | Google query: `"customer security review" "startup" "SaaS"` | Buyer-trigger phrasing from early enterprise sales. | Prioritize posts mentioning a current deal/review, not generic SOC2 guides. | Email. | Founder email. |
| 9 | Google query: `"spreadsheet" "security questionnaire" "SaaS"` | Strong fit for the import → map → export wedge. | Look for teams with spreadsheet pain, not enterprise GRC teams. | Email. | Founder email. |
| 10 | LinkedIn search: `"security questionnaire" "B2B SaaS" founder` | More likely to expose currently active founders/operators. | Manual only; no automated scraping or account actions from cron. | LinkedIn DM after Curi approval. | LinkedIn founder DM. |
| 11 | LinkedIn search: `"vendor questionnaire" "startup"` | Vendor-risk terminology catches procurement-driven pain. | Confirm they are answering questionnaires, not issuing them. | LinkedIn DM/email. | LinkedIn founder DM. |
| 12 | Warm-network ask | Fastest safe route: ask Curi’s network for founders hit by questionnaires. | Curi chooses who to send to. | Warm text/email. | Warm network text. |

## Approval-ready first batch

Recommended first batch size: **10 manually qualified prospects**.

Suggested approval request to Curi:

> Approve one outreach batch for Security Questionnaire Desk: I will use the public page and the $99 launch-pack copy in `outreach.md`, from sender identity `Jesse / CTW`, over **[choose: LinkedIn DM / direct email / warm-network text]**, to 10 manually qualified B2B SaaS founders/operators who publicly mention security-questionnaire pain. No claims beyond redacted questionnaire → answer-library starter + first-draft response map; no SOC2/compliance advice.

## Qualification checklist before a prospect enters the batch

- B2B SaaS or software vendor selling to larger companies.
- Public signal of security questionnaire, customer security review, vendor risk assessment, or SOC2-readiness pain.
- Small enough that full GRC/trust-center tooling may be overkill.
- Public contact/channel available without account creation, scraping, or impersonation.
- Message can truthfully reference the public signal without sounding like surveillance.
- Disqualify if they need legal/security advice, certification, control monitoring, or trust-center replacement.

## Exact first-reply ask

If someone replies with interest, ask only for:

1. whether a current deal is blocked;
2. approximate row/question count;
3. whether they already have an answer library;
4. whether they can send a redacted questionnaire or sample rows;
5. whether they want the $99 launch pack.

Do not ask for secrets, customer names, credentials, network diagrams, personal data, or unreleased security details.
