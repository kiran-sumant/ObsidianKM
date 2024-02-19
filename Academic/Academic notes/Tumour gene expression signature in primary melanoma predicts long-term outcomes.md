# Main Idea of Thesis

[[Adjuvant Systemic Therapy ]]used following [[resection]] of stage 3 [[melanoma]], but it requires more accurate [[prognostic]] data to classify/stratify patients.
Metastasis-associated gene signature identified, expression signature helps ID patients at high risk of metastasis.

Prognostic biomarkers for cancers are vital but unmet in clinics. It will help guide adjuvant therapies. Clinical guidelines from trial study need to be established by further research, as most studies only undergo retrospective or pr

#### [Doc Link](Tumour%20gene%20expression%20signature%20in%20primary%20melanoma%20predicts%20long-term%20outcomes.pdf)

# Details/Quotes

Use of [[Differential Expression Analysis]], on primary tumours from RNA-Sequenced Melanomas in an adjuvant trial.

Basically took RNA from tumour, sequences it. We find Cam-121 gene expression the best indicator-most associated with (progression-free) melanoma survival

Used machine learning model to create the classification model. More accurate compared to:
- Clinical covariates
- Current basic prognostic signatures

## Data Vis
> [!info] Kaplan-Meier Survival Plot (Fig. 1 a and b)
> Compares survival probabilities for high and low "Cam-121"
> > [!abstract]- Variables
> > - Time in years
> > - Survival Probability (overall or progression-free)
> > High Cam-121 generally decreases survival probability further over years
> 

> [!info] Forest Plot (Fig. 1 c) 
> Demonstrates Hazard ratio estimates for with hazard model sets with difference clinical variables. All fall within confidence interval
> > [!abstract]- Variables
> > - Hazard ratio
> > Models:
> > - Sex
> > - Age
> > - Stage
> > - ECOG
> > - Treatment
> > - NClass
> > - All the above
> > - All the above + Tumour Infiltrating Lymphocyte (TIL) count

Cam-121 Negatively correlates with TIL count.

## Machine Learning

R was used!!!
- Labelled for training
- One-Hot Encoding was used to convert covariate data to numeric dummy variables
- Variance Stabilizing Transformation (VST) used to transform both training and testing datasets for gene-expression data
- Data was used to train multiple ML models, and two-sample Welch t-tests used to statistically compare models based on AUROC (SVMRadical appears to be the most reliable across datasetsand classification models)

## Related Links
[Melanoma Transcriptomics Source Data](https://github.com/Manikgarg/MelanomaTranscriptomics/tree/master/Source_Data)
[Melanoma Transcriptomics Scripts](https://github.com/Manikgarg/MelanomaTranscriptomics/tree/master/scripts)

## Related Reading



#### Tags: #reference #gene-expression #data-science #melanoma #cancer 