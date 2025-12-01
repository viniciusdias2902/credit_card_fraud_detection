# Credit Card Fraud Detection

Machine Learning model for credit card fraud detection using Random Forest and SMOTE to handle imbalanced data.

## Dataset

**⚠️ IMPORTANT**: The dataset is not included in this repository due to file size limitations.

You **must** download it manually to run this project:

1. Go to [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
2. Download the `creditcard.csv` file (143 MB)
3. Place it in the project root directory

**Dataset Information:**

- **Size**: 284,807 transactions
- **Features**: 30 variables (V1-V28 from PCA transformation, Time, Amount)
- **Target**: Class (0 = legitimate, 1 = fraud)
- **Imbalance**: Only ~0.17% fraudulent transactions

## Setup

1. Clone this repository:

```bash
git clone https://github.com/viniciusdias2902/credit_card_fraud_detection.git
cd credit_card_fraud_detection
```

2. Install dependencies:

```bash
pip install scikit-learn imbalanced-learn pandas numpy matplotlib seaborn
```

3. **Download the dataset** (see Dataset section above)

4. Make sure `creditcard.csv` is in the project root directory

## Usage

1. Open the Jupyter notebook:

```bash
jupyter notebook treinamento_modelos.ipynb
```

2. Run all cells sequentially

## Technologies

- Python 3.x
- scikit-learn
- imbalanced-learn
- pandas
- numpy
- matplotlib
- seaborn

## Model

- **Algorithm**: Random Forest Classifier
- **Technique**: SMOTE (Synthetic Minority Over-sampling Technique)
- **Approach**: Handles class imbalance by generating synthetic samples
