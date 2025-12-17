# Classification-and-Segmentation-Project-for-Adult-Census-Income

Project Overview

This project aims to assist a retail business client in understanding and targeting their customer base by using demographic and employment-related data. The main objectives are:

Classification Model: Predict whether an individual earns less than $50,000 or more than $50,000 based on 40 demographic and employment-related variables.

Segmentation Model: Create population segments to identify distinct groups for marketing purposes, highlighting the differences between them and potential marketing strategies.

The dataset is derived from the 1994–1995 Current Population Surveys conducted by the U.S. Census Bureau. Each record contains 40 features, a weight (for population distribution), and a gold-standard label indicating income categor

# Classification and Segmentation Project for Adult Census Income

This project contains notebooks and code to perform classification and segmentation tasks on the Adult Census Income dataset.

## Getting Started

Follow the instructions below to set up and run the notebook in either **Google Colab** or a **local environment**.

---

## Running the Notebook on Google Colab

1. **Clone the Repository:**
   Open a terminal or command prompt and run the following command to clone the repository to your local machine:
   ```bash
   git clone https://github.com/Divya2890/Classification-and-Segmentation-Project-for-Adult-Census-Income.git
   ```

2. **Upload the Repository to Google Drive:**
   - Open your Google Drive in a web browser.
   - Drag and drop the entire cloned folder (`Classification-and-Segmentation-Project-for-Adult-Census-Income`) into your Drive.

3. **Open the Notebook in Colab:**
   - Open [Google Colab](https://colab.research.google.com/).
   - Click on `File` -> `Open Notebook` -> `Google Drive`.
   - Navigate to the folder you uploaded and select the notebook file.

4. **Modify File Paths:**
   - Inside the notebook, update file paths as needed based on your Google Drive path.
   - For instance, if the folder is in `/My Drive/`, set paths in the notebook:
     ```python
     data_path = '/content/drive/My Drive/Classification-and-Segmentation-Project-for-Adult-Census-Income/data'
     ```

5. **Run All Cells:**
   - Mount your Google Drive by running:
     ```python
     from google.colab import drive
     drive.mount('/content/drive')
     ```
   - Once Drive is mounted, execute all cells in the notebook to train models or generate results.

---

## Running the Notebook in a Local Environment

1. **Clone the Repository:**
   Run the following command to clone the repository to your local system:
   ```bash
   git clone https://github.com/Divya2890/Classification-and-Segmentation-Project-for-Adult-Census-Income.git
   ```

2. **Set up the Environment:**
   - Install [Python](https://www.python.org/downloads/) if you don’t already have it installed.
   - Make sure you have `pip`, a package manager for Python, installed.
   - Navigate to the project folder:
     ```bash
     cd Classification-and-Segmentation-Project-for-Adult-Census-Income
     ```
   - Install dependencies:
     ```bash
     pip install -r requirements.txt
     ```

3. **Run the Notebook:**
   - Install Jupyter Notebook if it’s not installed already:
     ```bash
     pip install notebook
     ```
   - Start the Jupyter Notebook server:
     ```bash
     jupyter notebook
     ```
   - Open the notebook file from the Jupyter interface and execute all cells.

---

## Repository Structure

```
Classification-and-Segmentation-Project-for-Adult-Census-Income/
├── data/                       # Include datasets here
├── report/                     # Generated Client Report
├── requirements.txt            # Dependencies for the project
└── README.md                   # Project documentation (you're reading this!)
└── Classification.ipynb        # Notebook modelling Classification
└── Segmentation.ipynb          # Notebook that models customer segmentation

```

