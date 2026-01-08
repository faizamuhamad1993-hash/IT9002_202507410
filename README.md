# How to Run This Project
This repository contains an NLP-based automated essay scoring project implemented in a Jupyter Notebook. Follow the steps below to set up the environment and run the code successfully.

## Project Files

├── NLP_Project_Faiza_202507410.ipynb   # Main project notebook
├── README.md                          # Instructions to run the project

## Requirements
Make sure you have the following installed on your system:

* Python **3.8 or above**
* Jupyter Notebook or JupyterLab

### Required Python Libraries
Install the required dependencies using pip: pip install numpy pandas scikit-learn nltk transformers torch

## NLTK Setup
Some NLP components require additional NLTK resources. Run the following once before executing the notebook:
import nltk
nltk.download('punkt')
nltk.download('stopwords')

## ▶️ Running the Project

1. Clone this repository: git clone https://github.com/your-username/your-repo-name.git
2. Navigate into the project directory: cd your-repo-name
3. Launch Jupyter Notebook: jupyter notebook
4. Open the notebook file: NLP_Project_Faiza_202507410.ipynb
5. Run all cells sequentially from top to bottom.

## Notes
* Running the BERT model may require more memory and computational resources.

## Author
**Faiza Ramzan**

This README is intended to help users quickly set up and execute the project code for academic and learning purposes.
