# Credit Risk Analysis and Prediction

This repository contains two key notebooks that together provide a comprehensive approach to credit risk prediction. The project starts with Exploratory Data Analysis (EDA) to gain insights into the data, followed by feature engineering and the development of a predictive model using machine learning techniques.

## Notebooks

### 1. Risk Analysis EDA (`risk-analysis-eda.ipynb`)

This notebook performs an exploratory data analysis (EDA) on the dataset to understand key trends, distributions, and correlations. The insights gained here guide the feature engineering and model-building processes.

#### Key Steps:
- **Data Overview**: A quick look at the data structure, including missing values, data types, and unique values.
- **Descriptive Statistics**: Key statistics are computed to understand the central tendency and variability of features.
- **Visualization**: Various plots like histograms, scatter plots, and correlation matrices to visualize relationships and distributions.
- **Outlier Detection**: Identification of outliers using box plots and statistical methods.
- **Feature Importance**: Preliminary analysis of which features might be more relevant for predicting credit risk.

### 2. Risk Feature Engineering and Model (`risk-feature-eng-log-model.ipynb`)

This notebook focuses on transforming raw data into meaningful features and building a predictive model to assess credit risk. A logistic regression model is developed to predict whether a client will have payment difficulties.

#### Key Steps:
- **Feature Engineering**: Transforming existing features and creating new ones that are more useful for model building.
- **Handling Missing Values**: Techniques like imputation to fill in missing data.
- **Encoding Categorical Data**: Transforming categorical variables into numerical format using encoding techniques.
- **Model Building**: Logistic regression is employed to predict the likelihood of a client facing payment difficulties.
- **Model Evaluation**: Accuracy, precision, recall, and ROC-AUC metrics are computed to assess model performance.
- **Hyperparameter Tuning**: Optimizing the model through techniques such as cross-validation.

## Dataset

The dataset used for this analysis can be found on Kaggle:
[Credit Risk Dataset](https://www.kaggle.com/datasets/adithiav/credit-risk/data)

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/credit-risk-analysis.git
   ```
2. Open the notebooks in Jupyter or Google Colab to explore the EDA and model building steps:
   - `risk-analysis-eda.ipynb` for exploratory data analysis.
   - `risk-feature-eng-log-model.ipynb` for feature engineering and model building.

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Results

The predictive model shows strong performance in distinguishing clients with payment difficulties from those without, as evidenced by evaluation metrics like accuracy and ROC-AUC scores.

## Conclusion

This project demonstrates a complete workflow from data exploration to model deployment for credit risk prediction. By identifying key features and building an optimized logistic regression model, it helps in making data-driven decisions for managing credit risk.

