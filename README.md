# Resources

A list of references, tools, packages and reading materials relevant to (my) research, covering epidemiology, statistics, machine learning, causal inference, and R/Quarto workflows.

This is a work in progress repo, suggestions are highly welcome.


## Contents

| Category | Description |
|---|---|
| Epidemiology | R-based epi methods and applied resources |
| Statistics | Statistical modeling tips and books |
| ML | Python ML frameworks |
| Data Visualization | R visualization ecosystem |
| Causal ML/AI | Causal inference for different topics |
| Omics | Resources for different omics |
| R/Quarto | Tips, tricks, and good coding practices |
| Reporting Guidelines | For prediction model reporting or other types of modeling |



# Resources

## Epidemiology

- **[The Epidemiologist R Handbook](https://www.epirhandbook.com/en/)**: Great resource to learn R for epidemiology.
- **[Advanced Epidemiological Methods](https://ehsanx.github.io/EpiMethods/)**: Website that goes through teaching R and a lot of statistical methods.

## Statistics

- **[Regression Modeling Strategies](https://hbiostat.org/rmsc/)**: Great book to gain more in-depth knowledge of statistical modeling.
- **[Marginalia: A guide to figuring out what the heck marginal effects are](https://www.andrewheiss.com/blog/2022/05/20/marginalia/#what-does-marginal-even-mean-in-the-first-place)**: Defines what marginal effects are, and explores the subtle differences between average marginal effects, marginal effects at the mean, and marginal effects at representative values with the `marginaleffects` and `emmeans` R packages.
- **[How to Interpret Statistical Models with marginaleffects for R and Python](https://marginaleffects.com/)**: Designed to help you overcome challenges in communicating model results to colleagues and stakeholders.
- **[performance](https://easystats.github.io/performance/index.html)**: The primary goal of the performance package is to provide utilities for computing indices of model quality and goodness of fit.
- **[interactionR](https://github.com/tunsmart/interactionR)**: InteractionR allows researchers to produce publication-ready tables that includes all effect estimates necessary for full reporting effect modification and interaction analysis as recommended by Knol and Vanderweele (2012).
- **[Assessing interation in epidemiological studies](https://ehsanx.github.io/interaction/)**: Guide to understand and interpret interactions.
- **[Multiple Time Varying Covariates](https://github.com/egonzato/mtvc)**: The function mtvc takes as input one more more time varying variable, with the respective date in which that change was found, and restructures the data frame into the counting process strucure, where each patient has a time window which reflects the comorbidity status.
  
## ML

- **[scikit-learn: Machine Learning in Python](https://scikit-learn.org/stable/)**: The go-to reference for ML in Python.
- **[Tidymodels packages](https://www.tidymodels.org/packages/)**: The tidymodels framework is a collection of packages for modeling and machine learning using tidyverse principles.
- **[Compendium of free ML reading resources](https://github.com/Carl-McBride-Ellis/Compendium-of-free-ML-reading-resources)**: GitHub repo with a lot of ML resources.
- **[Machine Learning with R, Fourth Edition](https://github.com/PacktPublishing/Machine-Learning-with-R-Fourth-Edition)**: Learn techniques for building and improving machine learning models, from data preparation to model tuning, evaluation, and working with big data.
- **[GEiPRS - A Fast and Powerful Machine Learning Method for Polygenic Risk Score Prediction by Leveraging Genotype-Environment Interactions](https://github.com/linnabrown/geiprs)**: GEiPRS simultaneously models both genotype (G) and GEI effects and efficiently handle high-dimensional GWAS data in terms of variant selection and PRS construction and prediction. 
- **[iterative Random Forests (iRF)](https://github.com/sumbose/iRF)**: The R package iRF implements iterative Random Forests, a method for iteratively growing ensemble of weighted decision trees, and detecting high-order feature interactions by analyzing feature usage on decision paths. 


## Data Visualization

- **[easystats: An R Framework for Easy Statistical Modeling, Visualization, and Reporting](https://github.com/easystats)**: A collection of R packages for statistical modeling and visualization.
- **[the ggplot2 Geom Explorer](https://www.ggplot2-uncharted.com/ggplot2-geom-explorer)**: This explorer puts every option on one page, so you can stop defaulting to bar and line charts and reach for whatever actually fits your story.
- **[R color cheatsheet](https://www.nceas.ucsb.edu/sites/default/files/2020-04/colorPaletteCheatsheet.pdf)**: Finding a good color scheme for presenting data can be challenging. This color cheatsheet will help!
- **[ggstatsplot](https://www.indrapatil.com/ggstatsplot/index.html)**: {ggstatsplot} is an extension of {ggplot2} package for creating graphics with details from statistical tests included in the information-rich plots themselves.
- **[Plotting Functions for the 'performance' Package](https://easystats.github.io/see/articles/performance.html)**: The primary goal of the performance package in easystats ecosystem is to provide utilities for computing indices of model quality and goodness of fit. 
  

## Causal ML/AI

- **[Causal-ish Omics](https://github.com/Trhova/Causal-Microbiome-Omics)**: A guide for people doing microbiome/metabolomics/multi-omics who want to get closer to causal answers.
- **[Causal Artificial Intelligence](https://causalai-book.net/)**: A comprehensive textbook bridging probability theory, causal inference, machine learning, and decision-making under uncertainty.
- **[Causal Inference in R](https://www.r-causal.org/)**: The tools in this book will allow readers to better make causal inferences with observational data with the R programming language. 


## Omics

- **[Tutorials Multi-Omics Factor Analysis](https://biofam.github.io/MOFA2/tutorials.html)**: Tutorials to use MOFA.
- **[Computational Genomics with R](https://compgenomr.github.io/book/)**: The aim of this book is to provide the fundamentals for data analysis for genomics.
- **[DNA Methylation: Array Workflow](https://nbis-workshop-epigenomics.readthedocs.io/en/latest/content/tutorials/methylationArray/Array_Tutorial.html#quality-control)**: In this tutorial, we will provide examples of the steps involved in analyzing methylation array data using R and Bioconductor.
- **[Quality control of the proteomic data from LUMOS machine](https://www.huber.embl.de/users/jlu/Proteomics/qualityControl_LUMOS.html)**: Example of QC for proteomics data.


## R/Quarto Tips and Tricks

- **[How to Make High-Quality PDFs with Quarto and Typst](https://rfortherestofus.com/2025/11/quarto-typst-pdf)**: Step-by-step guide to producing polished PDFs from Quarto.
- **[R for the Rest of Us (Blog)](https://rfortherestofus.com/blog)**: Tips, news, and tutorials for R users of all levels.
- **[The Good Research Code Handbook](https://goodresearch.dev/)**: Practical guidance on organizing research code so it is easy to understand and works reliably — aimed at grad students, postdocs, and PIs.
- **[The {targets} R package user manual](https://books.ropensci.org/targets/)**: The package skips costly runtime for tasks that are already up to date, orchestrates the necessary computation with implicit parallel computing, and abstracts files as R objects. If all the current output matches the current upstream code and data, then the whole pipeline is up to date, and the results are more trustworthy than otherwise.
- **[A Few Claude Skills for R Users](https://rworks.dev/posts/claude-skills-for-r-users/)**: This is a (very) short roundup of Skills created by members of the community that are especially helpful for R users.

## AI/ML Prediction Model Reporting

- **[TRIPOD+AI Statement](https://www.bmj.com/content/385/bmj-2023-078378)**: Updated guidance for reporting clinical prediction models that use regression or machine learning methods.
- **[Improving Health Care with Clinical Prediction Models From Idea to Impact](https://library.maastrichtuniversity.nl/resources/maastricht-university-press/catalog/improving-health-care-with-clinical-prediction-models/)**: This textbook offers a practical and comprehensive guide to developing, validating, and implementing clinical prediction models in health care, tracing the full pathway from concept to real-world impact.
