# Unofficial LaTeX Template for Mahidol University Graduate Studies

A LaTeX template for theses, thematic papers, and independent studies at the Faculty of Graduate Studies, Mahidol University. Updated for PR07284 (B.E. 2569 / 2026).

## Which template should I use?

| Study Plan | Format | File |
|---|---|---|
| Thesis | Traditional (6 chapters) | `main-thesis-traditional.tex` |
| Thesis | Publication-based | `main-thesis-publication.tex` |
| Thematic Paper | Traditional | `main-thematic-traditional.tex` |
| Thematic Paper | Publication-based | `main-thematic-publication.tex` |
| Independent Study | Traditional | `main-independent-traditional.tex` |
| Independent Study | Publication-based | `main-independent-publication.tex` |

**Notes:**
- The 6-chapter structure (Introduction, Literature Review, Research Methodology, Results, Discussion, Conclusion and Recommendations) is mandatory only for Thesis Traditional Format.
- Thematic Paper and Independent Study follow the basic Traditional Format structure, but the number of chapters and level of detail are at the discretion of the advisor and examination committee.
- Publication-based Format requires at least one published or accepted publication. Publisher permission evidence must be included in the appendix.

## Files

- `muthesis2026.cls` — The class file. Provides `\thesisplan`, `\thematicplan`, and `\independentstudyplan` commands.
- `preamble.tex` — Shared metadata (student info, advisor info, committee, biography). Edit this first.
- `references.bib` — BibTeX database.
- `figures/` — Place figures here.

## How to compile

```bash
latexmk -pdf main-thesis-traditional.tex
```

Or compile with your preferred LaTeX editor (Overleaf, TeXShop, VS Code + LaTeX Workshop, etc.).

## Final submission (PR07284 requirements)

- Output must be a single PDF/A file with all fonts embedded.
- A4 page size.
- Signature fields left blank for initial e-Thesis upload.
- Turnitin similarity report prepared (core content ≤ 25%).
- Biography appears as the final page.
- Confirm dissemination rights with your major advisor.

## History

- 2026: Updated for PR07284. Added support for Thesis/Thematic Paper/Independent Study plans with Traditional and Publication-based formats. (Thanapon Noraset)
- 2023: hyperref support. (Phaphontee Yamchote)
- 2021: Updated format per FGS instructions. (Thanapon Noraset)
- 2017: Initial version. (Angkana Huang)
- 2009: Original class file. (Ekasit Kijsipongse, based on Michael A. Allen's 2006 work)
