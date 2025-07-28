# Kim Ståhlberg | Data Science Portfolio

Hi, I'm Kim, a Data Scientist completing my Master's in Data Science at the University of Helsinki with a background in Statistics (BSc). This repository showcases my project work in machine learning, graph analytics, and statistical modeling.

**Contact:** [stahlberg.kim@gmail.com](mailto:stahlberg.kim@gmail.com)

---

## Featured Projects

### 1. High-Performance Travel Network Analysis
As a Data Science Trainee at VATT, I engineered a pipeline to provide a high-performance Python alternative to an existing QGIS/Stata workflow for calculating a travel-time matrix for a nation-wide historical transport network.

* **My Contribution:** I built the new pipeline from scratch and created a framework to benchmark its performance. The goal was to compare a baseline pure-Python implementation (`NetworkX`) and an optimized C-backed implementation (`igraph`) against each other and the original legacy workflow.
* **Outcome:** The `igraph` implementation was validated to be numerically identical to the baseline (`NetworkX`) while achieving a **~12x performance speedup** (~1 min vs. ~12 minutes). The overall Python pipeline provides a more automated and reproducible solution than the original GIS-based method.
* **Public Demo:** A public notebook demonstrating a **~18x performance gain** on a similarly scaled random graph **is available here.**
* **Tech Stack:** Python, geopandas, python-igraph, NetworkX, joblib.

### 2. NLP Pipeline for Automated Text Classification
In a separate trainee project at VATT, I designed and delivered a complete two-stage NLP pipeline to classify thousands of unstructured, Finnish-language free form text entries.

* **My Contribution:** I managed the end-to-end workflow. This included a modern approach to programmatic labeling using the Google Gemini API, and training `spaCy` models for both stages of the pipeline.
* **Outcome:** The first-stage binary filter achieved a **93% F1-score**, and the final multi-label classifier achieved a **~90% F1-score** on its primary categories, successfully automating a massive manual data-structuring task.
* **Public Demo:** A public version of this pipeline, demonstrating the same techniques on a Finnish movie review dataset, **is available here.** `[<-- Link to your NLP demo repo]`
* **Tech Stack:** Python, spaCy, scikit-learn, Pandas, Google Gemini API.

### 3. Automated ANOVA Pipeline for BioMedicum Helsinki
As part of a five-person team on a Master's level Data Science Project, we developed a user-friendly statistical pipeline in R for the Koistinaho Lab to automate the analysis of complex experimental data.

* **My Contribution:** I took the lead on developing the core R analytics engine. My primary responsibilities were to architect the data cleaning and validation functions (normality, variance) and to implement the primary analysis logic, which automatically selects one of four distinct ANOVA models based on user input. I also communicated directly with the client-scientist to translate their research needs into technical requirements for the pipeline.
* **Outcome:** Our team delivered a tool that provides researchers with a reproducible and highly efficient workflow, significantly reducing manual analysis time.
* **Tech Stack:** R, Tidyverse, rstatix.

### 4. Enterprise Revenue Forecasting for CGI Finland
As part of a university course project, our team developed a revenue forecasting model for CGI Finland based a large historical transaction dataset.

* **My Contribution:** I designed and implemented the core time series forecasting model using Python (Pandas, Statsmodels). My model used seasonal decomposition to accurately identify and predict complex trends and seasonal patterns.
* **Outcome:** The model was accepted by the client and is currently shadowing their existing forecasting methods to validate its improved accuracy.
* **Tech Stack:** Python, Pandas, NumPy, Matplotlib, Statsmodels.

---

## Technical Skills

* **Languages:** Python, R, SQL
* **Python Libraries:**
    * **ML & NLP:** scikit-learn, spaCy, statsmodels, joblib
    * **Data & Geospatial:** pandas, numpy, geopandas
    * **Graph & Network:** NetworkX, python-igraph
    * **Visualization:** matplotlib
* **R Libraries:** Tidyverse, rstatix, caret, randomForest, e1071
* **APIs & Cloud:** Google Gemini API
* **MLOps & Big Data:** Docker, Kubernetes (K8s), MLflow, Spark
* **Version Control:** Git, GitHub

---

## License

Copyright (c) 2025 Kim Ståhlberg. Licensed under the MIT License.
