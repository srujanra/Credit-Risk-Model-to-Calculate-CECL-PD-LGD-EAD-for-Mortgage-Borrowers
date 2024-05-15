# Credit Risk Model to Calculate CECL (PD/LGD/EAD) for Mortgage Borrowers

This repository contains the code and resources for a Credit Risk Modeling project aimed at calculating Current Expected Credit Loss (CECL) for mortgage borrowers. The project involves processing and analyzing a large dataset of mortgage data to develop models for Probability of Default (PD), Loss Given Default (LGD), and Exposure at Default (EAD).

## Project Overview
<img src="Credit risk.png">
### Data Collection and Processing
- **Dataset**: 300,000 mortgage records.
- **Tools Used**: Python, NumPy, pandas, matplotlib, scikit-learn.
- **Techniques**: Data cleaning, validation, and transformation of borrower characteristics and loan performance factors.

### Feature Engineering and Selection
- **Feature Engineering**: Applied techniques such as min-max scaling, one-hot encoding, and fine classing.
- **Feature Selection**:
  - **Methods Used**: Weight of Evidence (WoE), Information Value (IV), Chi-Square Test.
  - **Outcome**: Narrowed down to 50 relevant variables.

### Model Development and Evaluation
- **Models**: Logistic Regression, Linear Regression, etc.
- **Evaluation Metrics**: Precision, Accuracy, Recall, F1 Score, ROC Curve.
- **Components Modeled**:
  - **PD**: Probability of Default
  - **LGD**: Loss Given Default
  - **EAD**: Exposure at Default
- **Ongoing Monitoring**: Regularly assessed model performance using the mentioned metrics.

## Repository Contents

- `data/`: Contains the dataset used for analysis (ensure data is anonymized or use sample data).
- `notebooks/`: Jupyter notebooks with detailed step-by-step analysis and code.
  - Data Cleaning and Transformation
  - Feature Engineering and Selection
  - Model Development (PD, LGD, EAD)
  - Model Evaluation and Monitoring
- `src/`: Python scripts for data preprocessing, feature engineering, model training, and evaluation.
- `reports/`: Documentation and reports summarizing the findings, models, and performance metrics.
- `README.md`: Project overview and instructions.

## Getting Started

### Prerequisites

Ensure you have the following libraries installed:
- pandas
- numpy
- matplotlib
- scikit-learn

### Installation

Clone the repository:
```bash
git clone https://github.com/yourusername/credit-risk-model-cecl.git
cd credit-risk-model-cecl
```

### Usage

1. **Data Preparation**:
   - Place your datasets in the `data/` folder.
   - Run the preprocessing scripts or notebooks to clean and transform the data.

2. **Feature Engineering and Selection**:
   - Execute the feature engineering and selection notebooks to prepare the final set of features.

3. **Model Development**:
   - Run the model development scripts to train PD, LGD, and EAD models.
   
4. **Model Evaluation and Monitoring**:
   - Use the evaluation scripts to assess model performance using precision, accuracy, recall, F1 score, and ROC curve.

5. **Analysis and Reporting**:
   - Review the generated plots, model outputs, and evaluation metrics in the reports.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or new features.



## Acknowledgements

- Thanks to the open-source community for the libraries and tools used in this project.
