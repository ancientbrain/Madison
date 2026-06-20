# gaps.md — Satwika Maddukuri
# Generated: June 2026 | Attested: 2026-06-20
# Migration rule: a gap closes only with evidence → new resume.json entry → row deleted

| Gap | Evidence the target demands it | What I have | Madison build that would close it | Plan |
|---|---|---|---|---|
| **Third party risk assessment experience** | State Street job posting R-790974 lists "vendor due diligence" and "third party assessments" as core responsibilities. GRC analyst postings at JPMorgan, Fidelity, and BNY Mellon consistently require demonstrated TPRM experience. | Human Risk Report Generator demonstrates behavioral risk assessment logic. State Lottery co-op covers vulnerability management but not vendor-facing assessment workflows. | Extend Human Risk Report Generator with a vendor onboarding workflow — automate the behavioral risk intake form and generate a vendor-specific risk score. This is a real TPRM deliverable. | Build v2 of Human Risk Report Generator with vendor input fields (vendor name, industry, employee count) by August 2026. Document as a TPRM portfolio piece. |
| **Financial services regulatory knowledge (FFIEC, SOC 2, DORA)** | State Street posting requires "regulatory compliance" experience. Financial services GRC roles universally reference FFIEC, SOC 2 Type II, and increasingly EU DORA for global firms. | General cybersecurity compliance knowledge from ISC2 CC. No direct financial services regulatory coursework or project work. | Build a Madison recipe that maps Human Risk Report Generator output to FFIEC cybersecurity assessment framework categories — demonstrating applied regulatory knowledge in a portfolio artifact. | Complete FFIEC CAT self-study module (free, FFIEC.gov) by September 2026. Add FFIEC mapping to Human Risk Report Generator v2. |
| **Advanced security certification (CRISC or CISM)** | CRISC appears in 34% of third party risk analyst job postings at financial institutions (source: CyberSeek 2025). State Street posting R-790974 lists CRISC as preferred. Hiring manager Michael Yun holds CRISC, CISM, CISA, CISSP. | ISC2 Certified in Cybersecurity (CC) — entry level. No intermediate or advanced certification. | No Madison build closes this gap — it requires passing an exam. However, the Human Risk Report Generator project provides direct study material for CRISC domain 2 (IT Risk Assessment) and domain 3 (Risk Response). | Register for CRISC exam preparation by January 2027. Use Human Risk Report Generator project as applied study anchor for risk assessment domains. |
| **Published security research or thought leadership** | Senior GRC and TPRM roles increasingly expect LinkedIn articles, conference presentations, or published frameworks. Hiring managers Google candidates — finding nothing beyond a profile is a missed opportunity. | No published writing, no conference presentations, no public thought leadership. | Write a Madison-style analysis of human behavioral risk in financial services vendor ecosystems — publishable as a LinkedIn article or Medium post. The Human Risk Report Generator provides the data and the framework. | Write and publish one LinkedIn article on human behavioral risk in TPRM by August 2026 using Human Risk Report Generator findings as source material. |
| **GitHub portfolio with professional README** | Technical security roles and AI-adjacent security roles increasingly expect a GitHub presence. Human Risk Report Generator is deployed but the repo README is minimal. | GitHub repo exists with app.py and requirements.txt. No professional README, no architecture documentation, no usage guide. | Add a professional README.md to the human-risk-app repo — problem statement, architecture diagram, data sources, usage instructions, and live URL. This is a 2-hour task with outsized portfolio impact. | Write professional README.md for human-risk-app repo by June 25, 2026. |

---

## Project Proposal — Top Gap Row

**Proposed Madison Build: Human Risk Report Generator v2 — Vendor TPRM Workflow**

The most significant gap between my current profile and the State Street Third Party Cyber Risk Analyst role (R-790974) is demonstrated vendor-facing risk assessment experience. My current Human Risk Report Generator assesses organization types generically — it does not model the workflow a TPRM analyst actually runs when onboarding a new vendor.

Version 2 of the Human Risk Report Generator will extend the existing Madison SyntheticPersonas pipeline with a vendor intake layer: the analyst inputs vendor name, industry, employee count, and data access level. The pipeline generates a vendor-specific behavioral risk profile — scored against the same 270 records of phishing, social engineering, and CISA advisory data — and produces a structured vendor risk report aligned to FFIEC cybersecurity assessment framework categories.

This build closes three gaps simultaneously: it demonstrates TPRM workflow knowledge, produces a financial services regulatory artifact (FFIEC mapping), and creates a portfolio piece that directly mirrors the work described in the target job posting. The deliverable is a deployed tool with a documented vendor assessment workflow — something no other entry-level candidate is likely to present in an interview at State Street.

**Target completion: August 2026 | Estimated build time: 15-20 hours**

---

## Deleted row — with reason

~~**Social media presence gap**~~ — Deleted. On review, the target audience (financial services security hiring managers) does not discover candidates through social media activity. LinkedIn profile and GitHub portfolio serve the discovery function. Maintaining a Twitter/X or Instagram presence for cybersecurity content would not meaningfully improve hiring outcomes for this specific aspiration. Evidence: rejected channel reasoning in brand.yml. Investing time in social content creation would trade off against certification study and Madison build time — a bad trade at this stage.
