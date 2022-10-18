# ckd_progression

Codesets and key variable definitions for study "Using Electronic Health Record Data to Evaluate Kidney Function Decline in Children with Chronic Kidney Disease"

## Codesets

| Codeset name and link       | Description |
|-----------------------------|-------------|
| [rx_hypertension.csv](https://github.com/PEDSnet/ckd_progression/blob/main/codesets/rx_hypertension.csv)                  | Anti-hypertensive medications                                                                                                               |
| [dx_glomerular_disease.csv](https://github.com/PEDSnet/ckd_progression/blob/main/codesets/dx_glomerular_disease.csv)      | Glomerular disease diagnoses                                                                                                                |
| [dx_hypertension.csv](https://github.com/PEDSnet/ckd_progression/blob/main/codesets/dx_hypertension.csv)                  | Hypertension diagnoses                                                                                                                      |
| [dx_cancer.csv](https://github.com/PEDSnet/ckd_progression/blob/main/codesets/dx_cancer.csv)                              | Cancer diagnoses                                                                                                                            |
| [dx_pmca_codeset.csv](https://github.com/PEDSnet/ckd_progression/blob/main/codesets/dx_pmca_codeset.csv)                  | Pediatric Medical Complexity Algorithm (PMCA) diagnosis codeset, adapted from [Simon et al 2014](https://pubmed.ncbi.nlm.nih.gov/24819580/) |
| [lab_urine_protein_qual.csv](https://github.com/PEDSnet/ckd_progression/blob/main/codesets/lab_urine_protein_qual.csv) | Qualitative urine protein lab measurements                                                                                                  |
| [height.csv](https://github.com/PEDSnet/ckd_progression/blob/main/codesets/height.csv)                                    | Height measurement                                                                                                                          |
| [lab_serum_creatinine.csv](https://github.com/PEDSnet/ckd_progression/blob/main/codesets/lab_serum_creatinine.csv)        | Serum creatinine lab measurements                                                                                                           |
| [px_kidney_transplant.csv](https://github.com/PEDSnet/ckd_progression/blob/main/codesets/px_kidney_transplant.csv)        | Kidney transplant procedures                                                                                                                |                                                                                                    |
| [px_dialysis.csv](https://github.com/PEDSnet/ckd_progression/blob/main/codesets/px_dialysis.csv)              | Dialysis procedures                                                                                                          |
| [nephrology.csv](https://github.com/PEDSnet/ckd_progression/blob/main/codesets/nephrology.csv)                            | Nephrology specialty                                                                                                                        |
| [kidney_biopsy](https://github.com/PEDSnet/ckd_progression/blob/main/codesets/kidney_biopsy/)                             | Kidney-biopsy related procedure and diagnosis codes                                                                                         |

## Key variable definitions

* **Hypertension**: Hypertension was defined by the presence of a diagnosis code associated with at least two physician visits (Inpatient, Outpatient, or ED visits) within two years of cohort entrance.
* **Proteinuria**: Proteinuria was defined as having at least one urinalysis with at least 1+ proteinuria within two years of cohort entrance.
* **Long-term dialysis**: Long-term dialysis was defined as occurrence of 2 dialysis codes separated by at least 90 days
* **Chronic disease burden**: For chronic disease burden, the numeric count of body systems with chronic conditions in the three years prior to cohort entrance using ICD9/10 codes as specified by the Pediatric Medical Complexity Algorithm (PMCA); the PMCA count was filtered to exclude renal and genitourinary disease from the count.
* **Glomerular disease**: two occurrences of glomerular diagnosis codes OR one occurrence of a glomerular diagnosis code AND a native kidney biopsy.
* **Malignancy**: at least two physician visits (Inpatient, Outpatient, or ED visits) on different days at which at least one diagnosis code for malignancy was used.
