# Ransomware Detection Dataset - Pre-processing and Evaluation

## Project Overview
This project focuses on the pre-processing and evaluation of a dataset for ransomware detection. The dataset includes both ransomware (R) and benign software (Goodware - G), where each row represents a software and each column represents the number of times an API was accessed by that software.

## Pre-processing Steps
1. **Data Cleaning**: The dataset is cleaned by removing irrelevant or incomplete data.
2. **Data Analysis**: Basic analysis of the dataset is performed to understand patterns and distributions.
3. **Visualization**: Graphs are generated to visually represent the API usage patterns of ransomware and Goodware.

## Evaluation
After cleaning and pre-processing, the dataset is evaluated using **Random Forest** for classification. The Random Forest algorithm is used to classify the software into ransomware or Goodware based on API usage patterns.

### Algorithm Used
- **Random Forest Classifier**: A machine learning algorithm that creates a forest of decision trees, using a subset of data to train each tree and making predictions based on the majority vote across all trees.

## Example File
An example file demonstrating the evaluation of the dataset using the Random Forest algorithm is included in this repository.

## Requirements
- Python 3.x
- Libraries: Pandas, Scikit-learn, Matplotlib, Seaborn

## Installation
Clone this repository and install the necessary libraries:
```bash
git clone https://github.com/your-username/ransomware-detection.git
cd ransomware-detection
pip install -r requirements.txt
