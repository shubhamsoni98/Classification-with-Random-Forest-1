# Classification-with-Random-Forest-1
To classify sales into categories (Low, Moderate, High) using Random Forests to inform strategic decisions and optimize marketing strategies.

# Sales Prediction with Random Forests

## Objective
To classify sales into categories (Low, Moderate, High) using Random Forests to inform strategic decisions and optimize marketing strategies.

## Solution

### Data Collection
- Utilized the `Company_Data.csv` dataset containing features like CompPrice, Income, Advertising, and categorical variables such as ShelveLoc, Urban, and US.

### Data Preparation
- **Cleaning**: Verified absence of missing values and handled outliers.
- **Encoding**:
  - Applied Ordinal Encoding for `ShelveLoc`.
  - Applied One-Hot Encoding for `Urban` and `US`.
  - Applied Label Encoding for the target variable `Sales`.

### Exploratory Data Analysis (EDA)
- Analyzed feature distributions and their relationships through visualizations such as KDE plots and bar charts.

### Model Building
- Trained a Random Forest Classifier with 500 trees and a maximum depth of 10.
- Evaluated performance using accuracy, classification report, and confusion matrix.

### Execution Time
- 5.31 seconds.

## Business Impact

- **Strategic Insights**: Provided actionable insights for better marketing strategies and resource allocation.
- **Decision Support**: Enhanced understanding of sales drivers and customer segmentation.
