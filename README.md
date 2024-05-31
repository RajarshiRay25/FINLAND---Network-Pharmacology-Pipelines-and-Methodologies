# FINLAND---Network-Pharmacology-Pipelines-and-Methodologies
Developing mechanistic workflows to understand the biological connection among various set of biological conditions and diseases to visualize the shared biological pathways and expressed phenotypes which correlate with their overall progression.
---

## Methodologies used to develop the Network Pharmacology workflow

1. Obtain Common Gene list among the selected biological conditions.
2. Set the reference biological condition or disease on whose parameters the genes and data will be referenced and mapped.
3. Create combinations of Genes-Chemicals-Phenotypes-Pathways-Interaction Types etc.
4. Create Frequency matrix to obtain the gene frequency for each types in the mentioned parameters.
5. Select the samples from the matrix having the maximum gene frequencies which will enable us to narrow down the biological interpretation.
6. Create Jaccard Index (JI) across gene pairs to visualise the content of parameters between them to select out the best genes and correlation.
7. Create Correlation Heatmaps to visually analyse the data.
8. Create Knowlege Graphs (KG) and Interaction Networks to visualise the mapped data to observe how each paramters link among each other and infer conclusions based on existing research.
9. KGs across all possible mapped combinations to create complex networks.
10. Perform gene enrichment and pathway analysis along with single cell and organ localisation analysis to obtain detailed activity details about the best correlated genes from above matrix.
11. Select the best genes which are causing the biological condition and obtain bioactive candidates from drug databases and create a ML dataset.
12. ML dataset made for classification and regression which classifies active and inactive compounds and predict the bioactivity IC50 values respectively.
13. Molecular Descriptors and Fingerprints of each chemical to be used as features and bioactivity class and IC50 values respectively. 
14. Analysing the VIP plots, Applicability Domain and Frequency plots , we obtain the best chemical candidates based on their theory and analyse them.
15. Predict the targets of those drugs and map them with the already prepared pathways and phenotype data of the reference map as mentioned in Step 2.
16. KG among the target gene of the chemical and the pathways and genes.

---

