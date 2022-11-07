# Dynamic_NicheNet

**Abstract**  
Despite the development and evolution of the single-cell RNA sequencing (scRNA-seq) technology, the generation of time-series scRNA-seq data is highly expensive, thus rarely studied. Currently, there is no method or work developed to study intercellular communication in this type of data. Therefore, we aim to develop an extension of NicheNet for time-series single-cell RNA sequencing data using a pseudobulk approach. The pseudobulk approach helps the study of single-cell data at sample-level, in which a sample indicates a time point in time-series single-cell data. Analysing this pseudobulk count matrix allows identification of differentially expressed genes across time. The differentially expressed genes reflect biological activation in response to external stimuli or ligand, known to be involved in intercellular communication. Given the group of genes that exhibit similar temporal patterns as target genes of interest, NicheNet predicts active ligands and further enables the study of intercellular communication on ligand-to-target level. In this method, we 1) revealed the temporal trends of ligands and targets in specific cell types, 2) identified the most crucial target genes across time in a given receiver cell type, 3) identified the most probable sender cell population for a significantly active ligand-target pair, and 4) constructed a dynamic network across time of intercellular communication. All discussed steps in this method are demonstrated by in-house data, reflecting the gene expressions in the process of liver regeneration stimulated by partial hepatectomy of mice.

scripts
  - Data_Exploration.rmd
  
  - DE_pseudobulk_DecontX.rmd
  - Dynamic_NicheNet_pseudobulk_DecontX.rmd
  
  - DE_pseudobulk_clusterPerCelltype.rmd
  - Dynamic_NicheNet_pseudobulk_clusterPerCelltype.rmd
  
  - Gene_interaction_cascades.rmd
  
Data
  - NicheNet v2.0 **Ligand-Target matrix and Networks** ([https://zenodo.org/record/5884439#.Yk2JcMhBxPZ](https://zenodo.org/record/5884439#.Yk2JcMhBxPZ))
  - Download prior models in the link above
  - Liver regeneration dataset (Seurat object) could not be uploaded due to large file size.
