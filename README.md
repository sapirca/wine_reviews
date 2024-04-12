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

* **Conda (Miniconda or Anaconda)** - [https://conda.io/projects/conda/en/latest/user-guide/install/index.html](https://conda.io/projects/conda/en/latest/user-guide/install/index.html)

* **Kaggle Account and API Key** 
   * Sign up for a free Kaggle account at [https://www.kaggle.com/](https://www.kaggle.com/).
   * Once logged in, go to your account settings page ([https://www.kaggle.com/[your-username]/account](https://www.kaggle.com/[your-username]/account)) and click on "Create New API Token". This will download a file called `kaggle.json`.
   * **Securely Install the API Key:**
       ```bash
       mkdir -p ~/.kaggle
       cp ~/Downloads/kaggle.json ~/.kaggle/
       chmod 600 ~/.kaggle/kaggle.json
       ```

### Downloading the Dataset

Once you have your Kaggle API key set up, you can include instructions to download the dataset directly during setup:

```bash
!kaggle datasets download -d zynicide/wine-reviews

### Run the python code ??

Convert the colab to python?

```bash
???


### Installation

#    cd Predictive-Wine-Quality
1. **Create the conda environment:**
   ```bash
   git clone https://github.com/sapirca/wine_reviews.git
   conda create --name wine-quality-project python
   conda activate wine-quality-project
   pip install -r requirements.txt
   
   jupyter notebook --port=7770
   Navigating to the Notebook:
    Open your web browser.
    Paste http://localhost:7770/tree in the address bar and press Enter.
    This will open the Jupyter Notebook dashboard.
    Navigate through the file structure in the dashboard to find the folder: /path/to/git/repo/wine_reviews/
    Click on the Understanding_wine_trends_across_different_attributes.ipynb file to open your notebook.
   




