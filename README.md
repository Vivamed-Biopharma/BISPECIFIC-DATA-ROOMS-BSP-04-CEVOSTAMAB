# BSP-04-CEVOSTAMAB: Novel FcRH5 x CD3 Bispecific Antibody Variants

![Status](https://img.shields.io/badge/Status-Pre--Clinical-blue)
![License](https://img.shields.io/badge/License-Proprietary-red)
![Category](https://img.shields.io/badge/Category-Bispecific%20Antibody-lightgrey)

This data room contains the complete in-silico design and validation package for BSP-04-CEVOSTAMAB. This asset comprises novel, humanized variants of the FcRH5 x CD3 bispecific antibody Cevostamab, engineered for an improved safety and administration profile. The core innovation focuses on enabling a fixed-dose regimen with potentially reduced Cytokine Release Syndrome (CRS) for the treatment of BCMA-refractory multiple myeloma.

---

### V9 Diligence Score (Validated: 2026-02-06)

| Metric | Score | Notes |
| :--- | :--- | :--- |
| **Patentability** | 6.25 / 10.0 | Differentiated from prior art (Genentech's Cevostamab) through novel sequences and formulation claims. |
| **In-Silico Enablement** | 9.0 / 10.0 | Comprehensive computational validation using a state-of-the-art 2026 toolchain. |
| **Commercial Value** | 7.75 / 10.0 | Addresses a significant unmet need in a heavily relapsed patient population. |
| **Composite Score (P+S+C)** | **23.00 / 30.0** | |
| **rNPV Estimate** | $150.0M | V9 model estimate. |
| **Gemini rNPV (Initial)**| $650.0M | Initial LLM-based analysis. |

---

## Innovation Profile

-   **Mechanism of Action:** T-cell redirection and activation against FcRH5-expressing tumor cells. The bispecific antibody simultaneously engages the CD3 epsilon chain on T-cells and the FcRH5 receptor on multiple myeloma cells, forming a cytolytic synapse that leads to T-cell-mediated tumor cell lysis.
-   **Target/Drug:**
    -   **Targets:** FcRH5 (on myeloma cells) × CD3 (on T-cells)
    -   **Drug Class:** Bispecific Antibody (BsAb)
    -   **Parent Molecule:** Cevostamab (BFCR4350A)
-   **Therapeutic Area/Indication:** Oncology; specifically, relapsed/refractory Multiple Myeloma (MM) in patients who are refractory to B-cell maturation antigen (BCMA)-targeted therapies.
-   **Differentiation from Prior Art:** Genentech's Cevostamab (BFCR4350A) is established as prior art. This program differentiates through:
    1.  **Novel Variant Sequences:** Claims cover specific humanized antibody variable domain sequences, derived from murine precursors, designed for enhanced developability and stability.
    2.  **Improved Dosing Regimen:** The variants are engineered to support a fixed-dose regimen, contrasting with complex step-dosing protocols often required to manage toxicity in this class.
    3.  **Potential for Reduced CRS:** Formulation and sequence improvements are aimed at mitigating the risk of severe Cytokine Release Syndrome, a major dose-limiting toxicity for T-cell engagers.

## Scientific Rationale

FcRH5 (Fc receptor-homolog 5) is a type I membrane protein that is expressed on B-lineage cells and is found on nearly 100% of multiple myeloma cells, with limited expression on normal tissues. This makes it an ideal target for T-cell redirecting therapies. While the concept of targeting FcRH5 x CD3 is clinically validated by the parent molecule Cevostamab, its application can be limited by toxicity (CRS) and complex dosing schedules.

The BSP-04 program addresses these limitations by leveraging state-of-the-art computational protein engineering. By starting from murine precursor sequences and applying advanced humanization and de-immunization algorithms, we have designed novel variants with optimized biophysical properties. These properties are predicted to translate into a more favorable therapeutic window, enabling a simplified, fixed-dose administration that improves patient convenience and potentially reduces the clinical burden of CRS management. The program aims to deliver a "best-in-class" FcRH5-targeting bispecific antibody for the BCMA-refractory MM population, an area of high unmet medical need.

## In-Silico Validation

The BSP-04 variants have undergone extensive in-silico validation using a comprehensive, state-of-the-art computational pipeline. All computational data is housed in the linked shared data repository.

### Sequence Validation (Status: VALIDATED - 2026-02-06)

All antibody VH/VL sequences were confirmed to possess correct structural and framework features prior to in-depth analysis:
-   **N-terminal Frameworks:** Presence of canonical residues (e.g., QVQL/EVQL for VH, DIVMTQ/DIQMTQ for VL).
-   **Conserved Cysteines:** Correct positioning for intradomain disulfide bond formation.
-   **J-Region Signatures:** Validated JH/Jkappa joining regions.
-   **CDR3 Specificity:** Confirmed that Complementarity-Determining Region 3 (CDR3) sequences are specific and not generic placeholders.
-   **Humanization:** The provided murine precursor sequences (containing motifs like `GSLKLS`) were successfully evolved into humanized variants (e.g., `GSLRLS`).

### Computational Methods Employed

The following computational tools were used for the design and analysis of the BSP-04 variants:

| Method | Application | Purpose |
| :--- | :--- | :--- |
| **Boltz-2 (AlphaFold3)** | Structure Prediction | Generation of high-accuracy protein structures and complexes. |
| **DiffDock-L** | Binding Prediction | Docking and binding affinity prediction for antibody-antigen interactions. |
| **ProteinMPNN** | Sequence Design | Inverse folding for sequence optimization on a fixed backbone. |
| **RFdiffusion** | *De Novo* Design | Design of novel protein topologies and variants. |
| **Aggrescan3D** | Developability | Prediction of Aggregation Prone Regions (APRs) on 3D structures. |
| **NetSolP** | Developability | Prediction of protein surface solubility. |
| **ThermoMPNN** | Stability Engineering | Prediction of changes in thermostability (ΔTₘ) upon mutation. |
| **DeepImmuno** | Immunogenicity | *In-silico* prediction of immunogenic T-cell epitopes. |
| **EvoEF2** | Stability Analysis | Calculation of folding free energy changes (ΔΔG). |

## Patent Claims Summary

The intellectual property for this asset centers on the novel composition of matter for the engineered variants and their method of use.
-   **Core Claims:** The patent application claims cover 'novel variant sequences' of the FcRH5 x CD3 bispecific antibody.
-   **Formulation Claims:** Claims are included for formulations that enable a fixed-dose administration schedule.
-   **Method of Use:** Claims describe the use of these variants for treating BCMA-refractory multiple myeloma with a reduced CRS profile.

## Data Room Index

All computational data for this bispecific program is located in a centralized, shared GitHub repository.

**Repository Link:** **[Bispecific-BSP-02-ELRANATAMAB](https://github.com/nickharris808/Bispecific-BSP-02-ELRANATAMAB)**

| Directory | Files | Content Description |
| :--- | :--- | :--- |
| `01_reference_data/` | 117 | Boltz-2 (AlphaFold3) generated CIF structure files, Multiple Sequence Alignments (MSAs), and pLDDT confidence scores for the parent molecule and designed variants. |
| `02_aggregation_analysis/` | 19 | Aggrescan3D output files detailing the mapping of Aggregation Prone Regions (APRs) on the antibody variants' surfaces. |
| `03_variant_designs/` | 45 | Candidate variant sequences generated by ProteinMPNN and RFdiffusion, provided in FASTA format. |
| `04_validation_results/` | 256 | Comprehensive validation data, including EvoEF2 ΔΔG calculations, NetSolP solubility scores, ThermoMPNN stability predictions, and DeepImmuno immunogenicity reports. |

## Usage

This data room serves as a comprehensive resource for due diligence and scientific review of the BSP-04-CEVOSTAMAB program.

1.  **Review Innovation Profile:** Begin with the Innovation Profile and Scientific Rationale sections to understand the asset's strategic positioning and mechanism.
2.  **Assess In-Silico Data:** Use the Data Room Index to navigate to the shared computational repository. The directories are organized by analysis type (structure, design, validation). Cross-reference the results in `04_validation_results/` with the design files in `03_variant_designs/`.
3.  **Evaluate Patentability:** The patent analysis highlights the key areas of differentiation from prior art. This forms the basis for the program's freedom-to-operate and commercial exclusivity.
4.  **Contact:** For questions or further information, please raise an issue in this repository or contact the program lead.