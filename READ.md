# CCLE model comparison

[Aplying ML models to CCLE data to predict cancer lines with expression data]

## Question
[What are you predicting, from what, and why does it matter?]

## Data
- Source: DepMap Public 26Q3 (https://depmap.org), cancer cell line data.
- Files used: `OmicsExpressionTPMLogp1HumanProteinCodingGenes.csv` (gene expression, log2(TPM+1)) and `Model.csv` (cell line metadata).
- The data is not in this repository. [Say how to download it and where to put it, for example `data/`.]
- Citation: DepMap, Broad (2026). DepMap Public 26Q3. Dataset. depmap.org

## Setup
```
conda env create -f environment.yml
conda activate ccle-ml
```

## Project structure
- `notebooks/`: Code broken down to diffent sections of the porject
- `results/`: figures and tables
- `src/`: reusable code, if any

## Methods
- Labels: [which column, which classes, and why you kept those, for example diseases with more than 50 models]
- Preprocessing: [one-row-per-model choice, features, scaling]
- Models: [which ones you compare]
- Evaluation: [train/test split or cross-validation, and which metrics]

## Results
[Fill in later: a table comparing the models.]

## Limitations
[For example: only common diseases, cell lines are not patients, 424 models had no expression data.]

## Status
[What is done and what comes next.]