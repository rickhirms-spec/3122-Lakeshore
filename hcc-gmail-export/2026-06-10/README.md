# HCC 109 Gmail Export Manifest

Source mailbox: `HCC.mbox`

Parsed mailbox results:
- Total emails parsed: 243
- Attachments extracted locally: 389
- Emails flagged as HCC/condo/property relevant: 156

Generated locally:
- `README.md` — timeline summary and top senders/domains
- `condo_relevant_full_messages.md` — full text of flagged HCC/condo messages
- `condo_relevant_email_index.csv` — structured index for flagged messages
- `condo_timeline.csv` — chronological timeline with excerpts
- `attachment_inventory.csv` — attachment metadata with filename, source email, type, size, hash
- `all_email_index.csv` — all mailbox messages
- `attachments/` — extracted original attachments
- `messages/` — one Markdown file per email

Important note: the full attachment bundle was extracted locally but was not uploaded here because the GitHub connector is best suited to UTF-8 text files, while many attachments are binary PDFs/images. A ZIP export was generated separately for download.

## High-value HCC/property subjects found
- Re: Your purchase of 29 - 3122 Lakeshore Road W, Oakville
- HCC 109 Periodic Information Certificate
- HCC 109 - Periodic Information Certificate
- HCC109 - Arrears payment #29
- HCC 109 - Notice
- HCC 109 - AGM Package
- HCC 109 - Operating Budget
- HCC 109 - Community Newsletter
- HCC 109 - Special Assessment Letter for 2026
- HCC 109 - unit 29 - Records Request
- Halton Condominium Corporation No. 109 - Records & Special Assessment
- NOTICE: MRCM Statement of Account for HCC 109 Unit 29
- CondoCafe invite / account access

## Main property/condo related senders identified
- MRC Customer Service <customerservice@mrcm.ca>
- MRC Customer Service2 <customerservice2@mrcm.ca>
- John McKenzie <JMcKenzie@mrcm.ca>
- Rehanna Rohan <RRohan@mrcm.ca>
- Information Certificates <information.certificates@WILSONBLANCHARD.COM>
- Michelle Kelly <mkelly@rcllp.ca>
- Stefanie Benoit <S.Benoit@atrens-counsel.com>
- PMG Accounting <acct@pmguild.ca>
- Gail Cote <gail@pmguild.ca>
- Gessica Zublena <gessicazublena@gmail.com>

## Sample recent HCC timeline entries
- 2026-05-26 — HCC 109 Periodic Information Certificate — attachment: HCC_109_May_2026_PIC.pdf
- 2026-02-18 — HCC 109 - Newsletter — attachment: Newsetter_-_Winter_Edition_-Feb-26.pdf
- 2026-02-15 — NOTICE: MRCM Statement of Account for HCC 109 Unit 29 — attachment: Statement_of_Account.pdf
- 2026-02-11 — HCC 109 Exclusive Offer from Associa Canada from Enbridge Sustain
- 2026-01-07 — FW: HCC 109 - unit 29 - Records Request — attachment: Request_for_Records_12102025_RS.pdf
- 2025-12-22 — HCC 109 - Special Assessment Letter for 2026 — attachment: Special_Assessment_Letter_FINAL.pdf
- 2025-12-09 to 2025-12-23 — Halton Condominium Corporation No. 109 - Records & Special Assessment correspondence
- 2025-11-28 — HCC 109 - Operating Budget — attachment: HCC_109_Budget_Letter_FINAL.pdf
- 2025-11-24 — HCC 109 Periodic Information Certificate — attachment: HCC_109_November_2025_PIC.pdf
- 2025-10-23 — HCC 109 - Community Newsletter

## Next recommended repo additions
Upload the generated local text/index files from the ZIP if you want the repo to contain every extracted message and every CSV index. Keep the raw attachment ZIP out of the public repo if it contains personal, legal, financial, school, or utility documents.