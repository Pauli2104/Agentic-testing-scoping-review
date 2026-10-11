# The Agent Explores, the Tester Decides

Replication package for the scoping review **“The Agent Explores, the Tester Decides: A Scoping Review of Agentic AI and Human Responsibility in Feature-Level Software Testing”** by Paula Otaño (Systems Engineering Department, UTN – Córdoba Regional Faculty) and Cristian Rodriguez Rivero (Mechatronics Department, Fontys University of Applied Sciences). Submitted to *Information and Software Technology*.

## Contents

| Path | Description |
|---|---|
| `manuscript/` | LaTeX source (Elsevier `elsarticle`), bibliography and graphical abstract |
| `docs/search_strings.md` | Exact search string for each of the seven sources |
| `docs/PRISMA-ScR_checklist.docx` | Completed PRISMA-ScR checklist |
| `docs/PRISMA_2020_flow_diagram.docx` | PRISMA 2020 flow diagram |
| `data/00_prisma_counts.csv` | Counts behind the flow diagram |
| `data/01_records_retrieved.csv` | All 1,900 exported records with the deduplicated id they map to |
| `data/02_title_abstract_screening.csv` | Decision, exclusion code and reason for the 1,841 screened records |
| `data/03_fulltext_eligibility.csv` | Eligibility decisions for the 136 reports assessed |
| `data/04_charting_included_sources.csv` | Charted data for the 64 included sources |

Abstracts are not redistributed because they remain under publisher copyright; each record carries a DOI or arXiv identifier.

## Method in brief

Seven sources (IEEE Xplore, ACM Digital Library, ScienceDirect, Wiley Online Library, SpringerLink, Taylor & Francis Online, arXiv), January 2015 – 15 September 2026, plus backward snowballing. Screening was assisted by a large language model and verified by two reviewers (first author vs model: agreement 90.0%, Cohen’s κ = 0.80; second reviewer vs final decisions: agreement 83.7%). Exclusion codes E1–E11 are defined in Section 4.3 of the manuscript.

## Building the manuscript

```
cd manuscript
pdflatex Otano_IST_manuscript
bibtex Otano_IST_manuscript
pdflatex Otano_IST_manuscript
pdflatex Otano_IST_manuscript
```

## Citation

See `CITATION.cff`. Until the article is published, please cite this repository.

## License

Data and documentation: CC BY 4.0 (see `LICENSE`).
