# Font Licensing & Digital Asset Compliance Audit

**A Simulated Legal Review of Multi-Channel Font Usage**

> **Read this first.** This is a student research project built around a **fictional** company, NovaWear. No real client, audit, engagement or dispute exists. The author has no affiliation with Monotype Imaging Inc., MyFonts or any font foundry. Nothing here is legal advice, and nothing here states that any real company or product is compliant or non-compliant.

---

## 1. The business problem

Fonts are software. A brand that uses a typeface on its packaging, website, app, advertising and internal decks may be relying on several different permissions. Monotype, for example, describes separate desktop, web, application, digital ad, e-publication, embedded and server licences, and its current terms measure each channel differently (by user, page view, registered app user or ad impression). A licence bought for one channel does not automatically cover another.

NovaWear, a fictional Indian apparel brand, uses three fonts across eight channels. When asked, it could not produce an executed licence, an order form, a purchase record, a font inventory or installation records. This repository shows how a preliminary legal review would approach that situation: what can be said now, what cannot, what evidence to request, and which questions matter most.

## 2. Objectives

1. Map each channel where NovaWear uses fonts to the type of permission that channel would normally need.
2. Test each use against licence provisions that were actually located and read, without assuming those provisions govern NovaWear.
3. Separate verified source text, interpretation, hypothetical facts, assumptions, open questions and recommendations.
4. Prioritise follow-up work and set out an evidence-collection and remediation sequence.
5. Produce reusable templates (use-case matrix, evidence register, findings register, licence verification checklist).

## 3. Repository contents

```
font-licensing-digital-asset-compliance-audit/
├── README.md                                  This file
├── LICENSE                                    Terms for reusing this repository
├── .gitignore                                 Excludes font files, evidence and local clutter
├── docs/
│   ├── executive-summary.md                   Two-page summary for a supervising lawyer
│   ├── preliminary-audit-report.md            Full use-case analysis (A–I method)
│   ├── clause-by-clause-review.md             Provisions actually located, with pinpoint citations
│   ├── methodology.md                         Review framework, priority scale, review vs audit
│   ├── evidence-and-documentation-guide.md    Collecting and preserving evidence
│   ├── remediation-plan.md                    Phased plan, from evidence collection to escalation
│   ├── limitations-and-assumptions.md         What this project does not and cannot establish
│   └── sources-and-research-log.md            Every source, its version, date and use
├── templates/
│   ├── use-case-matrix.csv                    One row per channel (UC-01 to UC-08)
│   ├── evidence-register.csv                  Evidence received and requested (EV-01 to EV-17)
│   ├── findings-register.csv                  Findings and priorities (FND-01 to FND-10)
│   └── licence-verification-checklist.md      Questions to answer from the actual licence
└── portfolio/
    └── cv-entry.md                            Short CV description of the project
```

## 4. Review framework

### Reference licence frameworks

Because NovaWear has no licence on file, the review uses two publicly available Monotype documents as **reference frameworks**. They show the kinds of conditions a commercial font licence may contain. They are not assumed to govern NovaWear.

| Ref. | Document | Why it is used |
|---|---|---|
| RF-A | Monotype License and Service Terms, Version 2.0 (monotype.com/terms-and-conditions) | Current subscription-style terms with separate grants for desktop, server, applications, web pages and digital marketing |
| RF-B | Monotype Font Software End User License Agreement ("Monotype Single User License Agreement"), undated PDF hosted by Monotype | Older workstation-based model; Monotype's own glossary indicates its "Licensed Unit" concept now appears only in legacy licences |

NovaWear's actual rights could instead come from a MyFonts purchase under a foundry's own EULA, a negotiated agreement, an agency's licence, a font bundled with other software, or an open licence. Identifying the governing document is the first open question (FND-04).

### Method

Every use case is analysed under nine headings:

| | Question |
|---|---|
| A | What is the business doing? |
| B | Which rights or permitted uses may be relevant? |
| C | Which verified licence provision, if any, is relevant? |
| D | What facts and evidence are available? |
| E | What evidence is missing? |
| F | What can and cannot be concluded? |
| G | What follow-up question should be asked? |
| H | What practical remediation or compliance step may be appropriate? |
| I | Low, medium or high review priority, and why? |

The priority scale and the distinction between a preliminary review and a completed audit are explained in [`docs/methodology.md`](docs/methodology.md).

## 5. Headline findings (illustrative)

| ID | Channel | Issue | Priority |
|---|---|---|---|
| FND-01 | Website | Self-hosted web font files apparently converted from desktop files; no web licence or page-view data located | High |
| FND-02 | Mobile app | Font bundled in the app package; no application licence or user figures located | High |
| FND-03 | Cloud storage | Font files in a shared folder open to anyone in the organisation with the link | High |
| FND-04 | All channels | No executed licence, order form, invoice or installation inventory | High |
| FND-05 | Email and HTML5 ads | Web font possibly delivered inside marketing emails and banners | Medium |
| FND-06 | Agency | Font files sent to an external agency; agency's own licence position unknown | Medium |
| FND-07 | Packaging and social | Script font of unknown provenance on commercially sold packaging | Medium |
| FND-08 | Legal framework | Governing law of any licence and Indian protection of font files are unresolved | Medium |
| FND-09 | Packaging and social | Printed and static outputs using the two brand fonts | Low |
| FND-10 | Internal documents | Installation count and editable decks shared with partners | Low |

None of these is a finding of infringement or of compliance. Each records a potential scope mismatch or documentation gap and the evidence needed to resolve it. Full reasoning is in [`docs/preliminary-audit-report.md`](docs/preliminary-audit-report.md).

## 6. Key legal points

- **Scope, not ownership, is the usual question.** Both reference frameworks reserve all rights not expressly granted, so the analysis asks whether a particular act falls inside a particular grant.
- **Indian law links licence scope to infringement.** Section 51(a) of the Copyright Act, 1957 treats as infringement an act done without a licence *or* in contravention of the conditions of a licence, but only where copyright subsists in the work.
- **Whether copyright subsists is itself uncertain.** A font file may arguably qualify as a "computer programme" (s. 2(ffc), read with s. 2(o)), while the typeface design is commonly said by Indian commentators to fall outside the Copyright Act. No Indian judgment on font software was located. The answer affects whether a particular gap is a contractual matter, an infringement risk, or both.
- **Output and distribution differ.** Printed packaging or a flat image reproduces letter shapes; a website, app or HTML email delivers the font file itself. That distinction drives most of the priority ratings.

## 7. Limitations

- All facts about NovaWear are invented for illustration.
- Only sections 1 and 2 (and the opening of section 3) of RF-A were retrieved and read; later sections, including reporting, audit, termination and governing law, were not reviewed.
- RF-B is undated, and whether Monotype still issues it is unconfirmed.
- No private licence, order form, invoice or account record was inspected.
- No link-validation script was run; URLs were opened individually during research.

See [`docs/limitations-and-assumptions.md`](docs/limitations-and-assumptions.md).

## 8. Ethical boundaries

- NovaWear is fictional. Its name was chosen for the exercise; any resemblance to a real business is unintended.
- The fonts are labelled "Brand Sans", "Brand Display" and "Script Accent". They are labels for fictional typefaces, not real products.
- No real company is accused of infringement or described as a Monotype customer.
- Licence provisions are summarised and cited, not reproduced. Readers should rely on the original documents.
- The project does not claim professional audit status or experience at any font company.

## 9. Using the templates

1. **Start with [`templates/licence-verification-checklist.md`](templates/licence-verification-checklist.md).** Work through it once the actual licence documents arrive; it replaces the reference frameworks with the real terms.
2. **Fill [`templates/use-case-matrix.csv`](templates/use-case-matrix.csv)** with one row per channel. Keep columns A to I; they mirror the report.
3. **Log every document in [`templates/evidence-register.csv`](templates/evidence-register.csv)** on receipt, with custodian, date, format and integrity record (see the evidence guide).
4. **Record conclusions in [`templates/findings-register.csv`](templates/findings-register.csv).** Each finding should cite a use case, the provision relied on, and the evidence still missing.
5. **Delete the illustrative rows** before using the templates for a real matter. Each illustrative row is marked `ILLUSTRATIVE` in the `data_status` column.

The CSVs use UTF-8, comma separators and double-quoted text fields, and open in Excel, Google Sheets or LibreOffice.

## 10. Licence for this repository

The author's original text and templates are released under CC BY 4.0 (see [`LICENSE`](LICENSE)). Third-party material referred to here, including Monotype's licence terms and statutory text, is not covered by that licence.
