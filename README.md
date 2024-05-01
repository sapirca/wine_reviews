# Predictive Wine Quality 

A machine learning project that explores the relationship between wine attributes and quality, with the aim of predicting wine ratings.

## Overview

Wine experts possess a unique skill in deciphering the flavors, aromas, and textures of wine to determine its quality. In this project, we attempt to model this process through data analysis and statistical techniques. The dataset used was obtained from Kaggle.

## Dataset Description

* **Source:** Kaggle - Wine Reviews dataset ([[link to the dataset](https://www.kaggle.com/datasets/zynicide/wine-reviews)])
* **Attributes:**
    * **price:** The cost of the wine.
    * **country:** Country of origin.
    * **points:** Rating assigned by a wine reviewer (on a scale of 80-100).
    * **province:** The region within the country of origin.
    * **region\_1:**  A more specific region designation.
    * **region\_2:** An even more specific sub-region (may be null).
    * **variety:** Grape variety used to produce the wine.
    * **winery:** Name of the wine producer.
    * **taster\_name:** Name of the wine reviewer (provided in certain files).
    * **taster\_twitter\_handle:** Twitter handle of the reviewer (if available).
    * **title:**  Title of the wine review.
    * **description:** A textual description of the wine's characteristics.
* **Number of Rows:** Approximately 120,000 (after preprocessing)

## Project Content

We uncover patterns and relationships between wine attributes and their potential impact on wine ratings. We develop a machine learning model capable of predicting wine ratings with reasonable accuracy, using factors like price, origin, variety, etc.

## Getting Started

### Prerequisites

* **Conda (Miniconda or Anaconda)** -
Please download the following:
[https://conda.io/projects/conda/en/latest/user-guide/install/index.html](https://conda.io/projects/conda/en/latest/user-guide/install/index.html)



### Installation
0. *To download the Project execute the command:*
	git clone https://github.com/sapirca/wine_reviews.git
	
1. *To create the conda environment execute the following commands:*

```bash
conda create --name wine-quality-project python
conda activate wine-quality-project
cd wine_reviews
pip install -r requirements.txt
```

2. 
3. *To start the notebook process:*


```bash
jupyter notebook --port=7770
```
    
	
   
2.  *To run the notebook:*

	Open your web browser and paste the foollowing in the address bar:
```bash
http://localhost:7770/tree
```

This will open the Jupyter Notebook dashboard.
Navigate through the file structure in the dashboard to find the file to open your notebook:

predictive_wine_quality.ipynb
   

