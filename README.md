\# SRCAF Jaccard-Based Semantic Role Conflict Analysis



This repository contains the Python code and Jupyter Notebook implementation of the SRCAF (Structured Role Conflict Analysis Framework) experiment. The experiment analyzes semantic conflicts between roles (e.g., User, Platform, Regulator) using Jaccard similarity on extracted keyword sets.



---



\##  Environment Setup



We recommend using \[conda](https://docs.conda.io/en/latest/) to manage dependencies and isolate the environment.



\### 1. Create a new conda environment:



```bash

conda create -n srcaf-env python=3.10

```



\### 2. Activate the environment:



```bash

conda activate srcaf-env

```



---



\##  Required Python Packages



Install the following required libraries:



```bash

pip install numpy pandas scikit-learn matplotlib seaborn openpyxl

```



These libraries are used for:

\- `numpy` / `pandas`: data structure \& preprocessing

\- `scikit-learn`: Jaccard similarity metric

\- `matplotlib` / `seaborn`: plotting heatmaps and comparison graphs

\- `openpyxl`: Excel file I/O support (optional)



---



\##  Run the Notebook



After installing dependencies:



```bash

jupyter notebook SRCAF\_Jaccard\_Experiment\_Final.ipynb

```



The notebook will walk through:

\- Role narrative keyword extraction

\- Pairwise Jaccard similarity computation

\- Heatmap visualization of role overlap

\- Semantic conflict identification



---



\##  Files



\- `SRCAF\_Jaccard\_Experiment\_Final.ipynb`: Main experiment notebook

\- `Figure1.puml`: PlantUML diagram code for SRCAF conceptual flow

\- `Figure1.png`: Visual output of SRCAF process (optional)



---



&nbsp; 



