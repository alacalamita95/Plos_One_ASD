# A joint complex network and machine learning approach for the identification of discriminative gene communities in autistic brain
## Antonio Lacalamita, Ester Pantaleo, Alfonso Monaco*, Loredana Bellantuono, Alessandro Fania, Marianna La Rocca, Tommaso Maggipinto, Sabina Tangaro, Nicola Amoroso, Roberto Bellotti

This is a codebase behind the analysis of the paper: "A joint complex network and machine learning approach for the identification of discriminative gene communities in autistic brain".
### Files Provided:

#### 1. **Raw GEO Dataset** (`GSE28475-*-series_matrix.txt.gz`)
- **Source:** GEO Series GSE28475 ([NCBI GEO](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE28475))
- **Description:** Original expression datasetes from post-mortem frozen and fixed human brain tissues.
- **Format:** Compressed text file (`.gz`)

#### 2. **Preprocessed Dataset** (`GSE28475_Pre_Processed.RData`)
- **Format:** RData file
- **Dimensions:** 104 samples (33 ASD, 71 Control) × 18,630 genes
- **Preprocessing Steps:**
  - Quality control exclusion
  - Outlier removal
  - Log2 transformation
  - Quantile normalization
  - Batch effect correction
  - Covariate adjustments
- **Content:**
  - Rows: Subjects (identified by GSM IDs)
  - Columns: Genes (annotated with Gene Symbols)

## Citation
Please cite both the original GEO dataset (https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE28475) and the associated papers (https://doi.org/10.3389/fgene.2012.00011, https://doi.org/10.1186/1471-2164-12-449) when using this data.
