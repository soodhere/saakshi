# Writness site

- index.html: landing page for MCP server publishers
- demo.html: interactive demo (served at /demo). Publisher view by default; /demo#agents opens the agent-team preview; /demo#agent-id opens Agent ID
- vercel.json: clean URLs and basic security headers

Settings near the bottom of index.html:
- CONTACT_EMAIL is set to jigyasacanada@gmail.com
- FORM_ENDPOINT: paste a form service URL (for example a Formspree endpoint) so requests arrive by email without opening the visitor's mail app

To rename the product later, find and replace "Writness" in index.html and demo.html.
