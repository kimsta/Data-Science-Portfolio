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
* **Project Repository:** [View and run the code here](https://github.com/kimsta/fairness_bias_audit)
* **Tech Stack:** Python, Scikit-learn, Pandas, Fairness Metrics.

### 3. Privacy-Preserving ML & Membership Inference Defense
A security audit demonstrating data leakage in Neural Networks and implementing Differential Privacy (DP-SGD) to secure the model against attacks.

* **The Attack:** I simulated a **Membership Inference Attack (MIA)** using a counterfactual "Shadow Model" approach. The experiment proved that standard SGD models memorize specific training examples, creating a critical privacy leak (Privacy Gap: +0.13).
* **The Defence:** I implemented **Differential Privacy** using the **Opacus** library ($\epsilon=1.0$). The audit confirmed that the DP-protected model successfully masked the presence of individual data points (Privacy Gap: ~0.00), rendering the attack ineffective while maintaining >90% accuracy.
* **Project Repository:** [View and run the code here](https://github.com/kimsta/privacy_audit_mia)
* **Tech Stack:** Python, PyTorch, Opacus, Scikit-learn.


### 4. NLP Pipeline for Automated Text Classification
In a trainee project at VATT, I designed and delivered a complete two-stage NLP pipeline to classify thousands of unstructured, Finnish-language free form text entries.

* **My Contribution:** I managed the end-to-end workflow, including a modern approach to programmatic labeling using the Google Gemini API, and training `spaCy` models for both stages of the pipeline.
* **Outcome:** The first-stage binary filter achieved a **93% F1-score**, and the final multi-label classifier achieved a **~90% F1-score** on its primary categories, successfully automating a massive manual data-structuring task.
* **Public Demo:** A public version of this pipeline, demonstrating the same techniques on a Finnish sentiment dataset, **[is available here](https://github.com/kimsta/spaCy_NLP_Sentiment_Demo)**.
* **Tech Stack:** Python, spaCy, scikit-learn, Pandas, Google Gemini API.


### 5. Automated ANOVA Pipeline for BioMedicum Helsinki
As part of a Master's level Data Science Project, our team developed a user-friendly statistical pipeline in R for the Koistinaho Lab to automate the analysis of complex experimental data.

* **My Contribution:** I led the development of the core R analytics engine, architecting data cleaning validation and the primary analysis logic which automatically selects distinct ANOVA models based on user input.
* **Outcome:** A reproducible tool that significantly reduced manual analysis time for the researchers.
* **Public Demo:** An R Markdown file demonstrating the core logic of this automated pipeline, **[is available here](https://github.com/kimsta/R_Automated_ANOVA)**.
* **Tech Stack:** R, Tidyverse, rstatix, broom, R Shiny

---
## Technical Skills

* **Languages:** Python, R, SQL
* **Python Libraries:**
    * **Deep Learning & Privacy:** PyTorch, PyTorch Geometric, Opacus
    * **ML & NLP:** scikit-learn, spaCy, statsmodels, joblib
    * **Data & Geospatial:** pandas, numpy, geopandas
    * **Graph & Network:** igraph, graph-tool, NetworkX, NetworKit
    * **Visualization:** matplotlib
* **R Libraries:** Shiny, R Markdown, Tidyverse (dplyr, ggplot2), knitr, pwr, rstatix, broom, Stan
* **APIs & Cloud:** Google Gemini API
* **MLOps & Big Data:** Docker, Kubernetes (K8s), MLflow, Spark
* **Version Control:** Git, GitHub

---

## License

Copyright (c) 2025 Kim Ståhlberg. Licensed under the MIT License.
