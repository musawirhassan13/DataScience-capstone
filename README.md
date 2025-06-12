### 📘 README for `SpaceX_Machine Learning Prediction_Part_5.ipynb`

```markdown
# SpaceX Falcon 9 First Stage Landing Prediction – Machine Learning

This notebook focuses on building machine learning models to predict whether the Falcon 9 first stage will successfully land. It is the final part of the SpaceX landing prediction project.

## Objective
Train and evaluate multiple machine learning classification models to identify which algorithm best predicts landing success.

## Key Steps

- Data scaling using `StandardScaler`
- Model training:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Decision Tree
  - K-Nearest Neighbors (KNN)
- Hyperparameter tuning with `GridSearchCV`
- Evaluation using accuracy and confusion matrix

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- sklearn (LogisticRegression, SVC, DecisionTreeClassifier, KNeighborsClassifier, GridSearchCV, train_test_split)

## Outcome

- Decision Tree achieved the best performance based on GridSearchCV results.
- A confusion matrix visualizes each model’s performance on the test set.
```


### 📘 README for `edadataviz.ipynb`

```markdown
# SpaceX Falcon 9 First Stage Landing Prediction – EDA and Visualization

This notebook explores and visualizes the SpaceX launch data to understand feature distributions and patterns that may influence the success of first stage landings.

## Objective
Perform exploratory data analysis (EDA) to gain insights and prepare the dataset for machine learning modeling.

## Key Steps

- Import cleaned SpaceX dataset
- Visualize launch success rate by:
  - Launch site
  - Orbit type
  - Payload mass
- Create plots to understand correlations between features

## Libraries Used

- pandas
- matplotlib
- seaborn
- plotly.express

## Outcome

- Payload mass affects landing success with a peak in performance near 10,000 kg.
- Some launch sites have higher success rates than others.
- Geospatial and orbit-based differences were visualized using bar plots and scatter charts.
```


