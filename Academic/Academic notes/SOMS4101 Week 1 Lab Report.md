
| What we're working with                         | What has been Investigated                                                                           |
|:----------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| Survival Probability                            | Hazard Ratio w/ Univariate + multivariate Cox Regression analysis                                    |
| CAM-121                                         | HI/LO Cam-121                                                                                        |
| Cam-121 Score                                   | OS and PFS events                                                                                    |
| Patient TIL count                               | comparison of results with that from previous datasets                                               |
| External Datasets from other prognostic methods | The ability of the models based of CAM-121 to predict and gauge probability of clinical events, ==such as metastases==      |
| True Positive & False Positive Rate             | ROC/AUROC curve comparing classification performance of CAM-121 vs covariates.                       |
| median B-Cell and T-cell gene expression        | Cam-121 neg Correlation w/ t-cells, b-cells, and all immune cell types, both scatter + density plots |

## Clarify:
- Weighted Cam-121 score - > For each sample, a ==vector== of [[weighted signature expression score]]s was calculated by using Eq. 1 on the vst normalised gene expression data ([[Tumour gene expression signature in primary melanoma predicts long-term outcomes.pdf#page=11&selection=412,2,413,80|link]])
Eq.1: $$ Weighted \ signature \ score =  \sum_ {i=1}^nβ_i  \times gene_i  $$
- TIL count; Clark Score vs MIA


| Potential questions to answer                                                                                    |
| ---------------------------------------------------------------------------------------------------------------- |
| ~~Compare Fig2.A with Fig2.F, test values/data to see if curves are statistically similar~~                      |
| What are the downregulated key immune-mediated processes in the samples from patients that developed metastases? |

<u>***What link can be made between metastases and OS/PFS, or TIL count?***<u>

We can work with processed rows as n=143 for AVAST-M LN

data sources:

1. Table 1 for survivability (??????????????????)
2. Fig. 3b_3c_3d for metastases analyses (143 rows per analysis model)

PFS and OS for Fig.2 are both calculated from same dataset

#SOMS4101 #data-science #analysis #code