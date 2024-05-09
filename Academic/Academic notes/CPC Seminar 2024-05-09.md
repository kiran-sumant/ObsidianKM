# Professor Zhiyong Wang | Multimedia computing for multi-disciplinary collaboration 

**Date:** 9/5/24
**Seminar Series:** CPC Seminar Series
**Speaker(s):** Professor Zhiyong Wang

## What was the seminar about?
Sydney Informatics Hub director, Prof. Zhiyoung Wang
Focused on interdisciplinary multi-media content creation, computing in many areas including agriculture, data science etc.

> [!statement] Multimedia is the **foundation of human communication**

His work is divided into two categories:

| Multimedia Data Understanding   | Multimedia content creation        |
| ------------------------------- | ---------------------------------- |
| Multi-modal video summarisation | Generative artificial intelligence |
| Audiovid analutics              | 3D construction/animation          |
| Human behaviour understanding   | VR/AR/MR                           |

Multimedia computing means ==working with Big Data== and using **AI** to build models based on experience through training.

Looking at unstructured data, through ==video analysis and summarisation==

## What were the major methods used?

Workflow as follows:
1. Input Video
2. Generate snippets (attention enhanced DD + Parameter sharing)
3. Extract features 
4. **Task-specific branches** (Classification+ regression)
5. Consensus layer (Classification and regression concessions)
6. Output (Parameters, Loss, data visualised and classified)

Also developed video summarisation method callsed Unsupervides Topic-Guided Co-Attention Transformer for Extreme Multimodal Summarisation. (***TopicCAT***)
- Unimodal learning followed by Multimodal learning from unimodal learning results and training data.

> [!example] Motion control
> - Developing gaps between keyframes for systematic complex movement such as anatomically correct locomotion.
> - How to relate to biology?



## What did the speaker discover?

Used and implemented for weakly supervised classification task; **Freezing of Gait (FoG) detection in Parkinson's patients.**

Multimedia includes:
- Video
- Footstep pressure map

Was able to reliably classify for edge cases with confidence.


> [!info] What question did you ask and what was the answer?
> no question asked in first half


# Professor Jinman Kim | Multi-modal learning for biomedical image analysis and visualisation

**Date:** 9/5/24
**Seminar Series:** CPC Seminar Series
**Speaker(s):** Professor Jinman Kim

## What was the seminar about?

Multi-modal computation in biology, in order to process medical images, link conditions with symptoms, classify based on imaging, etc etc.

ultimate combo for data acquisition would be Medical Imaging/Electronic Health Record/Mass spectrometry

Major innovations seen in multi-modal learning:

Multi-scale and multi-granularity features

Multi-modal dataset curation and pretraining

Medical Knowledge through UMLS

Multi-pretask pretraining/==Foundation models==

## What were the major methods used?

Workflow:
1. Image Acquisition
2. ROI segmentation
3. Feature Extraction
4. Statistical Analysis

for **Radiation-enhanced medical image-text contrastive learning**:
- Inter-matching relation-enhanced contrastive learning framework
- Semantic relation modelling (correlate semantic data/local matches)
- Importance relation modelling (focused on critical local-matchings)

**Contrastive-guided reconstruction framework** for developing ML imaging models
- Cohesion of contrastive-based and generative-based methods
- Masking semantic-important tokens in both image and text.


## What did the speaker discover?

Feeding text into models for image processing gives a MASSIVE boost to performance of classification models (as per accuracy)

Can use many different methods to train a machine model on a text+image based dataset, including GPT paraphrasing and image reconstruction.

## What question did you ask and what was the answer?

> [!info] Title
> - (Q) *In the case of Imaging mass spectrometric ([[IMS]]) methods involving extensive controlling of FDR in post processing of data, how would we go about navigating FDR and other metadata statistics if we wish to create a meta-analysis to report on reproducability or begin training models on data from multiple sources and sort based on parameters*
> - (A) 

or:
Ask based on adjusting a model for operating between diferent machines and normalise training data based on statistical metadata.



## General comments:
