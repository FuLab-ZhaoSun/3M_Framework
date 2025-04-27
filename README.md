# 3M Framework: Targeting for Multi-omics-based Biobank Website

## Introduction

This repository contains the source code for a static website presenting the **3M Framework (multi-omics, multimodal biospecimen, multi-departments)**. The framework aims to provide standardized guidance for the management of multimodal biospecimens intended for multi-omics-based biobanks, based on a systematic review of omics technologies and biobanking practices.

The website translates the key findings and protocols from the associated manuscript  into an accessible web format.

## Features / Website Sections

The website is structured into the following main sections, corresponding to the HTML files:

*   **Home (`index.html`):** Landing page providing an overview and entry point to the framework. Includes visual elements and navigation.
*   **Introduction (`introduction.html`):** Presents the abstract, background information, challenges in multi-omics biobanking, and introduces the 3M framework concept.
*   **Omics Requirements (`omics.html`):** Details the specific sample volume requirements and brief technical descriptions for major omics platforms:
    *   Genomics (WGS/WES, Amplicon, Macrogenome)
    *   Transcriptomics (mRNA-seq, miRNA-seq, LncRNA-seq, CircRNA-seq, Macrotranscriptome)
    *   Proteomics (DIA/4D-DIA, Label-free/TMT, PRM, Macroproteomics, Modified Proteomics - Phosphorylation, Glycosylation, etc.)
    *   Metabolomics (Targeted/Non-targeted, Lipidomics, Full-Spectrum)
    *   Epigenomics (WGBS, RRBS, BSAS, ATAC-seq, MeRIP-seq, ChIP-seq)
    *   Includes downloadable CSV tables for sample requirements.
*   **Sample Management (`sample_management.html`):** Outlines standard operating procedures (SOPs) for:
    *   Multimodal biospecimen collection and storage (Tissue, Blood, Urine, Saliva, Faeces)
    *   Sample Aliquoting strategies
    *   Sample Transport guidelines (temperature control, dry ice usage)
    *   Quality Control (QC) measures (Sample sampling, Tissue/DNA/RNA/Protein quality testing).
*   **Ethics & Security (`ethics.html`):** Discusses crucial ethical considerations, informed consent processes, data security, privacy protection, and provides links to downloadable ethical documents (Consent forms, withdrawal forms).
*   **Biobank Workflow (`workflow.html`):** Describes the integrated management workflows for:
    *   Biobank Sample Management (Accession and Release processes)
    *   Metadata Management (Data Accession and Release processes)
    *   Includes links to downloadable procedural documents (Application forms, Agreements, Rejection notices).
*   **Contact Us (`authors.html`):** Provides information about the research team, affiliations, and contact details for the corresponding authors.

## How to View the Website

This is a static website built with HTML, CSS, and minimal JavaScript. To view it locally:

1.  Ensure all HTML files (`index.html`, `introduction.html`, etc.), the CSS file (`style.css`), and the `Biobank` directory (containing downloadable documents) are in the same project folder.
2.  Open the `index.html` file in your preferred web browser.

## Technology Stack

*   HTML5
*   CSS3 (`style.css`)
*   JavaScript (Basic DOM manipulation for scroll animations and CSV download functionality)
*   Font Awesome (for icons)
*   Google Fonts (Montserrat, Roboto)

## Content Source

The textual content, data tables, and workflow descriptions presented on this website are derived directly from the manuscript provided in `aticle.txt`. The content was adapted for web presentation, primarily involving the removal of in-text citation markers (e.g., `[1-2]`, `[52-53]`). The file structure for downloadable documents follows the organization provided.

## Contact

For questions regarding the framework or the research content, please contact the corresponding authors:

*   **Yang Fu:** `fuyang@zzu.edu.cn`
*   **Zhen Yang:** `13526685689@163.com` 