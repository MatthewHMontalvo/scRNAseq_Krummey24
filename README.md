This project analyzes single-cell RNA-seq data from heart transplant samples to characterize immune cell populations and transcriptional programs associated with acute rejection versus tolerance. A particular emphasis is placed on T cell subsets, including CD8⁺ T cells, given their central role in graft rejection.

**Data Type**

-Single-cell RNA-seq (scRNA-seq)

-Heart transplant tissue samples

-Experimental conditions: Acute Rejection (AR) vs Tolerance (Tol)

**Methods and Tools**

-R / RStudio

-Seurat for scRNA-seq preprocessing and clustering

-SingleR for cell type annotation

-Differential gene expression analysis between conditions and clusters

-Visualization using UMAP, violin plots, and feature plots

**Workflow Summary**

1. Quality control and filtering of single cells

2. Normalization and scaling

3. Dimensionality reduction (PCA, UMAP)

4. Cell clustering and annotation

5. Subsetting immune populations (e.g., CD8⁺ T cells)

6. Differential expression and pathway-level interpretation
