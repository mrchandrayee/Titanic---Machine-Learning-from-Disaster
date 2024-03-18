# Titanic---Machine-Learning-from-Disaster



```markdown
# Titanic - Machine Learning from Disaster

(https://www.kaggle.com/competitions/titanic/overview)

## Overview
This repository contains the code and resources for the Kaggle competition "Titanic - Machine Learning from Disaster". The goal of this project is to predict whether a passenger survived the sinking of the Titanic based on passenger information such as age, gender, socio-economic class, etc.

## Dataset
The dataset is provided in two CSV files:
- `train.csv`: Contains the details of a subset of passengers along with whether they survived or not (ground truth).
- `test.csv`: Similar to `train.csv` but without the survival information. Predictions need to be made for these passengers.

## Contents
- `train.csv`: Training dataset.
- `test.csv`: Test dataset.
- `titanic_predictions.csv`: Submission file containing predicted survival outcomes for test dataset.
- `titanic.ipynb`: Jupyter Notebook containing the code for data exploration, preprocessing, model building, and evaluation.
- `README.md`: This file.

## Requirements
- Python 3
- Jupyter Notebook
- Pandas
- Scikit-learn

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/mrchandrayee/Titanic---Machine-Learning-from-Disaster.git
   ```
2. Navigate to the repository directory:
   ```bash
   cd Titanic---Machine-Learning-from-Disaster
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook titanic.ipynb
   ```
4. Follow along with the notebook to explore the data, preprocess it, build a machine learning model, and make predictions.
5. After making predictions, the submission file `titanic_predictions.csv` will be generated. Submit this file to Kaggle for evaluation.

## Model
A Random Forest Classifier with 100 estimators is used for prediction. Hyperparameters are tuned using cross-validation.

## Evaluation
Model performance is evaluated using accuracy metric on a validation set.

## Results
The model achieved an accuracy of 76.79% on the validation set.
public score for this submission is 0.76794. This means that  model achieved an accuracy of approximately 76.79% on the test data provided by Kaggle.
## Credits
- Chand Rayee - [GitHub](https://github.com/mrchandrayee)

## License
This project is licensed under the [MIT License](LICENSE).
```

