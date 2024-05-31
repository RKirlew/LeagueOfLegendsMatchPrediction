This project aims to predict the outcome (win/loss) of League of Legends matches based on various in-game factors using machine learning techniques. The provided example demonstrates how to train a logistic regression model for this task.
Requirements

    Python (>=3.6)
    pandas
    scikit-learn

Installation

    Clone the repository:

bash

git clone https://github.com/RKirlew/league-of-legends-match-prediction.git
cd league-of-legends-prediction

    Install the required Python packages:

bash

pip install -r requirements.txt

Usage

    Data Preparation:
        Ensure you have a dataset containing League of Legends match data in CSV format. The dataset should include features like champion selection, player statistics, and match outcomes.

    Training the Model:
        Modify the features and target variables in predict.py to match the columns in your dataset that you want to use as features and the target variable (win/loss).
        Run the predict.py script to train the logistic regression model and evaluate its performance on a test set.

    Predicting Match Outcomes:
        Modify the new_match_data dictionary in predict.py with the features of the new match you want to predict.
        Run the predict.py script to predict the outcome of the new match using the trained model.

Example

bash

python predict.py

Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.
