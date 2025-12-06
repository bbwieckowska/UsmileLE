U-smile LE: Code Repository
This repository contains all R code and data required to reproduce the analyses presented in the paper:

"U-smile Likelihood Evaluation: a threshold-free, explainable framework for binary classification model assessment"

by Barbara Więckowska & Przemysław Guzik.

📁 Repository Structure

UsmileLE_code.qmd:	Main Quarto document containing all R code for:

• Data generation

• Univariate GLM (logistic regression) models

• GLM stepwise selection based on p‑value

• Random Forest forward selection based on effect size

• Visualization matrices for logistic regression and random forest

classification_datasets.xlsx / .RData	Generated synthetic datasets used in the study

selection_steps_GLM.xlsx / .RData	Stepwise selection results for logistic regression

selection_steps_RF.xlsx / .RData	Forward selection results for Random Forest


🚀 How to Run the Analysis

Open UsmileLE_code.qmd in RStudio (with Quarto installed).

Run the code chunks sequentially – the document is organized to:

Generate/reproduce the synthetic data

Perform univariate analyses

Execute stepwise/forward selection for GLM and RF

Generate all visualizations and result tables

Outputs (figures, tables, processed data) will be created in the working directory.

Note: All random seeds are set for full reproducibility.

📊 Data Overview

The synthetic datasets cover multiple scenarios:

Low / medium / high predictive power

Balanced and imbalanced (90/10) class distributions

Symmetric and asymmetric predictors

Real-world clinical data (Heart Disease dataset) is also integrated

📦 Required R Packages

The code uses the following key packages:

tidyverse, caret, randomForest, pROC

ggplot2, patchwork (for visualization)

readxl, writexl (for Excel I/O)

All packages are loaded automatically in the .qmd file.

🔗 Citation
If you use this code or the U-smile LE method, please cite our paper:

Więckowska, B., & Guzik, P. (2025). U-smile Likelihood Evaluation: a threshold-free, explainable framework for binary classification model assessment. [Journal Name].

📧 Contact
For questions or issues regarding the code, please contact:
Barbara Więckowska – bbwięckowska@gmail.com
