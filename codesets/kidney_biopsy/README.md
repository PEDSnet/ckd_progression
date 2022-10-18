# Kidney biopsy

A broad approach was applied for kidney biopsy that incorporates any of the following:

* A procedure code for kidney biopsy ([px_kidney_biopsy](https://github.com/PEDSnet/ckd_progression/blob/main/codesets/kidney_biopsy/px_kidney_biopsy.csv))
* A procedure code associated with biopsy (renal not specified, [px_biopsy](https://github.com/PEDSnet/ckd_progression/blob/main/codesets/kidney_biopsy/px_biopsy.csv)), accompanied by source value string search for kidney/renal/kidney biopsy ICD code or kidney finding diagnosis code ([dx_kidney_finding](https://github.com/PEDSnet/ckd_progression/blob/main/codesets/kidney_biopsy/dx_kidney_finding.csv)) on same date
* A diagnosis code for kidney biopsy ([dx_kidney_biopsy](https://github.com/PEDSnet/ckd_progression/blob/main/codesets/kidney_biopsy/dx_kidney_biopsy.csv))
* A diagnosis code for biopsy result (renal not specified, [dx_biopsy_result](https://github.com/PEDSnet/ckd_progression/blob/main/codesets/kidney_biopsy/dx_biopsy_result.csv)), accompanied by kidney finding condition code on same date ([dx_kidney_finding](https://github.com/PEDSnet/ckd_progression/blob/main/codesets/kidney_biopsy/dx_kidney_finding.csv)) 
* String search for kidney/renal biopsy in visit source value