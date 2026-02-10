# Loan Status Prediction

This project predicts the approval status of loan applications using a machine learning model (Support Vector Machine). It demonstrates a complete workflow including data preprocessing, visualization, model training, evaluation, and making predictions.

## Features

- Data cleaning and preprocessing
- Exploratory data analysis and visualization
- Categorical variable encoding
- Model training using Support Vector Machine (SVM)
- Model evaluation on training and test data
- Predictive system for new loan applications

## Technologies Used

- Python
- pandas
- numpy
- seaborn
- scikit-learn

## Getting Started

1. **Clone the repository**  
   ```
   git clone https://github.com/yourusername/loan-status-prediction.git
   cd loan-status-prediction
   ```

2. **Install dependencies**  
   ```
   pip install -r requirements.txt
   ```
   Or install individually:
   ```
   pip install pandas numpy seaborn scikit-learn
   ```

3. **Dataset**  
   Place your dataset file as `dataset.csv` in the project directory.

4. **Run the notebook**  
   Open `Loan_Status_Prediction.ipynb` in Jupyter Notebook or VS Code and run the cells.

## Usage

- The notebook guides you through each step: loading data, preprocessing, training, evaluating, and making predictions.
- Modify the `input_data` variable at the end of the notebook to test predictions for different applicants.

## Example

```python
input_data = (1, 1, 4, 1, 0, 3036, 2504, 158, 360, 0, 1)
# Predicts if the loan will be approved or not for the given applicant data
```

## License

This project is licensed under the MIT License.