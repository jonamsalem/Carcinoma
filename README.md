# Single-Cell Insights into Carcinoma and Breast Cancer

## Introduction

[Invasive Ductal Carcinoma](https://www.breastcancer.org/types/invasive-ductal-carcinoma) (IDC) is the most common type of breast cancer, accounting for about 75–80% of all breast cancer cases. IDC begins in the milk ducts of the breast but invades the surrounding breast tissue, which means it has the potential to spread (metastasize) to other parts of the body through the lymphatic system or bloodstream.

### Causes and Risk Factors

While the exact cause of IDC isn't always clear, [several factors](https://pmc.ncbi.nlm.nih.gov/articles/PMC10415229/#:~:text=Genetic%20testing%20and%20counseling%20are%20essential%20for,with%20an%20increased%20risk%20of%20breast%20cancer.) increase the risk of developing it:

-   **Genetics:** Mutations in genes like **BRCA1, BRCA2, TP53**, or **HER2**.

-   **Hormonal Influence:** High estrogen levels, hormone replacement therapy, or early menstruation/late menopause.

### Applications of Single-Cell RNA-Seq in Invasive Ductral Carinoma

-   Like other cancers, Carinoma is not made up of identical cancer cells. Instead, the tumor is composed of a **diverse population of cells.** Single Cell Sequencing allows researches to study cancer heterogeneity at finer resolutions when compared to bulk RNA-Seq, enabling scientists to identify h distinct gene expression profiles, which could indicate **aggressiveness or drug resistance** of subpopulations.

-   scRNA-Seq allows for the understanding of the tumor environment. Single-cell sequencing allows researchers to capture both cancer cells and surrounding stromal, immune, and endothelial cells in the tumor, revealing how these cells communicate.

-   As Carcinoma progresses, the tumor evolves over time, acquiring new mutations that can contribute to drug resistance or metastasis. Single-cell sequrncing techeologies enables the tracking of these **epigenetic changes** across individual cells, giving insights into the **evolutionary trajectory**

-   Single-cell RNA-Seq can reveal **subpopulations of cells** that are resistant to chemotherapy, radiation, or hormonal therapies which help identify which cells are actually **expressing resistance mechanisms** even if the majority of the tumor seems responsive to treatment, enabling clinicians to set **personalized treatment regimens** for patients.

### Dataset

Single-cell RNA sequencing study focused on understanding the differences between invasive ductal carcinoma (IDC) and invasive lobular carcinoma (ILC) in breast cancer.

**Cancer Cell Lines (IDC and ILC):**

-    MCF7 – Wild type (IDC)

-   MCF7 with ESR1 Y537S mutation (IDC)

-   T47D – Wild type (IDC)

-   T47D with CDH1 knockout (CRISPR) (IDC)

-   MDA-MB-134-VI (IDC)

-   SUM44-PE (IDC)

-   BCK4 (IDC)

**Control Cell Line:**

-   MCF10A – Non-cancerous, normal mammary epithelial cell line

-    HEK293 – Human embryonic kidney cell line (commonly used as a control in experiments)

10X Genomics 3' Chromium v3.0:

-    Focuses on sequencing the 3' end of mRNA transcripts.

Illumina NovaSeq 6000 System:

-    High-throughput sequencer that allows for fast and efficient sequencing of large datasets

Source:

Chen F, Ding K, Priedigkeit N, et al.
Single-Cell Transcriptomic Heterogeneity in Invasive Ductal and Lobular
Breast Cancer Cells [published correction appears in Cancer Res. 2024
Dec 16;84(24):4298. doi: 10.1158/0008-5472.CAN-24-3940.]. *Cancer Res*. 2021;81(2):268-281. doi:10.1158/0008-5472.CAN-20-0696
