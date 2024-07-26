# Dental Sensitivity Prediction Using Machine Learning

## Objective
To develop a supervised machine learning model to predict the risk and intensity of dental sensitivity in patients undergoing in-office tooth whitening.

## Materials and Methods
This project utilizes retrospective data from 458 patients, incorporating the following variables:
- **Occurrence and intensity of dental sensitivity**: Measured by the Visual Analog Scale (VAS) from 0 to 10.
- **Baseline tooth color**
- **Characteristics of the whitening material**: Concentration and pH.
- **Characteristics of the intervention**: Number and duration of applications.
- **Age**

### Classification Models
- AdaBoost
- Decision Tree
- Gradient Boosting
- K-Nearest Neighbors
- Logistic Regression
- Multilayer Perceptron
- Random Forest
- Support Vector Machine

### Regression Models
- Gradient Boosting
- Linear Regression
- Support Vector Regression
- K-Nearest Neighbors
- Random Forest
- Multilayer Perceptron
- Decision Tree
- AdaBoost

### Evaluation Metrics
#### Classification Models
- **Area Under the ROC Curve (AUC)**
- **Accuracy**
- **Recall**
- **Precision**
- **F1-score**

#### Regression Models
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **Mean Absolute Error (MAE)**
- **Coefficient of Determination (R²)**

### Cross-Validation
All models were evaluated using 5-fold cross-validation to ensure robustness and reliability of the results.

## Results
ROC curves were generated for the classification models to visualize their performance.

## License
This project is licensed under the MIT License.

