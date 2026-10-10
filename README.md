# Saakshi site

- index.html: landing page (four seats, how it works, roadmap aligned with the product document, trust, early-access form)
- demo.html (served at /demo): sign in as a provider, invoker, tester or the platform, and follow the ten-chapter story with a shared ledger, receipts, change trail, identity registry and trust centre. Open a seat directly with /demo#provider, /demo#invoker, /demo#tester or /demo#platform.
- demo-v1.html (served at /demo-v1): earlier feature-by-feature views (policy studio, network signals, routing profiles, selective disclosure, KPIs)
- saakshi.example.yaml: the standard manifest providers publish and invokers and testers use with Trust Check
- vercel.json: clean URLs and basic security headers

Tokens (TKN) and payouts are simulated; signatures, hashes and proofs are real and run in the browser.
Settings near the bottom of index.html: CONTACT_EMAIL (set) and FORM_ENDPOINT (paste a Formspree endpoint).
