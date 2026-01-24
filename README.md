# Exploratory Transcriptomic Analysis of Allergic Rhinitis

This repository contains an exploratory re-analysis of publicly available
microarray gene expression data examining pathway-level immune signals and
molecular heterogeneity in allergic rhinitis.

The work is intentionally exploratory and hypothesis-generating. It does not
introduce new experimental data, clinical claims, or diagnostic assertions.

## Contents

- `analysis/`  
  Jupyter notebook used for data loading, preprocessing, statistical testing,
  and visualization.

- `figures/`  
  Figures generated from the analysis, including differential expression and
  variance comparisons.

## Pathway-level summary
| Pathway                                           | Direction of aggregate signal                                              | Evidence derived from analysis                                                                                                                                                                |
| ------------------------------------------------- | -------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Cytokine–cytokine receptor interaction            | Predominantly positive log2 fold-change among nominally significant probes | Multiple probes mapping to cytokine and cytokine-receptor genes showed nominal differential expression (unadjusted p < 0.05), with effect sizes clustered near zero but biased away from null |
| NF-κB signaling                                   | Predominantly positive log2 fold-change                                    | Nominally significant probes mapped to genes within NF-κB-related signaling cascades; observed signals were modest in magnitude and distributed across probes                                 |
| Th1/Th2 differentiation                           | Predominantly positive log2 fold-change                                    | Probes associated with Th1/Th2 differentiation pathways demonstrated nominal differential expression consistent with immune polarization patterns                                             |
| Epithelial adhesion and barrier-related processes | Mixed directionality across probes                                         | Probes mapping to epithelial adhesion and barrier maintenance genes showed both positive and negative log2 fold-changes, with no consistent directional bias                                  |
| Cell cycle (negative control)                     | No enrichment detected                                                     | Probes mapping to cell-cycle-related pathways did not show clustering of nominal significance beyond background levels                                                                        |

- `data/`  
  Information on the publicly available datasets used.

## Data Source

Gene Expression Omnibus (GEO):  
GSE19187  
https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE19187

All data used are publicly available and de-identified.

## Scope and Limitations

This analysis is exploratory in nature and intended to characterize signal
structure and heterogeneity within existing data. Findings should be interpreted
as hypothesis-generating and not as confirmatory or clinically actionable.

## License

- Code: MIT License  
- Manuscript and figures: CC BY 4.0

