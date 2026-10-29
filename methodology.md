# Methodology

## 1. What kind of exercise this is

### Preliminary legal review versus completed audit

| | Preliminary legal review (this project) | Completed licence audit |
|---|---|---|
| Purpose | Identify where problems may lie and what evidence would resolve them | Establish, against the governing documents, whether each use is licensed |
| Inputs | Client statements, sample files, public documents | Executed agreement, order forms, invoices, amendments, account records, installation and usage data |
| Governing terms | Not yet identified; public standard terms used only as reference | Identified and read in the version in force at the relevant time |
| Facts | Partly known, largely unverified | Collected under a defined process and verified |
| Output | Issues list, evidence requests, priorities | Conclusions on each use, quantified gaps, remediation agreed |
| Conclusions | "Potential scope mismatch", "documentation gap", "insufficient evidence to conclude" | "Licensed", "not licensed", "licensed subject to condition X" |
| Who signs off | Supervising lawyer, with stated limits | Qualified counsel, often with technical input |

A preliminary review is the step before an audit. Its value lies in asking the right questions in the right order. It should not be read as a finding that any use is or is not lawful.

### Why public standard terms are only a reference

A public standard-form licence tells us what a licensor offers today. It does not tell us:

- whether the customer accepted that form or a different one;
- which version applied when the customer accepted it (licensors revise terms, and legacy licences may remain in force);
- whether an order form, bespoke agreement or amendment varies it;
- which fonts, how many users, which channels and what volumes were purchased;
- whether the fonts came from the licensor at all, rather than from a reseller, agency, bundled software or a free source.

The reference frameworks are therefore used to identify the questions a licence is likely to answer, not to supply the answers.

## 2. Sources and verification

### Hierarchy

1. Primary licence text published by Monotype, in the version actually opened.
2. Indian statute from India Code (Copyright Act, 1957, version "as on 15th June, 2026").
3. Other licensors' official texts, only where they help (SIL Open Font License 1.1, as a comparison and remediation option).
4. Secondary commentary (law firm articles, a WIPO submission), used for context and always labelled as secondary.

### Rules applied

- A provision is cited only if it was located and read. Where a document or part of a document could not be retrieved, that is recorded in [`sources-and-research-log.md`](sources-and-research-log.md) and nothing is inferred about its content.
- Clause references follow the numbering used in the source document. RF-A uses a mix of numbers, letters and roman numerals (for example, §2.C.iv); RF-B uses plain section numbers (§1 to §13).
- Licence provisions are summarised in plain language with a pinpoint citation. Direct quotation is kept to a few words and used only where the wording itself matters.
- Secondary sources are never used to establish what a statute or licence says.

### Labels used in the analysis

| Label | Meaning |
|---|---|
| **Verified source** | Text read in a cited source, summarised or briefly quoted |
| **Interpretation** | The author's reading of how a provision applies |
| **Hypothetical fact** | An invented fact about NovaWear |
| **Assumption** | A working premise that the evidence has not yet confirmed |
| **Open question** | A point that cannot be answered on present information |
| **Recommendation** | A suggested next step |

## 3. Analytical framework (A to I)

Each use case in the [preliminary audit report](preliminary-audit-report.md) and the [use-case matrix](../templates/use-case-matrix.csv) is analysed under the same nine headings.

| Step | Question | What a good answer looks like |
|---|---|---|
| A | What is the business doing? | A concrete description of the act (for example, "serves WOFF2 files from its own server to every visitor"), not just the channel name |
| B | Which rights or permitted uses may be relevant? | The type of permission involved: desktop installation, server hosting, web delivery, app embedding, document embedding, sublicensing |
| C | Which verified licence provision, if any, is relevant? | Pinpoint references to RF-A and RF-B, or a statement that no verified provision addresses the point |
| D | What facts and evidence are available? | Evidence IDs from the register, with a note on reliability |
| E | What evidence is missing? | Specific documents or data, not "more information" |
| F | What can and cannot be concluded? | Both halves stated separately |
| G | What follow-up question should be asked? | A question the client can actually answer |
| H | What remediation step may be appropriate? | Proportionate and sequenced; preservation before change |
| I | Priority and reason | Low, medium or high, with a reason tied to the scale below |

## 4. Priority scale

Priority reflects how urgently a point needs review, not a prediction of liability.

| Priority | Criteria |
|---|---|
| **High** | The use appears to involve distributing or hosting the font file itself to people outside a defined licensed group (website visitors, app users, an organisation-wide cloud link), and no licence covering that channel has been located; or the gap prevents any conclusion across channels. |
| **Medium** | The use may be covered depending on which licence applies; or it involves a third party or a font of unknown provenance; and targeted evidence could resolve it quickly. |
| **Low** | The use produces output only (printed matter, flat images, video) of a kind that both reference frameworks permit from a licensed installation, so the open point is the number of installations rather than the nature of the use. |

### Why the distinction between output and distribution matters

- Under both reference frameworks, desktop-type rights cover installing the font and creating materials with it. Distributing materials is generally permitted provided the materials do not contain the font software (RF-A §2.B.3(i); RF-B §2 read with the definition of "Personal or Internal Business Use" in §13).
- Web delivery, app bundling, HTML email and cloud hosting involve copies of the font file reaching other people's devices. RF-A treats each of these as a separate grant with its own volume measure (§2.C.i, §2.C.iii to §2.C.v). RF-B contains no web or app grant at all.
- Under Indian law, if copyright subsists in the font file as a computer programme, making and issuing copies of it engages the owner's exclusive rights (Copyright Act, s. 14(b) read with s. 14(a)(i) and (ii)). Printed output reproduces letter shapes, whose protection in India is doubtful. So distribution raises both contractual and potential infringement questions; output may raise only contractual ones.

## 5. Process followed

1. **Scoping.** Listed the eight channels named in the brief and the three fonts (all fictional).
2. **Research.** Located and read Monotype's current published terms, an older Monotype EULA, Monotype's licensing glossary and the Copyright Act, 1957. Checked secondary commentary on typeface protection in India. Recorded each source in the research log.
3. **Fact pattern.** Built a fictional evidence set (EV-01 to EV-09 received; EV-10 to EV-17 missing) reflecting what a brand with no licence records might plausibly hold.
4. **Analysis.** Applied steps A to I to each channel and recorded findings.
5. **Prioritisation.** Applied the scale above.
6. **Quality control.** Cross-checked every clause reference against the source text, checked that the report and CSVs use the same IDs, priorities and provisions, and confirmed that no file describes a real engagement.

## 6. Language conventions

The report uses these phrases with specific meanings:

| Phrase | Meaning |
|---|---|
| **Potential scope mismatch** | On the facts known, the use appears to fall outside the kind of grant the client is believed to hold |
| **Documentation gap** | The use may well be licensed, but nothing produced so far shows it |
| **Requires licence verification** | The answer depends on terms not yet seen |
| **Insufficient evidence to conclude** | No conclusion either way is possible yet |

Words such as "infringing", "unlicensed", "compliant" and "breach" are not used as conclusions anywhere in this project.
