# Breast Cancer Detection using PCA and Machine Learning

This project implements a Breast Cancer Detection system using Principal Component Analysis (PCA) for dimensionality reduction and a machine learning model for classification.

## Project Overview

The objective is to classify breast cancer as either malignant or benign using the Wisconsin Breast Cancer Dataset. PCA is used to reduce the dataset's dimensionality while preserving the most important features.

## Workflow

1. **Data Preprocessing:** 
   - Load the dataset.
   - Handle missing values.
   - Normalize the data.

2. **Dimensionality Reduction:**
   - Apply PCA to reduce the dimensionality of the dataset while retaining maximum variance.

3. **Modeling:**
   - Train a machine learning model (e.g., Logistic Regression, SVM, etc.) on the reduced dataset.

4. **Evaluation:**
   - Evaluate the model using accuracy, precision, recall, and F1-score.

## Dependencies

- Python 3.x
- NumPy
- pandas
- scikit-learn
- matplotlib
- seaborn

Install the required packages with:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/alihassanml/PCA-Principal-Concept-Analysis.git
cd PCA-Principal-Concept-Analysis
```

2. Run the project:

```bash
python main.py
```

3. View results and metrics.

## Dataset

The dataset used is the [Wisconsin Breast Cancer Dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)).

## Contributing

Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License.
