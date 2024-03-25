# Titanic Survival Predictions

This repository contains the machine learning model predictions for the Titanic survival dataset. The model predicts whether a passenger survived the Titanic disaster based on various features like age, sex, class, etc.

## Dataset

The dataset used for training the model is the famous Titanic dataset, which includes passenger information from the Titanic. It has been split into training and test sets, with the following features:

- PassengerId: Unique ID for each passenger
- Pclass: Passenger class (1st, 2nd, or 3rd)
- Name: Passenger name
- Sex: Passenger sex
- Age: Passenger age
- SibSp: Number of siblings/spouses aboard
- Parch: Number of parents/children aboard
- Ticket: Ticket number
- Fare: Fare paid for the ticket
- Cabin: Cabin number
- Embarked: Port of embarkation

## Model

The model is a combination of RandomForestClassifier and GradientBoostingClassifier from the scikit-learn library. The model training includes preprocessing steps such as encoding categorical variables and imputing missing values.

## Predictions

The `predictions.csv` file contains the survival predictions for the test set. Each row corresponds to a PassengerId and its predicted survival outcome (0 = No, 1 = Yes).

## Usage

To run the prediction script:

1. Ensure you have Python and the necessary libraries installed.
2. Clone this repository.
3. Run the script with the command `python predict.ipynb`.

## Contributing

Contributions to improve the model or its implementation are welcome. Please feel free to fork this repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments

- The dataset is provided by Kaggle as part of the Titanic: Machine Learning from Disaster competition.
- The scikit-learn library is used for implementing the machine learning model.


### Connect With Us 🌐

Feel free to reach out to us through any of the following platforms:

- Telegram: [@crupgrade](https://t.me/crupgrade)
- LinkedIn: [Mr. Chandrayee](https://www.linkedin.com/in/mrchandrayee/)
- GitHub: [mrchandrayee](https://github.com/mrchandrayee)
- Kaggle: [mrchandrayee](https://www.kaggle.com/mrchandrayee)
- Instagram: [@chandrayee](https://www.instagram.com/chandrayee/)
- YouTube: [Chand Rayee](https://www.youtube.com/channel/UCcM2HEX1YXcWjk2AK0hgyFg)
- Discord: [AI & ML Chand Rayee](https://discord.gg/SXs6Wf8c)


