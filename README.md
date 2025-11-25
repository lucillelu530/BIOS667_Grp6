# BIOS667 Final Project

Longitudinal Modeling of Cognitive Decline in Older Adults Using GLM, GEE, and GLMM: An Analysis of the OASIS-2 Cohort

## Group Member

Yini Lu, Wan-Chen Lin, Rui Peng, Yixin Zhang

**Specific Task**

|   | Coding | Group members |
|-------------------|-------------------------|----------------------------|
| Introduction | N/A | Yini Lu |
| Data preprocessing | Remove NAs, Renamed variables, Recoded MMSE as binary, convert data format | Rui Peng, Wan-Chen Lin, Yixin Zhang, Yini Lu |
| Model 1: GLM | Model construction, Model performance evaluation and Model diagnostics | Rui Peng |
| Model 2: GEE | Model construction, Model performance evaluation and Model diagnostics | Yixin Zhang |
| Model 3: GLMM | Model construction, Model performance evaluation and Model diagnostics | Wan-Chen Lin |
| Model Comparisons | TBD | Yini Lu |
| Results Gathering | Qmd writing, literature review; Tables/ figures tidying | Yini Lu |
| Presentation | Summary all results | Rui Peng, Wan-Chen Lin, Yixin Zhang, Yini Lu |

## Introduction

Alzheimer’s disease (AD) is the most common cause of dementia worldwide and remains one of the most pressing public health challenges of the 21st century. Accurate and early cognitive assessment plays a central role in diagnosing Alzheimer’s disease, evaluating disease progression, and identifying individuals at elevated risk of decline. The Mini-Mental State Examination (MMSE) is one of the most widely used tools for assessing global cognitive status in clinical practice and research.

In this study we would use `OASIS` Longitudinal Dataset to investigate how baseline demographic and clinical factors, specifically age, sex, education, and dementia group, relate to both the probability and progression of poor cognition as measured by longitudinal changes in MMSE performance.

## Data Description

OASIS-2 longitudinal MRI aging cohort is a publicly available neuroimaging resource designed to advance research on brain aging and Alzheimer’s disease. The longitudinal dataset includes 150 adults aged 60 to 96, each with two or more MRI sessions separated by at least one year, totaling 373 imaging sessions. Within this cohort, 72 participants were nondemented across all visits, 64 were demented at baseline and remained so (including 51 with mild to moderate AD), and 14 transitioned from nondemented to demented during follow-up.

## Methods

We intend to use three models to describe the trajectory of MMSE: Logistic GLM, GEE and GLMM.

## Results

## Discussion

Result Comparisons

## Conclusion

Future potential directions

## Supplement materials

For peer reviewers and graders, we recommend you all to get access the data through this github repo using the following code:

```{r}
## Data access
library(readr)
oasis <- read_csv("https://raw.githubusercontent.com/lucillelu530/BIOS667_Grp6/main/data/oasis_longitudinal.csv")
```

For `.QMD` file reproduction, we also recommend all to download the `/code/.bib` and `/code/.csl` files in the repo.

=======
