# Credit Card Fraud Detection

![Fraud Detection](https://via.placeholder.com/800x300)

A machine learning project for detecting fraudulent credit card transactions using advanced classification techniques. This project focuses on analyzing transaction data and building predictive models to classify transactions as fraudulent or legitimate.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

Credit card fraud is a significant challenge in the financial industry. This project aims to provide a machine learning solution to detect fraudulent transactions based on transaction features. It includes:

- Exploratory Data Analysis (EDA) for understanding the dataset.
- Data preprocessing steps such as handling imbalanced data.
- Implementation of classification algorithms.
- Evaluation of model performance.

## Dataset

The dataset used is publicly available and consists of transactions labeled as fraudulent or legitimate. You can download the dataset from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud).

### Features
- **Time**: The time elapsed between this transaction and the first transaction in the dataset.
- **V1, V2, ..., V28**: Principal components obtained using PCA.
- **Amount**: Transaction amount.
- **Class**: Target variable (1 for fraud, 0 for legitimate).

## Technologies Used

- **Python**: Programming language.
- **Pandas, NumPy**: Data manipulation and analysis.
- **Matplotlib, Seaborn**: Data visualization.
- **Scikit-learn**: Machine learning models and evaluation metrics.
- **Imbalanced-learn**: Handling imbalanced datasets.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/youssefelzahar/-credit-card-fraud-detection.git
   ```
2. Navigate to the project directory:
   ```bash
   cd credit-card-fraud-detection
   ```


## Usage

1. Run the exploratory data analysis:
   ```bash
   python eda.py
   ```
2. Train the machine learning models:
   ```bash
   python train_model.py
   ```
3. Evaluate the model performance:
   ```bash
   python evaluate_model.py
   ```

## Project Structure

```plaintext
credit-card-fraud-detection/
|-- data/                  # Dataset files
|-- notebooks/             # Jupyter notebooks for EDA and experimentation
|-- src/                   # Source code
    |-- preprocessing.py   # Data preprocessing scripts
    |-- model.py           # Machine learning model scripts
|-- requirements.txt       # Python dependencies
|-- README.md              # Project documentation
```

## Results

The performance of the models is evaluated using the following metrics:
- **Precision**: Ability to identify only the fraudulent transactions.
- **Recall**: Ability to detect all fraudulent transactions.
- **F1-Score**: Balance between precision and recall.

Example results:
| Model            | Precision | Recall | F1-Score |
|------------------|-----------|--------|----------|
| Logistic Regression | 0.92      | 0.85   | 0.88     |
| Random Forest       | 0.96      | 0.91   | 0.93     |

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

