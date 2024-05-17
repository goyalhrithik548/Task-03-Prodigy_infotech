# Bank Marketing Predictive Modeling

## Overview
This repository contains code and documentation for building a predictive model to determine whether a customer will purchase a product or service based on their demographic and behavioral data. The model utilizes a decision tree classifier trained on the Bank Marketing dataset obtained from the UCI Machine Learning Repository.

## Dataset
The Bank Marketing dataset consists of various features such as age, occupation, marital status, education level, credit default status, average yearly balance, housing loan status, personal loan status, contact communication type, and the last contact day of the week.

## Model Performance
- Test Accuracy of Decision Tree Classifier: 88.75%
- Cross-Validation Accuracy Scores Decision Tree: 88.96%

## Key Insights
- Significant Features: Age, occupation, marital status, education level, credit default status, average yearly balance, housing loan status, and personal loan status were found to be significant predictors of customer purchase behavior.
- Targeted Marketing Strategies: Insights from the model can inform targeted marketing strategies based on customer demographics and behavioral characteristics.
- Opportunities for Further Analysis: While the decision tree model provided valuable insights, further analysis could explore additional factors influencing purchase behavior and employ more advanced machine learning techniques.

## Repository Structure
- `data/`: Directory containing the Bank Marketing dataset (bank.csv).
- `notebooks/`: Jupyter notebooks for data exploration, preprocessing, model training, and evaluation.
- `models/`: Trained model files and model evaluation results.
- `README.md`: Documentation providing an overview of the project, dataset, model performance, key insights, and repository structure.

## Requirements
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib

## Usage
1. Clone the repository: `git clone https://github.com/your_username/bank-marketing-predictive-model.git`
2. Navigate to the repository directory: `cd bank-marketing-predictive-model`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Explore the Jupyter notebooks in the `notebooks/` directory to understand the data preprocessing, model training, and evaluation process.
5. Experiment with the code and models to further improve predictive performance or explore additional insights.

## Contributors
- [Hrithik Kumar](https://github.com/goyalhrithik548)

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
