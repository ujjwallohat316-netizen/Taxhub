# TaxHub

**AI knowledge + intake layer for German Steuerkanzleien.**

TaxHub is a case-study MVP for CITO's Founder's Associate / Entrepreneur & Investor in Residence process. The product thesis is simple: existing practice software remains the system of record; TaxHub makes a firm's trusted knowledge easier to find, verify and turn into action.

## MVP

- Source-grounded knowledge Q&A
- Explicit citations to the underlying German legislation
- Abstention when the demo corpus does not support an answer
- One-click conversion of an answer into a client-request draft
- No API keys, database, or paid services required for the demo

## Demo corpus

The prototype references public German legislation, including the GmbHG and Abgabenordnung. The demo intentionally distinguishes public authoritative material from firm-specific knowledge. A production version would ingest the firm's own procedures, templates, FAQs and approved knowledge base.

## Product wedge

**DATEV stays the system of record. TaxHub becomes the intelligence layer around it.**

The intended ICP is a German Steuerkanzlei with roughly 15–60 employees where senior staff repeatedly answer questions from colleagues and where client intake creates avoidable manual work.

## Important limitation

This is a product prototype, not tax advice or a production tax-compliance system. Statutory requirements can change and should be verified against the current official source before being relied upon.

## Run locally

This prototype is static. Open `index.html` in a browser or serve the directory with any static HTTP server. No environment variables are required.
