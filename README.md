# Supplementary material: bottlenecks in IMU-based movement measurement

Supplementary material for the narrative review *Where Clinical Confidence Is Lost: Bottlenecks in the Measurement Chain of IMU-Based Human Movement Analysis* (ICORR 2027).

## Contents

| File | What it is |
| --- | --- |
| `material-suplementar.md` | S1 search strings, S2 record counts, S3 eligibility criteria, S4 screening flow and priority rule |
| `docs/index.html` | Same content as a web page (enable GitHub Pages on `/docs`) |
| `data/triagem.csv` | 166 records read at abstract level: id, DOI, title, year, source string, type, decision, criterion, priority |
| `data/consolidado.csv` | 29 articles extracted from full text, with measurement-chain link and main error |
| `data/resumo_por_elo.csv` | Counts of articles per link of the chain and per bottleneck |
| `diagram/arquivos-do-artigo.mmd` / `.svg` | Map of the files used to build the article (Mermaid source and image) |

## Notes

- Title and abstract screening was done with a large language model (Claude Sonnet 5.5) under criteria set and supervised by the author (see S4).
- Full texts and database exports are not included because of publisher and database terms. Records are identified by DOI.
- Some text fields in the CSV files are in Portuguese.

## License

Suggested: CC BY 4.0 for the documentation and data. Add a `LICENSE` file before publishing.
