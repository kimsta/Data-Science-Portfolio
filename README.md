# Kim Ståhlberg | Data Science Portfolio

Hi, I'm Kim, a Data Scientist completing my Master's in Data Science at the University of Helsinki with a background in Statistics (BSc). This repository showcases my project work in machine learning, graph analytics, and statistical modeling.

**Contact:** [stahlberg.kim@gmail.com](mailto:stahlberg.kim@gmail.com)

---

## Featured Projects

### 1. High-Performance Travel Network Analysis
As a Data Science Trainee at VATT, I engineered a high-performance Python pipeline to calculate a travel-time matrix for a nation-wide historical transport network, replacing an inefficient QGIS/Stata workflow.

* **My Contribution:** I built the pipeline from scratch, from cleaning raw geospatial data (`geopandas`) to building the graph structure. A core part of the project was benchmarking performance between `NetworkX` (pure-Python) and `igraph` (C-backed).
* **Outcome:** The `igraph` implementation was validated to be numerically identical to the baseline while achieving a **~12x performance speedup** (~1 min vs. ~12 minutes), providing a robust, high-performance tool for VATT's future research.
* **Tech Stack:** Python, geopandas, python-igraph, NetworkX, joblib.

### 2. NLP Pipeline for Automated Text Classification
In a separate trainee project at VATT, I designed and delivered a complete two-stage NLP pipeline to classify thousands of unstructured, Finnish-language free form text entries.

* **My Contribution:** I managed the end-to-end workflow. This included a modern approach to programmatic labeling using the Google Gemini API, and training `spaCy` models for both stages of the pipeline.
* **Outcome:** The first-stage binary filter achieved a **93% F1-score**, and the final multi-label classifier achieved a **~90% F1-score** on its primary categories, successfully automating a massive manual data-structuring task.
* **Tech Stack:** Python, spaCy, scikit-learn, Pandas, Google Gemini API.

### 3. Automated ANOVA Pipeline for BioMedicum Helsinki
As part of a five-person team on a Master's level Data Science Project, we developed a user-friendly statistical pipeline in R for the Koistinaho Lab to automate the analysis of complex experimental data.

* **My Contribution:** Developing the core R analytics engine. My primary responsibilities were to architect the data cleaning and validation functions (normality, variance) and to implement the primary analysis logic, which automatically selects one of four distinct ANOVA models based on user input. I also communicated directly with the client-scientist to translate their research needs into technical requirements for the pipeline.
* **Outcome:** Our team delivered a tool that provides researchers with a reproducible and highly efficient workflow, significantly reducing manual analysis time.
* **Tech Stack:** R, Tidyverse, rstatix.

### 4. Enterprise Revenue Forecasting for CGI Finland
As part of a university course project, our team developed a revenue forecasting model for CGI Finland based on a large historical transaction dataset.

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
