# Retzos JDE Helper – Privacy Policy

Last updated: 26 October 2026

Retzos JDE Helper is a Chrome extension used by the finance team of Retzos Group to work with
JD Edwards EnterpriseOne (JDE). It is an internal tool. It is not offered to the public and
is distributed by link only.

## What the extension does

- On JDE journal entry screens it compares each grid line's Company with the document's
  header company and outlines lines that differ.
- On JDE voucher screens it shows each voucher's GL code, looked up from the company's own
  JDE Helper server.
- A folder at the right edge of the JDE window opens two company pages (a calendar and the
  store list, both on the company's internal server) in a new tab. Opening them sends
  nothing from the extension.
- Popup switches turn the checks on or off and show or hide the folder.

## Retzos JDE Helper - Finance

A second edition for accountants does everything above and also fills in JDE forms the user asks
it to: manual payments and customer receipts from the vouchers or invoices the user selected. It
types only into the user's own JDE session, never posts, and sends nothing anywhere else; its
options and a record of what it entered stay in the browser on the user's computer.

## Data the extension handles

- **Voucher identifiers.** To look up GL codes the extension sends the voucher's company,
  document type and document number to the company's JDE Helper server on the company
  network (host `localerp`, port 3100). These identifiers are accounting record keys. They
  are not personal data and they leave the browser only to that server.
- **Settings.** The popup switches and the folder's position on the page are stored in
  Chrome's extension storage on the user's computer. Nothing else is stored.

The extension does not collect, store or transmit personal information, browsing history,
page content outside the JDE screens above, or any data to third parties. It runs only on
`https://jde.retzos.com`.

## Server-side records

The company's JDE Helper server keeps a request log (client IP address, feature, number of
keys requested and matched, status, duration) for 90 days so the operator can see the
service is working. Voucher numbers are not written to that log.

## Sharing and sale

No data is shared with or sold to anyone. The server is operated by Retzos Group on its own
network.

## Contact

Questions about this policy: tlee@retzos.com
