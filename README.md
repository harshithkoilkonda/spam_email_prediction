# Spam Detection Using Random Forest Classifier

This project is a simple example of spam detection using a Random Forest Classifier. It uses a dataset containing text messages labeled as 'ham' (not spam) or 'spam' and builds a machine learning model to classify messages as either 'ham' or 'spam' based on their content.

### Prerequisites

To run this code, you need the following Python libraries installed:

- NumPy
- pandas
- Matplotlib
- scikit-learn

You can install these libraries using pip:

```
pip install numpy pandas matplotlib scikit-learn
```

### Installation

1. Clone this repository to your local machine:

```
git clone https://github.com/harshithkoilkonda/spam_email_prediction.git
```

2. Navigate to the project directory:

```
cd spam_email_prediction
```

3. Run the Jupyter Notebook file `EMAIL_SPAM_PREDICTION.ipynb` to see the code and its execution step-by-step.

## Dataset

The dataset used for this project is publicly available on [GitHub](spam.csv). It contains two columns: 'v2' (text of the message) and 'v1' ('ham' or 'spam').

## Model

We use a Random Forest Classifier to train a machine learning model. The model is trained on a balanced dataset to ensure equal representation of 'ham' and 'spam' labels.

## Usage

- The `EMAIL_SPAM_PREDICTION.ipynb` Jupyter Notebook contains the code for data preprocessing, model training, and evaluation.
- You can also use the trained model to make predictions on new text samples by loading it as shown in the notebook.


## Acknowledgments

- The dataset used in this project is sourced from GitHub.
