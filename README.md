# Kim Ståhlberg | Data Science Portfolio

Hi, I'm Kim, a Data Scientist completing my Master's in Data Science at the University of Helsinki with a background in Statistics (BSc). This repository showcases my project work in machine learning, graph analytics, and statistical modeling.

**Contact:** [stahlberg.kim@gmail.com](mailto:stahlberg.kim@gmail.com)

---

## Featured Projects

### 1. High-Performance Travel Network Analysis (Master's Thesis)
For my Master's thesis, titled "An Algorithmic Comparison for Efficiently Computing Travel-Time Matrices on a Multi-Modal Network," I am expanding on a project I began during my traineeship at a public research institute. The goal is to solve a computational bottleneck in simulation pipelines by developing and evaluating a high-performance Python framework for large-scale network analysis.

* **Foundational Work & Preliminary Results:** The foundational data pipeline was engineered during my traineeship and has already yielded a strong preliminary ~72x performance speedup over baseline methods by leveraging C-backed libraries like `igraph` over standard pure-Python implementations.

* **Thesis Research:** The current thesis work focuses on a rigorous comparative analysis of different algorithmic paradigms. This research evaluates the trade-offs between classic algorithms (**Dijkstra**), advanced exact methods (**Contraction Hierarchies**), and learned approximation methods (**Graph Neural Networks**).

* **Performance Benchmark:** A public notebook demonstrating the core optimization technique from the foundational work **[is available here](https://github.com/kimsta/Python-Graph-Benchmark)**.
* **Tech Stack:** Python, PyTorch, PyTorch Geometric, geopandas, python-igraph, graph-tools, NetworkX, NetworKit.

### 2. Algorithmic Fairness Audit: Healthcare Risk Prediction
A rigorous fairness audit and mitigation pipeline for a Heart Failure prediction model, designed to identify and correct safety disparities in medical diagnostics.

* **The Problem:** Through an intersectional audit (Age × Sex), I discovered a critical 4.5x Safety Disparity for young female patients compared to the reference group (older males). The standard model missed nearly 30% of heart failure cases in young women.
* **The Solution:** I engineered a hybrid mitigation strategy using **Decoupled Classifiers** and **Threshold Tuning**. By training separate models for demographic subgroups and adjusting the decision boundary for the disadvantaged group, I successfully reduced the safety risk by ~50% without requiring additional data collection.
* **Project Repository:** [Link](https://github.com/kimsta/fairness_bias_audit)
* **Tech Stack:** Python, Scikit-learn, Pandas, Fairness Metrics.

### 3. NLP Pipeline for Automated Text Classification
In a separate trainee project at VATT, I designed and delivered a complete two-stage NLP pipeline to classify thousands of unstructured, Finnish-language free form text entries.

* **My Contribution:** I managed the end-to-end workflow. This included a modern approach to programmatic labeling using the Google Gemini API, and training `spaCy` models for both stages of the pipeline.


### 4. NLP Pipeline for Automated Text Classification
In a separate trainee project at VATT, I designed and delivered a complete two-stage NLP pipeline to classify thousands of unstructured, Finnish-language free form text entries.

* **My Contribution:** I managed the end-to-end workflow. This included a modern approach to programmatic labeling using the Google Gemini API, and training `spaCy` models for both stages of the pipeline.
* **Outcome:** The first-stage binary filter achieved a **93% F1-score**, and the final multi-label classifier achieved a **~90% F1-score** on its primary categories, successfully automating a massive manual data-structuring task.
* **Public Demo:** A public version of this pipeline, demonstrating the same techniques on a Finnish sentiment dataset, **[is available here](https://github.com/kimsta/spaCy_NLP_Sentiment_Demo)**.
* **Tech Stack:** Python, spaCy, scikit-learn, Pandas, Google Gemini API.

### 5. Statistical Deep Dive into Padel Performance
This personal project is a comprehensive case study in applying a full statistical workflow—from data wrangling to a deployed web application—to a sparse, real-world dataset of amateur padel match results.

* **My Contribution:** I executed this project end-to-end, from raw data collection and wrangling to the final deployment of an interactive web application.

* **Key Methods:** The core of the project is a dual-paradigm statistical analysis. I used **frequentist** methods (hypothesis tests, power analysis) to establish statistical significance and complemented it with **Bayesian inference** (Beta-Binomial model) to quantify the uncertainty of each player's skill level.

* **Outcome & Deliverables:** The analysis produced a robust player ranking system, which is delivered via a live **[R Shiny App](https://kimst.shinyapps.io/Padel_Stats_Explorer/)**. The complete source code and a detailed statistical report are available in the **[project repository](https://github.com/kimsta/Padel_Project)**.

* **Tech Stack:** R, Shiny, R Markdown, Tidyverse, ggplot2, knitr, pwr.

### 6. Automated ANOVA Pipeline for BioMedicum Helsinki
As part of a five-person team on a Master's level Data Science Project, we developed a user-friendly statistical pipeline in R for the Koistinaho Lab to automate the analysis of complex experimental data.

* **My Contribution:** I took the lead on developing the core R analytics engine. My primary responsibilities were to architect the data cleaning and validation functions and to implement the primary analysis logic, which automatically selects one of four distinct ANOVA models based on user input. I also communicated directly with the client-scientist to translate their research needs into technical requirements for the pipeline.
* **Outcome:** Our team delivered a tool that provides researchers with a reproducible and highly efficient workflow, significantly reducing manual analysis time.
* **Public Demo:** An R Markdown file demonstrating the core logic of this automated pipeline, **[is available here](https://github.com/kimsta/R_Automated_ANOVA)**.
* **Tech Stack:** R, Tidyverse, rstatix, broom.

### 7. Enterprise Revenue Forecasting for CGI Finland
As part of a university course project, our team developed a revenue forecasting model for CGI Finland based a large historical transaction dataset.

* **My Contribution:** I designed and implemented the core time series forecasting model using Python (Pandas, Statsmodels). My model used seasonal decomposition to accurately identify and predict complex trends and seasonal patterns.
* **Outcome:** The model was successfully delivered and accepted by the client, demonstrating a measurable improvement in forecast accuracy over their existing methods. The project was later decommissioned following internal organizational changes at CGI.
* **Tech Stack:** Python, Pandas, NumPy, Matplotlib, Statsmodels.

---
## Technical Skills

* **Languages:** Python, R, SQL
* **Python Libraries:**
    * **Deep Learning, ML & NLP:** PyTorch, PyTorch Geometric, scikit-learn, spaCy, statsmodels, joblib
    * **Data & Geospatial:** pandas, numpy, geopandas
    * **Graph & Network:** igraph, graph-tool, NetworkX
    * **Visualization:** matplotlib
* **R Libraries:** Shiny, R Markdown, Tidyverse (dplyr, ggplot2), knitr, pwr, rstatix, broom
* **APIs & Cloud:** Google Gemini API
* **MLOps & Big Data:** Docker, Kubernetes (K8s), MLflow, Spark
* **Version Control:** Git, GitHub

---

## License

Copyright (c) 2025 Kim Ståhlberg. Licensed under the MIT License.
