# TaxHub — Case One-Pager

## 1. Why TaxHub?

**Beachhead:** German Steuerkanzleien, initially firms with ~15–60 employees.

The profession is large and structurally fragmented: as of 1 January 2026, the German tax adviser chambers counted **105,953 members**, including **89,549 Steuerberater** and **15,232 recognised professional practice companies**. **65.9% of Steuerberater were self-employed**, supporting the thesis that the market contains a large owner-led segment. [BStBK Berufsstatistik 2025](https://www.bstbk.de/mediapool/bstbk/ebooks/Berufsstatistik-2025/).

The incumbent is strong, not absent. DATEV reported **40,176 cooperative members and 1.01 million customers** as of 30 June 2026. That makes replacement a bad wedge. The better thesis is an AI layer that works around the existing system of record. [DATEV, 2026](https://www.datev.de/web/de/berufsgruppenuebergreifend/presse/presseinformationen/meldungen-2026/datev-steigert-umsatz-und-kundenbasis).

There is evidence of willingness to digitise: DATEV's 2025 survey found the leading digitalisation driver was **efficiency improvement (73%)**, followed by location-independent data access (72%). But **54% cited lack of time** and **46% implementation effort** as barriers. The product therefore needs to be low-friction and additive, not another core-system replacement. [DATEV Digitalisierungsumfrage 2025](https://www.datev.de/web/de/berufsgruppenuebergreifend/ueber-datev/das-unternehmen/datev-studien/datev-digitalisierungsumfrage).

## 2. ICP

**Primary buyer:** owner / managing partner of a 15–60-person Steuerkanzlei.

**User:** tax assistants, junior advisers, bookkeeping staff and other employees who repeatedly need answers from senior colleagues.

**Pain hypothesis:** firm knowledge is distributed across people, internal documents, templates, client processes and external authoritative sources. Finding the trusted answer is slower than asking the person who already knows it; converting that answer into a client-facing request creates another manual step.

**This is an assumption to validate in customer discovery, not a claimed market statistic.**

## 3. Product wedge

> **Your firm's knowledge. Instantly usable.**

TaxHub combines:

1. **Knowledge:** firm procedures, templates, FAQs and approved external material.
2. **Grounded Q&A:** answer only when the corpus supports the answer; show the underlying source.
3. **Intake/action:** turn the answer into a checklist or client email.

**Positioning:** DATEV remains the system of record. TaxHub is the intelligence layer around it.

## 4. What the real product would build first

**Phase 1:** secure knowledge ingestion + retrieval + citations + permissions.

**Phase 2:** client-intake assistant that captures the request, identifies missing information and drafts the next response.

**Phase 3:** integrations with the firm's existing workflow, including DATEV where commercially and technically appropriate.

The MVP intentionally does not attempt to replace practice-management software, provide autonomous tax advice, or automate every workflow.

## 5. Willingness to pay

**Pricing hypothesis, not a sourced market fact:** €500–€1,500/month for a 15–60-person firm, depending on users, corpus size and workflow modules.

The initial sale should be framed around a measurable pilot rather than a feature list: take 20 real internal questions from the previous month, test how many can be answered with source support, and measure senior-intervention time saved.

## 6. Three hardest objections

### “We already have DATEV.”
**Answer:** “Exactly. TaxHub is not asking you to replace it. DATEV remains where the firm's core records live. We sit above the workflow and make the knowledge around those records easier to use.”

### “AI cannot be trusted with tax questions.”
**Answer:** “I agree that an ungrounded chatbot should not be trusted. That's why TaxHub's first principle is abstention: if the firm's approved sources don't support an answer, it says so. Every answer exposes the underlying source for verification.”

### “I don't have time to implement another tool.”
**Answer:** “That's the reason the first pilot is deliberately narrow. Give us a small approved knowledge set and 20 real questions. If the team doesn't save meaningful time without a large implementation project, we stop.”

## 7. First 30 days

**Days 1–7 — validate:** interview 10 Steuerkanzleien; collect 100 anonymised recurring questions; map where answers currently live.

**Days 8–14 — prove retrieval:** ingest one controlled knowledge domain; benchmark answers against human-approved answers; measure citation accuracy and abstention rate.

**Days 15–21 — prove workflow:** add intake and client-response drafting; test with one pilot firm.

**Days 22–30 — sell:** run a paid/pilot conversion experiment with 5–10 firms; price against measurable time saved rather than generic AI usage.

## 8. MVP evidence corpus

The live prototype uses a small corpus of current public German legislation from the Federal Ministry of Justice:

- **GmbHG §7 — Anmeldung der Gesellschaft**: registration with the commercial register and statutory capital-contribution conditions.
- **GmbHG §8 — Inhalt der Anmeldung**: documents and declarations accompanying the registration application.
- **AO §147 — Aufbewahrung von Unterlagen**: statutory record-retention requirements and periods.

The prototype links each answer back to the official source. These sources are evidence for the demo, not a substitute for a firm's approved production knowledge base.

## 9. Product principle

**Grounded, not invented.** If the evidence is not in the knowledge base, TaxHub should say that it does not know.
