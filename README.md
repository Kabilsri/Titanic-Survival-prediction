![image](https://famousoceanliners.files.wordpress.com/2015/07/wpid-titanic_sinking_stu_w1.jpg)
# Titanic Survival Prediction

## Overview
This project aims to predict the survival of passengers aboard the Titanic using machine learning models. The dataset contains features such as age, gender, ticket class, and number of relatives aboard.

## Dataset
The dataset used in this project is the Titanic dataset from Kaggle. It includes:
- **Survived**: 0 (No) or 1 (Yes)
- **Pclass**: Ticket class (1st, 2nd, 3rd)
- **Name**: Passenger's name
- **Sex**: Male or Female
- **Age**: Age in years
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Ticket fare
- **Cabin**: Cabin number (if available)
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Installation
To run this project, you need to install the required Python libraries:
```sh
pip install pandas numpy scikit-learn seaborn matplotlib
```

## Implementation
The project follows these steps:
1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical features
   - Feature scaling
2. **Exploratory Data Analysis (EDA)**
   - Visualizing survival rates based on different features
3. **Model Training**
   - Decision Tree Classifier
   - Random Forest Classifier
4. **Model Evaluation**
   - Accuracy score
   - Confusion matrix
   - Precision, recall, F1-score

## Usage
Run the Jupyter Notebook to execute the model training and prediction:
```sh
jupyter notebook "Titanic Survival prediction.ipynb"
```

## Results
### Model Accuracy:
- **Decision Tree Classifier**: 81.3%
- **Random Forest Classifier**: 84.7%

### Sample Output:
```
   Survived REAL  Survived PREDICTION
0              0                    0
1              1                    1
2              1                    1
3              0                    0
4              1                    1
```

- The best-performing model is evaluated using accuracy and other metrics.
- Insights from the analysis help understand which features impact survival rates the most.

## Contributing
If you’d like to improve the project, feel free to fork the repository and submit pull requests.

## License
This project is open-source and available under the MIT License.

