# 📜 Inferred UPTE TX Contract

> What does the former UPTE **TX** contract look like once the November 2025
> tentative-agreement packet is written into it?

This project answers that question. It takes the 2021 UPTE–UC TX contract
(as updated March 5, 2024) and applies each of the 16 documents in the
11-8-25 UC/UPTE tentative-agreement packet. The result is a reviewable
**inferred** successor contract with full traceability and an honest log of
what could not be determined.

> ⚠️ **This is not an executed or authoritative agreement.** It is an
> analytical reconstruction. Several documents the packet refers to were not
> available, and many changes are written for other bargaining units (HX, RX,
> NX). Where applicability or wording is uncertain, the text is kept and
> marked rather than guessed. Read the [issues log](UPTE_TX_inferred_issues.md)
> before relying on any provision.

---

## 🚀 Start here

| If you want to… | Open |
| --- | --- |
| Read the whole inferred contract | [New_UPTE_TX_contract_(inferred).md](<New_UPTE_TX_contract_(inferred).md>) |
| See what is unresolved and why | [UPTE_TX_inferred_issues.md](UPTE_TX_inferred_issues.md) |
| Trace any change back to its source | [UPTE_TX_inferred_traceability.md](UPTE_TX_inferred_traceability.md) |
| Edit or compare individual articles | [updating folder](TX-2021-Contract-Full_updated+mar+5+24_split_markdown_updating) |
| Check the new-change documents | [packet split](UPTE-UC+Final+Full+CLEAN+TA+11-8-25_split_markdown) |

---

## 🗂️ What's in this repository

```text
.
├── New_UPTE_TX_contract_(inferred).md      ← final assembled draft
├── UPTE_TX_inferred_issues.md              ← unresolved questions (28 sections)
├── UPTE_TX_inferred_traceability.md        ← per-document provision & file ledgers
├── source_documents/                       ← original, unmodified sources
│   ├── TX-2021-Contract-Full_updated+mar+5+24.{docx,pdf,md}
│   └── UPTE-UC+Final+Full+CLEAN+TA+11-8-25_.pdf
├── TX-2021-Contract-Full_updated+mar+5+24_split_markdown_updating/
│   └── article-01 … article-47, appendix-a … appendix-f   ← 53 working files
└── UPTE-UC+Final+Full+CLEAN+TA+11-8-25_split_markdown/
    └── 01 … 16 change documents + README
```

### Source documents

| Document | Role |
| --- | --- |
| `TX-2021-Contract-Full_updated+mar+5+24` | The **baseline**: former UPTE TX contract (DOCX, PDF and Markdown). [Original PDF at upte.org](https://upte.org/s/TX-2021-Contract-Full_updated-mar-5-24.pdf) |
| `UPTE-UC+Final+Full+CLEAN+TA+11-8-25_` | The **change packet**: 77-page PDF of the negotiated changes. [Original PDF at upte.org](https://upte.org/s/UPTE-UC-Final-Full-CLEAN-TA-11-8-25_.pdf) |

The copies in `source_documents/` are for convenience; the upte.org links are
the original published versions.

### The 16 change documents

| # | Subject | Typical scope |
| --- | --- | --- |
| 01 | Successor MOU (the umbrella agreement) | All units |
| 02 | Healthcare counterproposal and 2026–2028 subsidies | UPTE |
| 03 | Layoff (Article 16) | RX/TX |
| 04 | Layoff (Article 13) | HX |
| 05 | Transfer, promotion and reclassification (Arts. 41, 31) | UPTE |
| 06 | Remote work, MSP protections, differentials | Package |
| 07 | Vacation (Article 43) | RX/TX |
| 08 | Vacation (Article 42) | HX |
| 09 | Holidays (Article 12) | RX/TX |
| 10 | Holidays (Article 10) | HX |
| 11 | Pregnancy disability and childcaring leave excerpt | NX text, extended by MOU |
| 12 | Union access (Article 2) | HX |
| 13 | Physician assistant side letter | HX |
| 14 | Mediation wage proposal (July 2025 5%) | Candidate scales |
| 15 | Wage proposal with all ATBs | Candidate scales |
| 16 | UCLA PTO side letter | HX |

---

## 🧭 Methodology

1. **Baseline split.** The former contract was divided into 47 articles and
   6 appendices (53 files) so each could be reviewed on its own.
2. **Sequential review.** Change documents were handled strictly in order,
   01 through 16. For each one, **every one of the 53 files** was checked for
   relevance, then edited where the change applied.
3. **Visual verification.** The PDF contains redlines (insertions and
   strikethroughs) that text extraction loses. Documents with markup
   (notably 03, 05 and 07) were checked against page images so struck text
   was removed and inserted text kept.
4. **Scope rule.** Terms written only for HX (or another unit) are applied to
   TX **only when explicitly extended**. Otherwise they are recorded, not
   applied.
5. **Preserve, don't invent.** Where a source is missing, conflicting or
   ambiguous, the wording is retained with an inline
   `[Inference issue …]` marker linked to the issues log.
6. **One commit per document.** Each review is its own commit, with its
   provision ledger and a 53-file relevance matrix.
7. **Final audit.** Programmatic checks confirmed the assembled draft matches
   the split files exactly, all issue markers resolve to a log entry, and
   specific tables and excerpts match their sources.

---

## ✅ Results

| Measure | Outcome |
| --- | --- |
| Change documents reviewed | **16 of 16** |
| Contract files maintained | **53** (47 articles + 6 appendices) |
| Recorded relevance dispositions | **848** (16 × 53) |
| Inline issue markers | **28 distinct IDs** referenced in the contract |
| Healthcare subsidy values checked | 48 of 48 match source |
| Vacation accrual values checked | 16 of 16 match source |
| NX leave excerpt (doc 11) | Reproduced verbatim, matches source |

### Where the major changes landed

| Topic | Primary location |
| --- | --- |
| Compensation, ATBs, equity, $25 minimum wage | Article 6; Appendix A |
| Healthcare caps and subsidies (2026–2028) | Article 4 |
| Layoff | Article 16 |
| Reclassification, transfer, promotion | Articles 15, 16, 41, 46 |
| Remote work | Article 13 |
| Differentials | Article 38 |
| Holidays (incl. Juneteenth) | Article 12 |
| Vacation | Article 43 |
| Pregnancy disability and childcaring leave | Article 18 |
| Union access, orientation, representatives | Article 1 |
| Candidate wage tables (documents 14–15) | Appendix A, labelled as candidate material |

### Known limitations

Highlights; the [issues log](UPTE_TX_inferred_issues.md) has all of them.

- **Missing referenced materials**: seniority side letter, sick-leave,
  grievance and arbitration proposals, salary and equity allocations, and
  the full short-term union leave and training proposals were not in the
  packet.
- **Conflicts with existing terms**: new seniority rules versus Article 16,
  and holiday pay wording versus the Cesar Chavez exception.
- **Unit applicability**: wage tables for accreted titles (documents 14–15)
  have uncertain TX coverage and are labelled *candidate source material*.
- **HX-specific items**: the physician assistant and UCLA PTO side letters
  were not extended to TX because the sources do not say they apply.
- **Signatures**: document 16 shows blank signature lines in the PDF.

---

## 🔎 How to read an issue marker

Inside the contract you will see notes like:

```markdown
**[Inference issue TIT-01: The MOU does not identify the bargaining units
for these title-specific terms. …]**
```

Search the ID (here `TIT-01`) in the [issues log](UPTE_TX_inferred_issues.md)
for the explanation, then in the
[traceability ledger](UPTE_TX_inferred_traceability.md) for the source
provision and PDF page.

## 🛠️ Reproducing or extending

- Edit the split files in the updating folder, not the assembled draft.
- The assembled draft is the 47 articles then six appendices, joined by
  `---` rules beneath its header. Regenerate it after any edit.
- Use `git diff --check` with trailing-space tolerance: the inherited
  Markdown uses trailing spaces for hard line breaks.
- Never modify `source_documents/`.
