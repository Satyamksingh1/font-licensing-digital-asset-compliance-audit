# Font Licensing & Digital Asset Compliance Audit

**A Simulated Legal Review of Multi-Channel Font Usage**

> **Read this first.** This is a student research project built around a fictional company, NovaWear. No real client, audit, engagement or dispute exists. The author has no affiliation with Monotype Imaging Inc., MyFonts or any font foundry. Nothing here is legal advice, and nothing here states that any real company or product is compliant or non-compliant.

---

## 1. The Business Problem

Fonts are software, and commercial font licences may grant different permissions for desktop, web, application, advertising, e-publication, embedding and server use. The permitted use and applicable limits depend on the actual licence terms.

NovaWear, a fictional Indian apparel brand, uses three fonts across eight channels. In the hypothetical scenario, it cannot produce an executed licence, order form, purchase record, font inventory or installation records.

This project demonstrates how a preliminary legal review could approach that situation: what can be established from available information, what remains uncertain, what evidence should be requested, and which questions require priority attention.

## 2. Objectives

1. Map each channel where NovaWear uses fonts to the permissions that may be relevant.
2. Compare hypothetical uses against located licence provisions without assuming those provisions govern NovaWear.
3. Distinguish source text, legal interpretation, hypothetical facts, assumptions, open questions and recommendations.
4. Prioritise follow-up work, evidence collection and potential remediation.
5. Develop reusable templates for use-case mapping, evidence tracking, findings and licence verification.

## 3. Repository Contents

```text
font-licensing-digital-asset-compliance-audit/
├── README.md
├── LICENSE
├── .gitignore
├── docs/
│   ├── preliminary-audit-report.md
│   ├── methodology.md
│   └── sources-and-research-log.md
├── templates/
│   ├── use-case-matrix.csv
│   ├── evidence-register.csv
│   ├── findings-register.csv
│   └── licence-verification-checklist.md
└── portfolio/
    └── cv-entry.md
```

The original root-level copies of some documents may remain in the repository while the folder structure is being organised. The files listed above are the intended organised locations.

## 4. Reference Licence Frameworks

Because the fictional company has no licence on file, the review uses publicly available Monotype documents as reference frameworks to illustrate the kinds of conditions a commercial font licence may contain. They are not assumed to govern NovaWear.

| Reference | Document | Purpose |
|---|---|---|
| RF-A | Monotype License and Service Terms, Version 2.0 | Reference for licence grants and potential differences between usage channels |
| RF-B | Monotype Font Software End User License Agreement, also described as the Monotype Single User License Agreement | Reference for an older workstation-based licensing model |

The actual rights could instead arise from a MyFonts purchase under a foundry's EULA, a negotiated agreement, an agency licence, software bundling or an open licence. Identifying the applicable agreement is therefore a preliminary question.

**Research limitation:** Only sections 1 and 2 and the opening of section 3 of RF-A were retrieved and read. RF-B is undated, and its current status has not been confirmed. These limitations restrict the conclusions that can responsibly be drawn.

## 5. Methodology

Each hypothetical use case is assessed under nine headings:

- **A — Activity:** What is the business doing?
- **B — Relevant permissions:** Which rights or permitted uses may apply?
- **C — Licence provision:** Which located provision, if any, is relevant?
- **D — Available evidence:** What facts and documents are available?
- **E — Evidence gaps:** What is missing?
- **F — Assessment:** What can and cannot be concluded?
- **G — Follow-up:** What should be clarified?
- **H — Practical response:** What verification or remediation may be appropriate?
- **I — Priority:** Is the issue low, medium or high priority, and why?

The distinction between a preliminary review and a completed audit is important. The project does not establish the company's actual licensing position.

See [`docs/methodology.md`](docs/methodology.md) for the review framework.

## 6. Illustrative Headline Findings

| ID | Channel | Potential issue | Priority |
|---|---|---|---|
| FND-01 | Website | Self-hosted web font files; web permissions and usage data not located | High |
| FND-02 | Mobile app | Font bundled in the application; application licence and user figures not located | High |
| FND-03 | Cloud storage | Font files in a shared folder; access and permitted distribution require verification | High |
| FND-04 | All channels | No executed licence, order form, invoice or installation inventory available in the scenario | High |
| FND-05 | Email and HTML5 ads | Potential font delivery in marketing materials requires verification | Medium |
| FND-06 | Agency | Font files sent to an external agency; its licence position is unknown | Medium |
| FND-07 | Packaging and social | Provenance of the fictional script font is unknown | Medium |
| FND-08 | Legal framework | Governing law and protection of font software under Indian law remain unresolved | Medium |
| FND-09 | Packaging and social | Printed and static outputs use the two brand fonts | Low |
| FND-10 | Internal documents | Installation count and sharing of editable presentations require clarification | Low |

These are **illustrative review issues, not findings of infringement or compliance**. Priority labels are provisional and would need to be reassessed against the actual licence, evidence and circumstances.

See [`docs/preliminary-audit-report.md`](docs/preliminary-audit-report.md) for the detailed analysis.

## 7. Key Legal Questions

- **Licence scope:** Does the relevant agreement authorise the particular use, distribution method, number of users or volume of usage?
- **Indian copyright law:** Section 51(a) of the Copyright Act, 1957 addresses acts done without a licence or in contravention of licence conditions, where copyright subsists in the relevant work. The applicability of this provision depends on the facts and legal status of the material involved.
- **Font software and typeface design:** Whether a particular font file qualifies for copyright protection as a computer programme, and how the law applies to the underlying typeface design, require careful analysis. This project does not claim to resolve those questions.
- **Digital delivery versus static output:** Delivering a font file through a website or application may raise different licence questions from using a font in a flattened image or printed design.
- **Governing agreement:** The actual purchase documents, licence terms, applicable version and any negotiated conditions must be identified before reaching a reliable conclusion.

## 8. Limitations and Assumptions

- NovaWear and its circumstances are fictional.
- The review is based on limited reference-document research, not a complete examination of every relevant licence provision.
- No private licence, order form, invoice, purchase record or account record was inspected.
- RF-B is undated, and whether it is currently issued has not been confirmed.
- No link-validation script was run; URLs were opened individually during research.
- The analysis does not establish infringement, compliance, liability or a real company's licensing position.

These limitations are part of the exercise: identifying what is unknown is an important part of responsible legal review.

## 9. Ethical Boundaries

- NovaWear is fictional and was created for this exercise.
- “Brand Sans”, “Brand Display” and “Script Accent” are labels for fictional typefaces, not identified commercial products.
- No real company is accused of infringement or described as a Monotype customer.
- Third-party licence provisions are summarised rather than reproduced at length; readers should consult the original documents.
- This is a student research project, not a professional audit or evidence of employment or engagement by a font company.

## 10. Using the Templates

1. **Licence verification:** Start with [`templates/licence-verification-checklist.md`](templates/licence-verification-checklist.md) when the actual licence documents are available.
2. **Use-case mapping:** Complete [`templates/use-case-matrix.csv`](templates/use-case-matrix.csv), using one row per channel.
3. **Evidence tracking:** Record documents received and requested in [`templates/evidence-register.csv`](templates/evidence-register.csv).
4. **Findings tracking:** Use [`templates/findings-register.csv`](templates/findings-register.csv) to record issues, supporting material, priority and outstanding questions.
5. **Before real-world use:** Remove illustrative data and validate the template against the actual matter, applicable law and licence documents.

The CSV files are intended to open in spreadsheet software such as Excel, Google Sheets or LibreOffice.

## 11. Licence for This Repository

The author's original text and templates are released under **Creative Commons Attribution 4.0 International (CC BY 4.0)**, subject to the terms of the included [`LICENSE`](LICENSE) file. Third-party material referred to in the project, including Monotype's licence terms and statutory text, is not covered by that licence.
