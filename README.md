# Kim Ståhlberg | Data Science Portfolio

Hi, I'm Kim, a Data Scientist pursuing my Master's in Data Science at the University of Helsinki with a background in Statistics (BSc). This repository showcases my project work in machine learning, graph analytics, and statistical modeling.

**Contact:** [stahlberg.kim@gmail.com](mailto:your.email@example.com)

---

## Featured Projects

### 1. High-Performance Travel Network Analysis (Master's Thesis)
As a Data Science Trainee at VATT Institute for Economic Research, I am engineering a high-performance Python system to replace an inefficient legacy workflow (QGIS/Stata). The project's goal is to compute an all-pairs travel-time matrix for a **nation-wide historical multi-modal transport network** with **tens of thousands of nodes**.

* **My Contribution:** I am architecting the entire Python pipeline, which involves parsing QGIS data, building the graph structure, and implementing optimized shortest-path algorithms. The core of the project focuses on performance engineering, including parallel processing and migrating logic to C-backed libraries to enable large-scale longitudinal and sensitivity analyses that were previously computationally infeasible.
* **Outcome:** This project forms the basis of my Master's thesis. The resulting high-performance tool will be a key asset for VATT's economic research on infrastructure impact.
* **Tech Stack:** Python, NetworkX, igraph, graph-tool (for evaluation), Parallel Processing.

### 2. NLP Pipeline for Text Classification
In a separate project as a Data Science Trainee at VATT, I developed a complete NLP pipeline to classify free-form text from thousands of Finnish-language renovation permits.

* **My Contribution:** I was responsible for the end-to-end development, from data cleaning and preprocessing to model selection and evaluation. This involved applying various NLP techniques, including feature extraction (TF-IDF) and implementing classification models (e.g., SVM, Naive Bayes) to categorize renovations based on their descriptions. I also worked on unsupervised clustering methods to help identify novel renovation types.
* **Outcome:** The model successfully categorizes permits, providing structured data for economic analysis that was previously locked in unstructured text.
* **Tech Stack:** Python, scikit-learn, NLTK, Pandas.

### 3. Automated ANOVA Pipeline for BioMedicum Helsinki
For the Koistinaho Lab at the University of Helsinki, I took a lead role in developing a user-friendly statistical pipeline in R to automate the processing of complex multi-electrode array (MEA) data, replacing a time-consuming manual workflow.

* **My Contribution:** I architected the core R analytics engine which automates the end-to-end analysis. This included implementing functions for data cleaning, outlier detection, normalization to a control treatment, and statistical validation (Shapiro-Wilk for normality, Levene's test for variance). A key feature I designed was the logic that selects and executes one of four distinct ANOVA models based on the user’s research questions, and then defines the appropriate post-hoc analysis.
* **Outcome:** The final tool provides researchers with a reproducible and highly efficient workflow, enabling rapid and consistent statistical analysis of their experimental data.
* **Tech Stack:** R, Tidyverse, rstatix

### 4. Enterprise Revenue Forecasting for CGI Finland
As part of a university course project, our team developed a revenue forecasting model and application for CGI Finland based on a large historical transaction dataset.

* **My Contribution:** I designed and implemented the core time series forecasting model using Python (Pandas, Statsmodels). My model used seasonal decomposition to accurately identify and predict complex trends and seasonal patterns in the revenue data.
* **Outcome:** The model was accepted by the client and is currently shadowing their existing forecasting methods to validate its improved accuracy and efficiency.
* **Tech Stack:** Python, Pandas, NumPy, Matplotlib, Statsmodels

---

## Technical Skills

* **Languages:** Python, R, SQL
* **Python Libraries:** scikit-learn, pandas, numpy, statsmodels, NetworkX, igraph
* **R Libraries:** tidyverse, caret, randomForest, e1071, rstatix
* **MLOps & Big Data:** Docker, Kubernetes (K8s), MLflow, Spark
* **Version Control:** Git, GitHub

---

## License

Copyright (c) 2025 Kim Ståhlberg. Licensed under the MIT License.
