# Preliminary Audit Report: NovaWear Font Usage

**Simulated preliminary legal review. NovaWear and every fact about it are fictional.**

| | |
|---|---|
| Subject | Font use across eight channels by NovaWear (fictional) |
| Nature of document | Preliminary legal review, not a completed audit (see [methodology.md](methodology.md), section 1) |
| Research date | 29 October 2026 |
| Reference frameworks | RF-A: Monotype License and Service Terms, Version 2.0. RF-B: Monotype Font Software EULA (legacy single-user form). Neither is known to govern NovaWear. |
| Companion files | [clause-by-clause-review.md](clause-by-clause-review.md), [use-case matrix](../templates/use-case-matrix.csv), [evidence register](../templates/evidence-register.csv), [findings register](../templates/findings-register.csv) |

---

## 1. Scope

This report asks, for each channel in which NovaWear uses fonts, whether the use is the kind of use a font licence would need to cover, what such a licence would typically require, what NovaWear has shown so far, and what it still needs to show. It does not decide whether any use is licensed. It cannot: NovaWear has not produced a licence.

Out of scope: valuation of any licence shortfall, negotiation with any licensor, technical forensic analysis of font files, and the law of any country other than India except where a licence document points to it.

## 2. The fictional scenario

### 2.1 The company (hypothetical facts)

NovaWear is a fictional Indian direct-to-consumer apparel brand with about 60 employees. It sells through its own website and mobile app and through a small number of retail partners. Design work is shared between a two-person in-house design team and an external creative agency ("Agency A"). Packaging is printed by an external printer ("Printer P").

### 2.2 The fonts (hypothetical facts)

| Ref. | Label | Role in brand guidelines | What NovaWear says about its source |
|---|---|---|---|
| F1 | Brand Sans (four styles: Regular, Medium, Bold, Italic) | Body text everywhere: packaging, website, app, ads, decks | "Bought years ago" by a former designer; believed to be from Monotype or MyFonts |
| F2 | Brand Display (one style) | Headlines on packaging, hero banners, ads | Same as F1 |
| F3 | Script Accent (one style) | Festive packaging and seasonal social ads | Downloaded "from a free fonts website" by a former intern |

These are labels for fictional typefaces. They do not refer to any real product.

### 2.3 Evidence position (hypothetical facts)

**Received:** brand guidelines (EV-01); an email from the Head of Marketing about the font purchase (EV-02); a CSS extract from the website and the web developer's statement (EV-03); a listing and sharing-settings screenshot of the shared font folder (EV-04); Agency A's statement of work (EV-05); the app developer's statement (EV-06); campaign samples (EV-07); print-ready packaging PDFs (EV-08); a sample internal deck (EV-09).

**Not received:** any licence, order form, invoice or receipt (EV-10); an installation inventory (EV-11); web traffic (EV-12), app user (EV-13) and email or ad volume (EV-14) data; Agency A's own licences (EV-15); the source and licence of F3 (EV-16); access logs and member lists for the shared folder and design-tool workspace (EV-17).

Every evidence item is client-supplied and unverified. Full details are in the [evidence register](../templates/evidence-register.csv).

## 3. Legal framework in brief

### 3.1 Contract

NovaWear's rights depend on the licence it actually accepted, read with any order form, receipt, amendment or account record. Possible sources include a Monotype subscription (RF-A-type terms with an order form), a legacy Monotype desktop licence (RF-B-type terms), a MyFonts purchase under a foundry's EULA, a licence held by Agency A, a font bundled with other software, or an open licence such as the SIL OFL. Each produces a different answer.

Both reference frameworks reserve every right not expressly granted (RF-A §2 opening; RF-B §2 and §7). The question in each use case is therefore whether an express grant covers the act.

### 3.2 Indian copyright law

- **If copyright subsists in the font file** as a computer programme (Copyright Act, 1957, s. 2(ffc) read with s. 2(o) and s. 13(1)(a)), then copying and issuing copies of the file are exclusive rights of the owner (s. 14(b)), and acting outside a licence's conditions can be infringement (s. 51(a)(i)).
- **The typeface design** (the shapes of the letters) is generally said by Indian commentators to be outside the Copyright Act (s. 2(c), s. 16), with possible design protection under the Designs Act, 2000 (s. 15 of the Copyright Act). This is secondary-source analysis; no Indian judgment was verified on either point.
- **Practical consequence:** uses that send the font file to others (website, app, HTML email, open cloud links) raise contractual questions *and* potential copyright questions. Uses that only produce printed or flat images raise mainly contractual questions.

### 3.3 Governing law

RF-B places governing law in separate Monotype terms that were not reviewed (§12). RF-A's governing-law provision falls in sections that were not retrieved. The forum and law that would apply to any dispute are unknown (FND-08).

---

## 4. Use-case analysis

### UC-01: Product packaging

**A. What NovaWear is doing.** The in-house team and Agency A design hang tags, boxes and mailer bags using F1 and F2 throughout and F3 on the festive range. Print-ready PDFs go to Printer P.

**B. Rights potentially relevant.** Installing fonts on design workstations; creating and printing materials; supplying print files with embedded fonts to a commercial printer.

**C. Verified provisions.**
- RF-A §2.B.1 (install on licensed users' workstations); §2.B.3(i) (create, print and distribute materials that do not contain the font software); §2.B.3(ii) (embed in non-commercial electronic documents, non-extractably).
- RF-B §2 and §13 ("Personal or Internal Business Use" excludes only distribution of the font software); §5 (printer may receive embedded documents for printing only, or a copy of the font if the printer holds its own licence); §13 ("Basic Licensed Unit" is one workstation and one printer).
- F3: no licence located. If F3 is under SIL OFL 1.1, commercial use and embedding are permitted (OFL permission paragraph; condition 5).

**D. Available evidence.** EV-01 names F1, F2 and F3 for packaging. EV-08's document properties list embedded subsets of all three fonts. EV-02 asserts a purchase but gives no detail.

**E. Missing evidence.** Licence for F1 and F2 (EV-10); number and identity of workstations with the fonts installed (EV-11); Printer P's licence position; the source, date and licence file for F3 (EV-16).

**F. Conclusions.**
- *Can conclude:* For F1 and F2, printed packaging is output, and both reference frameworks permit creating and printing materials from a licensed installation, provided the distributed product does not contain the font software. Printed boxes do not. Supplying embedded PDFs to a printer for printing is anticipated by RF-B §5 and is consistent with RF-A §2.B.3(ii).
- *Cannot conclude:* whether the installations used to create the artwork are themselves licensed (the seat count is unknown), whether Printer P holds its own licence, or whether F3's licence permits commercial use. Insufficient evidence to conclude on any of these.

**G. Follow-up questions.**
1. Which licence covers each workstation on which F1 and F2 are installed?
2. Where and when was F3 downloaded, and was a licence file included?
3. Did NovaWear or Agency A send Printer P the font files themselves, or only PDFs?

**H. Possible steps.** Locate the F1/F2 licence and reconcile it with an installation inventory. For F3, recover the original download and licence text. If F3's licence does not permit commercial use, or provenance cannot be established, take counsel's advice before the next print run on whether to license properly or substitute a font; treat stock already printed as a separate question for counsel.

**I. Priority.** F1/F2: **Low** (output-only use of a permitted kind; the open point is seat count). F3: **Medium** (unknown provenance on a product sold to the public; quick to resolve with the download record).

Findings: FND-07, FND-09.

---

### UC-02: Public website

**A. What NovaWear is doing.** The website's CSS uses `@font-face` rules to load `brandsans-regular.woff2` and `brandsans-bold.woff2` from NovaWear's own content delivery network. Every visitor's browser downloads these files. The web developer states that the WOFF2 files were "converted from the OTF files in the shared drive". F2 appears on the site only inside hero images.

**B. Rights potentially relevant.** Hosting font files on a server; delivering copies to visitors' browsers; creating web-format files; volume measured by page views.

**C. Verified provisions.**
- RF-A §2.C.iv (web page content up to Licensed Page Views; only Production Fonts); Section 1 definitions of "Page View", "Licensed Page View", "Font Software" (includes web-font copies) and "Derivative Work" (includes format conversion); §2.A.i.3 (web subsets made with Monotype's Subsetter Application).
- RF-B §2 (internal use only, no distribution of font software); §6 (no alteration of embedding bits); §7 (no further distribution); §9 (no converting or creating derivative works).

**D. Available evidence.** EV-03 (CSS extract and developer's statement). EV-04 shows OTF files of F1 in the shared drive, consistent with the developer's account.

**E. Missing evidence.** Any web licence for F1 (EV-10); monthly page views (EV-12); the original files used for conversion and the tool used; whether the licence (if any) allows self-hosting.

**F. Conclusions.**
- *Can conclude:* The website does not merely display F1; it distributes copies of F1 to every visitor. That is a different act from desktop use. Under RF-A it would require a web grant measured in page views; under RF-B there is no grant that could cover it, and the conversion step itself conflicts with §9. If NovaWear holds only a desktop-type licence, there is a **potential scope mismatch**. If copyright subsists in F1 as a computer programme, the copies served to visitors would engage s. 14(b) of the Copyright Act, so any scope gap would carry potential infringement risk under s. 51(a)(i), not only contractual risk. The s. 52(1)(aa) exception is unlikely to help, because it covers adaptation for the purpose for which the programme was supplied.
- *Cannot conclude:* that NovaWear lacks a web licence. One may exist (for example, bought by the web developer). Requires licence verification.
- F2 in hero images is output only; see UC-04.

**G. Follow-up questions.**
1. Does NovaWear, its web developer or any agency hold a web-font licence for F1? Who bought it and when?
2. What are the site's average monthly page views over the last 12 months?
3. Who converted the files, from which source files, with which tool, and when?

**H. Possible steps.** First, preserve the evidence (capture the live CSS, response headers and file hashes; see the evidence guide). Do not delete or replace the files until counsel has seen the evidence, as the history of what was served may matter. Then, depending on the licence position: obtain a web licence at the correct page-view tier and replace converted files with licensor-supplied web files; or move the site to a font whose licence permits web use (for example an OFL font, with the licence notice kept with the files).

**I. Priority.** **High.** The use distributes the font file to the public, the reference frameworks treat it as a separate grant, no licence for this channel has been located, and the converted files raise a further question under both frameworks.

Finding: FND-01.

---

### UC-03: Mobile application

**A. What NovaWear is doing.** The in-house Android and iOS shopping app bundles F1 in the app package, according to the app developer (EV-06). Every installation and update delivers a copy of F1 to the user's device.

**B. Rights potentially relevant.** Embedding font software in an application and distributing it to end users; volume measured by registered users.

**C. Verified provisions.**
- RF-A §2.C.i (incorporate Production Fonts non-extractably into Licensed Applications; no end-user authoring; distribute up to the number of Registered Users); Section 1 definitions of "Application" and "Registered User".
- RF-B §2 and §7 (no distribution of font software; no grant for applications).

**D. Available evidence.** EV-06 (developer's statement; public store listings).

**E. Missing evidence.** Any application licence (EV-10); the app package's font file list; downloads and registered users (EV-13); whether the files are protected against extraction.

**F. Conclusions.**
- *Can conclude:* Bundling F1 in the app distributes the font file with every download. Neither a desktop grant under RF-A nor any grant under RF-B covers this. If NovaWear holds only a desktop-type licence, there is a **potential scope mismatch**. RF-A's definition of "Registered User" counts downloads and updates, so the relevant volume could be large even if active use is low.
- *Cannot conclude:* whether an application licence exists, or whether the user count would fall within any licensed tier. Insufficient evidence to conclude.

**G. Follow-up questions.**
1. Is there an application licence for F1, and for how many apps and users?
2. How many unique users have downloaded, updated or registered on the app?
3. Is F1 stored in the package in a form that can be extracted without special tools?

**H. Possible steps.** Preserve a copy of the current app packages and their file lists. Pending the licence position, consider whether the next release can use system fonts or an OFL font in place of F1, with the OFL notice included in the app's legal notices. Any licensing discussion with a licensor should go through counsel.

**I. Priority.** **High.** Public distribution of the font file at scale, a separate grant under RF-A, no grant under RF-B, and no licence located.

Finding: FND-02.

---

### UC-04: Social media advertisements

**A. What NovaWear is doing.** Static images and short videos for paid social campaigns, produced by the in-house team and Agency A, using F1, F2 and (seasonally) F3. Files are exported as flat PNG and MP4 files.

**B. Rights potentially relevant.** Creating and distributing materials that do not contain font software.

**C. Verified provisions.** RF-A §2.B.3(i) (distribution of materials not containing font software; no substitute glyph sets built from static images); RF-A §2.A.iii.3 (if Agency A works under its own prototyping-level subscription, public distribution needs a separate licence). RF-B §3 (static images may be embedded even in commercial products if they do not replace individual glyphs).

**D. Available evidence.** EV-07 (three static ads).

**E. Missing evidence.** Which workstations produced the ads and whether they are licensed (EV-11); Agency A's licences (EV-15); F3's licence (EV-16).

**F. Conclusions.**
- *Can conclude:* The ads are flat images and video. They contain no font software and are not glyph substitutes. This is the kind of output both reference frameworks permit from a licensed installation.
- *Cannot conclude:* whether the installations used were licensed, or, for Agency A's work, under whose licence it was done. Insufficient evidence to conclude. F3 is dealt with under UC-01 and FND-07.

**G. Follow-up question.** For each campaign, who produced the artwork and on which licence?

**H. Possible step.** Include ad production in the installation inventory; ask Agency A to confirm its licence position in writing (see UC-06).

**I. Priority.** **Low** for F1 and F2 (output only). F3 is rated Medium under FND-07.

Finding: FND-09.

---

### UC-05: Digital marketing campaigns

**A. What NovaWear is doing.** Monthly HTML email newsletters whose template references F1 as a web font loaded from NovaWear's server, and HTML5 display banners built by Agency A.

**B. Rights potentially relevant.** Delivering font software inside emails and display ads; volume measured by impressions (ad responses or opened emails).

**C. Verified provisions.** RF-A §2.C.v (Digital Marketing Communications up to Licensed Impressions); Section 1 definitions of "Digital Marketing Communication" and "Impression" (an opened email to which the font is delivered counts). The "Electronic Document" definition expressly excludes Digital Marketing Communications, so the document-embedding rights in §2.B.3(ii) do not apply. RF-B contains no relevant grant.

**D. Available evidence.** EV-07 (newsletter HTML template; one HTML5 banner package).

**E. Missing evidence.** Whether the banners embed or load a font file or use outlined text or images (technical check of the banner package); email open counts and ad impressions (EV-14); any digital-ad licence (EV-10); whether Agency A licensed fonts for the banners (EV-15).

**F. Conclusions.**
- *Can conclude:* If F1 is delivered to email clients and ad viewers as a font file, RF-A treats that as a separate grant measured in impressions. A desktop grant would not cover it.
- *Cannot conclude:* whether a font file is in fact delivered. Many email clients do not load web fonts and many banners use outlined text; the samples need checking. Insufficient evidence to conclude.

**G. Follow-up questions.**
1. Does the banner package contain or request a font file?
2. How many newsletters were opened and how many banner impressions were served in the last 12 months?

**H. Possible steps.** Run the technical check on EV-07. If no font file is delivered, record that and downgrade to Low. If one is, verify licence coverage or move emails and banners to a fallback system font or an appropriately licensed alternative.

**I. Priority.** **Medium.** Possibly a separate licensable channel, but a simple technical check may resolve it.

Finding: FND-05.

---

### UC-06: Agency-created artwork

**A. What NovaWear is doing.** NovaWear's statement of work with Agency A says the client will supply brand fonts. NovaWear shared the F1, F2 and F3 OTF files with Agency A through a link to the shared drive folder. The number of agency staff with access is unknown.

**B. Rights potentially relevant.** Third parties using fonts on the licensee's behalf; sublicensing; transfer or lending of font files.

**C. Verified provisions.**
- RF-A Section 1, "Licensed Desktop User" (employees of an agency engaged by the customer may be licensed users; the customer is responsible for them; all who can potentially use the fonts are counted); §2.B heading paragraph (a Company Desktop License must cover all sublicensees with access); §2.E.2 (sublicensing to agencies working solely for the customer, counted against licensed numbers, sublicensee bound by all terms, customer fully responsible).
- RF-B §7 (no giving, lending, sublicensing or further distribution except as expressly provided); §5 (the only express third-party exception is the commercial printer); §13 (authorised agents may use the fonts, but within the Licensed Unit).

**D. Available evidence.** EV-05 (statement of work); EV-04 (sharing settings showing the link was shared externally).

**E. Missing evidence.** NovaWear's licence and seat count (EV-10, EV-11); Agency A's own licences and whether it retained the files after projects ended (EV-15); the list of agency users with access (EV-17).

**F. Conclusions.**
- *Can conclude:* Sharing font files with an agency is not, by itself, outside every licence. RF-A expressly contemplates it, provided each agency user is counted and bound. RF-B is narrower: it lets agents use the fonts on licensed equipment but restricts giving copies to others.
- *Cannot conclude:* whether NovaWear's seat count covers the agency users, or whether Agency A had its own licence (which could change the analysis for both UC-04 and UC-05). This is a **documentation gap**.

**G. Follow-up questions.**
1. How many Agency A staff received or could access the files?
2. Does Agency A hold its own licence for F1, F2 or F3, and on what terms?
3. Has Agency A deleted the files at the end of each project?

**H. Possible steps.** Ask Agency A for a written statement of its licence position and file retention. Going forward, add a font clause to agency contracts covering which party licenses fonts, how many agency users may access them, and deletion on completion. Stop sharing font files by open link.

**I. Priority.** **Medium.** May be covered depending on the licence; resolvable through a short exchange with the agency.

Finding: FND-06.

---

### UC-07: Cloud-based design files

**A. What NovaWear is doing.** A shared drive folder "Brand Assets/Fonts" holds the OTF files for F1, F2 and F3. Its sharing setting is "anyone in the organisation with the link". The fonts have also been uploaded to a team workspace on a browser-based design tool, where any team member can use them.

**B. Rights potentially relevant.** Storing font files on servers or cloud services; making them available to users; collaborative cloud authoring.

**C. Verified provisions.**
- RF-A Section 1, "Server" (cloud upload allowed only if files cannot be downloaded except by licensed users); §2.B.2 (server installation allowed only where access is restricted to licensed desktop users); §2.B heading paragraph and the "Licensed Desktop User" definition (count everyone who can potentially use the fonts); §2.B.5 (collaborative cloud authoring lets non-licensed people view and edit a document, not obtain the font).
- RF-B §4 (server use only if every workstation that can access the server is in the Licensed Unit; count all workstations that use the font at any time); §7 (no further distribution); §8 (one backup copy under exclusive control).

**D. Available evidence.** EV-04 (folder listing and sharing-settings screenshot).

**E. Missing evidence.** Access logs and the list of people who can open the folder (EV-17); the design-tool workspace member list (EV-17); the licensed seat count (EV-10, EV-11); the design tool's own terms on uploaded fonts (not reviewed).

**F. Conclusions.**
- *Can conclude:* Under both reference frameworks, the question is who **can** access the fonts, not who actually did. An organisation-wide link makes every NovaWear employee, and anyone else holding the link, a potential user. Unless NovaWear's licence covers that number, there is a **potential scope mismatch**. RF-A §2.B.2 is explicit that server installation is not permitted where access cannot be restricted to licensed users.
- *Cannot conclude:* the size of any gap, or whether an enterprise-level licence already covers it. Requires licence verification.

**G. Follow-up questions.**
1. Who can currently open the folder and the design-tool font library, and who has opened them?
2. Has the link ever been shared outside NovaWear (it was shared with Agency A; see UC-06)?

**H. Possible steps.** Export access logs and capture sharing settings first. Then restrict the folder and workspace to named licensed users. Restricting access, once recorded, does not destroy evidence and reduces exposure going forward. Use a font-management process that issues fonts to named users rather than an open folder.

**I. Priority.** **High.** It affects the seat count for the whole organisation, involves possible external access, and both reference frameworks address it directly. It is also the cheapest issue to contain.

Finding: FND-03.

---

### UC-08: Internal documents and presentations

**A. What NovaWear is doing.** F1 is installed on an unknown number of staff laptops for decks, reports and spreadsheets. Some decks, saved with embedded fonts in editable PowerPoint format, are sent to retail partners.

**B. Rights potentially relevant.** Desktop installation; embedding fonts in electronic documents; recipients editing with embedded fonts.

**C. Verified provisions.** RF-A §2.B.1; §2.B.3(ii) (non-commercial electronic documents, fonts not extractable without a tool). RF-B §2; §3 (where recipients can edit with the embedded font, they must be within the Licensed Unit); §13 ("Basic Licensed Unit" is a single workstation).

**D. Available evidence.** EV-09 (sample deck).

**E. Missing evidence.** Number of installations (EV-11); how decks are shared externally and in what format.

**F. Conclusions.**
- *Can conclude:* Internal use on licensed installations is the core of any desktop licence. Under RF-A, sharing non-commercial documents with embedded, non-extractable fonts is permitted. Under RF-B, sharing editable documents with external partners who are outside the Licensed Unit is not.
- *Cannot conclude:* whether the number of installations is covered. Insufficient evidence to conclude.

**G. Follow-up questions.** How many devices have F1 installed? Are decks sent to partners as PDF or as editable files?

**H. Possible steps.** Include laptops in the installation inventory. Share external decks as PDF unless editing is needed.

**I. Priority.** **Low.** Internal use is the expected use; the open point is the count, which is covered by FND-04.

Finding: FND-10.

---

## 5. Cross-cutting findings

### FND-04: No licence documentation or inventory (High)

NovaWear has produced no licence, order form, invoice, receipt, account record or installation inventory. Every channel-level conclusion above depends on these documents. RF-B §7 also shows that a licensor may require a business to document and certify its use within a short period. Assembling these records is the first task in the [remediation plan](remediation-plan.md). The [licence verification checklist](../templates/licence-verification-checklist.md) sets out what to extract from them.

The former designer named in EV-02 is a likely source of purchase records and should be asked, with appropriate care about the confidentiality of NovaWear's inquiry.

### FND-08: Governing law and Indian protection unresolved (Medium)

Two legal questions affect how serious any gap would be.

1. **Which law governs the licence?** Neither reference framework's governing-law clause was reviewed. A foreign governing law and forum would shape any dispute.
2. **Does Indian copyright protect the font file?** If a font file is a "computer programme" under s. 2(ffc), use outside licence conditions can be infringement under s. 51(a)(i). If not, the matter is likely to be contractual only in India. The interaction between s. 30A/s. 19 presumptions (five-year default term, India-only default territory) and a foreign-law clickwrap licence is also unresolved.

These are questions for qualified counsel. They do not change the evidence-collection steps.

---

## 6. Findings summary

| ID | Use case(s) | Fonts | Summary | Characterisation | Priority |
|---|---|---|---|---|---|
| FND-01 | UC-02 | F1 | Self-hosted, self-converted web font; no web licence or page-view data | Potential scope mismatch; requires licence verification | High |
| FND-02 | UC-03 | F1 | Font bundled in app; no application licence or user data | Potential scope mismatch; requires licence verification | High |
| FND-03 | UC-07 | F1, F2, F3 | Font files open to the whole organisation and shared externally | Potential scope mismatch | High |
| FND-04 | All | F1, F2, F3 | No licence, purchase record or inventory | Documentation gap | High |
| FND-05 | UC-05 | F1 | Web font possibly delivered in emails and HTML5 banners | Insufficient evidence to conclude | Medium |
| FND-06 | UC-06 | F1, F2, F3 | Font files given to agency; agency licence unknown | Documentation gap | Medium |
| FND-07 | UC-01, UC-04 | F3 | Free-download script font of unknown provenance on products and ads | Requires licence verification | Medium |
| FND-08 | All | — | Governing law and Indian copyright position unresolved | Open legal question | Medium |
| FND-09 | UC-01, UC-04 | F1, F2 | Printed packaging and flat ads | Output of a permitted kind; seat count unverified | Low |
| FND-10 | UC-08 | F1 | Internal installations and editable decks sent to partners | Documentation gap | Low |

## 7. Essential open questions

1. Which licence or licences govern F1 and F2, in which version, from which seller, and with what volumes? (FND-04)
2. Where did F3 come from and under what licence? (FND-07)
3. Who can access the font files today, inside and outside NovaWear? (FND-03, FND-06)
4. Does the website, app or marketing material deliver the font file itself, and at what volume? (FND-01, FND-02, FND-05)
5. Which law and forum govern the licence, and does Indian copyright protect the font file? (FND-08)

## 8. What happens next

The [remediation plan](remediation-plan.md) sequences the work: preserve and collect evidence first, verify the licence second, decide on remediation third, and escalate to qualified counsel where the licence position or legal exposure requires it. A completed audit would follow only once the governing documents are in hand.
