# VTS Invoice & DO Mailer

Single-file tool for preparing Invoice / Delivery Order dispatch emails and ZOHO serial-number blocks.

## Features
- Records of every invoice/DO generated (search by SO, PO, invoice, company or serial)
- Undo / redo, Bin (recover or delete forever), duplicate and edit records
- Company list with default recipient emails
- Duplicate SO/PO/invoice and serial-count checks
- Status tracking: Draft, Sent, Paid
- JSON backup/import and CSV export
- Optional sync across devices via a private GitHub Gist

## Data & privacy
- No customer data is stored in this repository. Records live in your browser's local storage and, if sync is on, in your own secret Gist.
- Your GitHub token is stored only in your browser. Never paste it into the code or commit it.
- A secret Gist is unlisted, not encrypted.

## Use
Open the site, then Backup & Sync tab to connect a GitHub token (classic, `gist` scope only) on each device.
