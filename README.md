# Fetal Health Classification using Cardiotocography (CTG)

Cardiotocography (CTG) is a method used during pregnancy to monitor fetal heart rate and uterine contractions. It is a crucial tool in assessing fetal well-being and helps in early detection of fetal distress.

This project aims to develop a model that can classify the outcome of CTG tests to ensure the well-being of the fetus. By analyzing CTG data, we can identify high-risk pregnancies and take necessary interventions to ensure a healthy outcome for both mother and baby.

## Dataset

The dataset used in this project contains features extracted from Cardiotocogram tests, along with the corresponding fetal health outcome. The dataset is available in the file `fetal_health.csv`.

Features include various parameters related to fetal heart rate, uterine contractions, and other relevant factors.

## Project Structure

The project structure is as follows:

- `README.md`: This file provides an overview of the project.
- `fetal_health_classification.ipynb`: Jupyter Notebook containing the code for data preprocessing, model training, and evaluation.
- `requirements.txt`: Text file listing the required Python libraries and their versions.
- `fetal_health.csv`: CSV file containing the dataset.

## Installation

To run the project, you need Python installed on your system. You can install the required libraries using the following command:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/SHYAM01SUNDAR/inlustro
```

2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open and run the Jupyter Notebook `fetal_health_classification.ipynb` to execute the code step by step.

4. Follow the instructions in the notebook to preprocess the data, train the model, and evaluate its performance.

## Results

The trained model achieved an accuracy of X% on the test set. The confusion matrix and classification report provide insights into the model's performance.

## Conclusion

This project demonstrates the development of a model to classify fetal health outcomes using CTG data. By accurately predicting the health status of the fetus, healthcare professionals can take timely actions to ensure a safe and healthy pregnancy.
