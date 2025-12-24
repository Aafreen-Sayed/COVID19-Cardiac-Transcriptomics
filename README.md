# Gene Enrichment Studies of COVID-19 Data & Cardiac Manifestations

## 🏆 Impact & Recognition
**Presented at:** International Conference on Computing, STEM and Applied Sciences (ICCSAS) 2025
**Host Institution:** B. K. Birla College, Kalyan
**Year:** 2025

## 📌 Project Overview
COVID-19 primarily affects the respiratory system but is strongly linked to cardiovascular complications like myocarditis and arrhythmias. This study utilized **transcriptomic data analysis** to identify Differentially Expressed Genes (DEGs) linking SARS-CoV-2 infection to cardiac dysfunction.

## 🛠️ Methodology & Tech Stack
* **Data Source:** Transcriptomic datasets from NCBI GEO (GSE193022, GSE211378, GSE243348).
* **Normalization:** Robust Multiarray Average (RMA) method.
* **DEG Identification:** GEO2R / Limma package in R (Threshold: logFC > 1.0, adj.P < 0.05).
* **Visualization:** Volcano plots (ggplot2) and PPI Networks (STRING).

## 📊 Key Findings
* **Downregulated Genes:** Identification of **HLA Class II genes** (HLA-DRA, HLA-DQA1, HLA-DRB5), suggesting immune suppression and impaired antigen presentation.
* **Upregulated Genes:** Identification of inflammatory markers (MMP9, CXCL8, IL1B), indicating cytokine storm-mediated cardiac damage.
* **Pathway Analysis:** Enriched pathways confirmed the association between viral immune response and cardiac tissue inflammation.

## 🖼️ Visuals
<br>
* **Figure 1:** Volcano Plot of Differentially Expressed Genes.
<img width="1200" height="800" alt="DEGs_VolcanoPlot" src="https://github.com/user-attachments/assets/1c2b7078-07ee-4cdc-b969-e09f0209252c" />

<br>
* **Figure 2:** Protein-Protein Interaction (PPI) Network of Downregulated Genes (HLA cluster).
<img width="1060" height="629" alt="image" src="https://github.com/user-attachments/assets/ea2db735-3395-4e0c-aea9-a141c820906a" />

<br>
* **Figure 3:** PPI Network of Upregulated Genes (Inflammatory markers).
<img width="898" height="546" alt="image" src="https://github.com/user-attachments/assets/8af7287f-c298-4571-b577-fb586b980263" />
<br>
---
*Research conducted by Aafreen Sayed under the guidance of Dr. Sneha Dokhale.*
