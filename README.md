# Select-Predictors
## Automatically select a subset of predictors for use in predictive modeling procedures
This extension provides a user interface for the SELECTPR  ED command. It takes a specified set of predictor variables as input   and selects a smaller subset for use in predictive modeling procedure  s. A univariable method that considers each predictor in isolation is   used, as opposed to the multivariable method of selecting predictors   that is used by the Naïve Bayes Classifier extension. The Select Pre  dictors extension supports both categorical and scale dependent varia  bles. Large sets of predictors can be handled.
---
Installation intructions
----
1. Open IBM SPSS Statistics
2. Navigate to Utilities -> Extension Bundles -> Download and Install Extension Bundles
3. Search for the name of the extension and click Ok. Your extension will be available.

---
Tutorial
----

### Installation Location

Analyze →

&nbsp;&nbsp;Dimension Reduction →

&nbsp;&nbsp;&nbsp;&nbsp;Predictor Selection 

### UI
<img width="812" alt="image" src="https://user-images.githubusercontent.com/19230800/196483412-df7c62bb-30d6-4711-acaa-5a79190a69a6.png">
<img width="812" alt="image" src="https://user-images.githubusercontent.com/19230800/196483482-dd4a54b6-e565-46e6-ae1e-067fabaf3374.png">
<img width="812" alt="image" src="https://user-images.githubusercontent.com/19230800/196483520-2064ad3a-692d-42bd-b960-7c47f5f9a355.png">
<img width="812" alt="image" src="https://user-images.githubusercontent.com/19230800/196483591-0a07df98-c2e5-48fa-8949-99f29b594358.png">

### Syntax
Example

> SELECTPRED salary <br />
> /SCREENING STATUS=ON PCTMISSING=70.0 PCTEQUAL=95.0 PCTUNEQUAL=90.0 STDDEV=0.0 CV=0.001 <br />
> /CRITERIA SIZE=AUTO PCUTOFF=0.05 RANKING=PEARSONCHISQ TIMER=5.0 SHOWUNSELECTED=0.0 <br />
> /MISSING USERMISSING=EXCLUDE <br />
> /PRINT  CPS EXCLUDED SELECTED SUMMARY 

### Output

<img width="821" alt="image" src="https://user-images.githubusercontent.com/19230800/196483875-3c910ffe-3d77-473c-acc5-2bfc214c2f6d.png">

---
License
----

- Apache 2.0
                              
Contributors
----

  - IBM SPSS
