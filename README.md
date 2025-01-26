# Spamfilter

## Overview
The **Spamfilter** is a machine learning-based tool designed to detect and filter spam messages. The project leverages modern algorithms and techniques to classify messages as spam or not spam, ensuring improved communication management.

## Features
- **Spam Classification**: Identifies whether a message is spam or not.
- **Customizable Model**: Allows users to modify parameters and extend functionalities.
- **Preprocessing Tools**: Includes data preprocessing and cleaning utilities.

## Project Structure
```
iu_spam-filter/
├── README.md             # Project overview and documentation
├── .gitignore            # Ignore unnecessary files
├── data/                 # Data
├── evaluation/           # Model evaluation
├── notebooks/            # Jupyter Notebooks
├── models/               # ML Models
├── reports/              # Reports and visualizations
├── tests/                # Unit and integration tests
├── requirements.txt      # Dependencies
└── config/               # Configuration files
```

Install the dependencies using the following command:
```bash
pip install -r requirements.txt
```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/PaulSchmidinger/iu_spam-filter.git
   ```
2. Navigate to the project directory:
   ```bash
   cd notebooks
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook spamfilter.ipynb
   ```

## Usage
1. Load the notebook in Jupyter.
2. Follow the sequential steps to:
   - Preprocess the dataset.
   - Train the spam filter model.
   - Test the model on sample data.
3. Customize the model or parameters as needed.
