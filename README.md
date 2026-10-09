# Writness site

- index.html: landing page
- demo.html: interactive demo (served at /demo), seven views:
  - /demo or /demo#end-to-end: the whole lifecycle in ten steps (default)
  - /demo#metrics: metrics and KPIs with tenant scopes and filters
  - /demo#publisher: publisher gateway flow
  - /demo#agents: agent-team controls
  - /demo#agent-id: agent identity and accountability chain
  - /demo#ledger: smart agreements, token payments, escrow, selective disclosure, consortium ledger
  - /demo#studio: consent, policy studio, both sides, monetization
- vercel.json: clean URLs and basic security headers

All prices and payments are in tokens (TKN), simulated. Signatures, hashes and proofs are real and run in the browser.

Settings near the bottom of index.html: CONTACT_EMAIL (set) and FORM_ENDPOINT (paste a Formspree endpoint to collect requests).
To rename the product, find and replace "Writness" in index.html and demo.html.
