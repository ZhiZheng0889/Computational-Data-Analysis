# Computational Data Analysis

This repository contains an R-based problem set focused on applied statistical learning and model evaluation. The work emphasizes regression, classification, diagnostics, and regularized estimation using built-in datasets such as `mtcars` and `iris`.

## Repository contents

- `Problem_Set_1_Zhi_Zheng.Rmd` — the main source notebook containing the analysis, code, and written explanations for each problem.
- `Problem_Set_1_Zhi_Zheng.nb.html` — an HTML-rendered version of the notebook for easy viewing in a browser without opening R.
- `ISLRv2_corrected_June_2023.pdf` — the course text/reference used for the assignment concepts.
- `Notes.docx` and `Practice Solution.docx` — supplemental course notes and practice materials.
- `README.md` — this overview of the repository and usage instructions.

## What is covered

The assignment includes several core topics in computational data analysis:

- Linear regression on the `mtcars` dataset
- Model fit assessment using $R^2$ and residual plots
- Variable transformations to improve model performance
- Training vs. test error as a function of model complexity
- Exploratory data analysis for the `iris` dataset
- K-nearest neighbors (KNN) classification with cross-validation
- Ridge regression via optimization and matrix-form estimation

## How to use this project

1. Open `Problem_Set_1_Zhi_Zheng.Rmd` in RStudio or another editor with R support.
2. Make sure R is installed and the needed packages are available:

```r
install.packages(c("ggplot2", "caret", "lattice", "class"))
```

3. Run the code chunks sequentially to reproduce the analysis.
4. If you want a quick rendered version without running R, open `Problem_Set_1_Zhi_Zheng.nb.html` in a browser.
5. If you need supporting course material, use the included PDF and notes files.

## Notes

This project is designed as a learning and assignment repository. It is best used to review statistical modeling techniques, inspect example code, and reproduce the results from the problem set in a local R environment.