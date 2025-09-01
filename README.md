# Differential Gene Expression in Placental Tissue from Women with and without Gestational Diabetes Mellitus

##### Keywords: Differential Expression Analysis - DESeq2 - Genomic Control - Multiple Testing Adjustment - Dermicidin

### Renderen HTML file: https://carofj.github.io/Differential-Gene-Expression-in-Placental-Tissue-from-Women-with-and-without-GDM/diffExGenesGDMPlacenta.html

### Introduction
Gestational diabetes mellitus (GDM) is among the most common complications of pregnancy, yet it remains frequently underdiagnosed. The condition is associated with increased risks of adverse outcomes for both mother and child, including the later development of type 2 diabetes and obesity. Identifying biomarkers that distinguish women who develop GDM from those who do not is therefore of considerable interest, as such markers could provide insights into the underlying pathophysiology of GDM and may also serve as predictive indicators to enable timely intervention (McIntyre et al. 2019).

This study utilized publicly available RNA sequencing data entitled “RNA sequence of gestational diabetes mellitus (GDM) and healthy control placentas”, obtained from the NCBI Gene Expression Omnibus (GEO) database (Wang and H 2021-12-31). The dataset comprises eight placental samples, four from women diagnosed with GDM and four from healthy controls. The mean gestational age at the time of sampling was approximately 37.2 weeks in the GDM group and 37.6 weeks in the control group, indicating comparable gestational ages across groups. All samples were collected postpartum from placental tissue. A detailed description of the experimental protocol is available on the GEO dataset webpage.

The aim of this analysis was to identify differentially expressed genes in the postpartum placenta between women who developed GDM and the control group. Furthermore, it was sought to investigate the biological processes associated with the significantly differentially expressed genes.

Data Overview:

    Sample size: n = 4 (GDM) and n = 4 (Control)

    Tissue source: Placenta (collected postpartum)

    Gestational age at sampling: 37-38 weeks for both sampling groups

    Sequencing platform: Illumina HiSeq 4000

### Discussion and Conclusion

The analysis identified two genes that appear to be significantly differentially expressed between the GDM and control groups. These findings are clearly illustrated in (Figure 11) and (Figure 12). One of these genes, ENSG00000161634 (dermicidin), encodes a secreted protein with two major functional domains: (1) a C-terminal peptide with antimicrobial properties, and (2) an N-terminal peptide that promotes neural cell survival under conditions of severe oxidative stress (NCBI 2025). This finding is particularly relevant given that GDM has been strongly associated with increased oxidative stress, suggesting that dermicidin and its protein products may represent potential biomarkers for GDM(Saucedo et al. 2023).

Another gene of potential interest is ENSG00000240567 (LINC02067), which appears to be differentially expressed between the GDM and control groups. This gene encodes a long intergenic non-protein coding RNA (lincRNA) and therefore does not produce a protein (National Center for Biotechnology Information 2025). Although its specific function has not been described in the literature, its differential expression suggests that it may still be biologically relevant and could serve as a potential biomarker.

This analysis uncovered several potentially relevant genes. However, the limited sample size likely reduced statistical power, such that only very strong signals could be detected with confidence. Future studies employing larger datasets will be valuable for validating these findings. Moreover, longitudinal datasets that include samples from different stages of gestation could provide important insights into how molecular profiles change over time and how these changes are influenced by GDM. Such data would help disentangle gestational age-related variation from disease-specific effects, thereby clarifying the true molecular signature of GDM.

### Data Analysis

    Data Preprocessing

    Differential Expression Analysis using the DESeq2 Package

    Genomic Control

    Multiple Testing Adjustment 

    Visualizations of the Results

### References

Love, Michael I., Wolfgang Huber, and Simon Anders. 2014. “Moderated Estimation of Fold Change and Dispersion for RNA-Seq Data with DESeq2” 15: 550. https://doi.org/10.1186/s13059-014-0550-8.
Love, Michael I, Zhu, Anqi, and Ibrahim, Joseph G. 2018. “Heavy-Tailed Prior Distributions for Sequence Count Data: Removing the Noise and Preserving Large Differences.” Oxford University Press (OUP). https://doi.org/10.17615/J2DS-AK73.
McIntyre, H. David, Patrick Catalano, Cuilin Zhang, Gernot Desoye, Elisabeth R. Mathiesen, and Peter Damm. 2019. “Gestational Diabetes Mellitus.” Nature Reviews Disease Primers 5 (1). https://doi.org/10.1038/s41572-019-0098-8.
National Center for Biotechnology Information. 2025. “NCBI Gene: LINC02067 (Homo Sapiens), Gene ID: 101243545.” https://www.ncbi.nlm.nih.gov/gene/101243545.
NCBI. 2025. “NCBI Gene ID:117159, Dermcidin (Homo Sapiens).” https://www.ncbi.nlm.nih.gov/gene/117159.
Saucedo, Renata, Clara Ortega-Camarillo, Aldo Ferreira-Hermosillo, Mary Flor Díaz-Velázquez, Claudia Meixueiro-Calderón, and Jorge Valencia-Ortega. 2023. “Role of Oxidative Stress and Inflammation in Gestational Diabetes Mellitus.” Antioxidants 12 (10): 1812. https://doi.org/10.3390/antiox12101812.
Wang, J, and Jin H. 2021-12-31. “RNA Sequence of Gestational Diabetes Mellitus (GDM) and Healthy Control Placentas.” https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE154414.

