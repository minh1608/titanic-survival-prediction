Titanic Survival Prediction 🚢

This repository contains the Kaggle notebook and supporting artifacts for the Titanic: Machine Learning from Disaster competition.
The project builds a reproducible machine learning pipeline to predict passenger survival based on demographic and ticket features.

The pipeline ingests the Titanic CSV dataset, preprocesses features, engineers new variables, and trains a Decision Tree classifier to evaluate survival predictions.

⸻

⚙️ Environment Setup

Option 1 — pip
pip install -r requirements.txt

Option 2 — conda
conda env create -f environment.yml
conda activate titanic-env

⸻

📓 Notebook Workflow

Steps implemented in the notebook:
	1.	Load and inspect Titanic dataset (train/test CSV).
	2.	Handle missing values (Age, Embarked, Cabin).
	3.	Encode categorical features (Sex, Pclass, Embarked).
	4.	Engineer new features (Family size, Title extraction).
	5.	Split train/test for validation.
	6.	Train Decision Tree classifier.
	7.	Perform hyperparameter tuning & pruning.
	8.	Evaluate validation accuracy.
	9.	Export predictions for Kaggle submission.

⸻

📦 Outputs

After running the notebook, you will find:
	•	Processed datasets: train_processed.csv, test_processed.csv
	•	Feature engineering artifacts: features.csv
	•	Model predictions: submission.csv
	•	Figures: .png plots of survival distributions, decision tree visualization

⸻

🚀 How to Run This Project
	1.	Clone the repo
git clone https://github.com/YOUR-USERNAME/titanic-survival-prediction.git
cd titanic-survival-prediction
	2.	Setup environment

	•	Using pip:
pip install -r requirements.txt
	•	Or with conda:
conda env create -f environment.yml
conda activate titanic-env

	3.	Run the notebook
Open Jupyter or VS Code and run:
notebooks/titanic.ipynb
	4.	Generate submission
Running all notebook cells will produce:

	•	submission.csv → upload to Kaggle for scoring

⸻

📊 Results
	•	Validation Accuracy: XX%
	•	Kaggle Leaderboard Score: XX%

Key insights:
	•	Gender and class were the strongest survival predictors.
	•	Family-related features added predictive power.
	•	Optimal tree depth balanced interpretability with accuracy.

⸻

📖 Citation

If you use this work, please cite:

Nguyen, P. M. (2025). “Titanic Survival Prediction: Decision Tree Modeling Approach.”
Kaggle Titanic: Machine Learning from Disaster Competition.

⸻

📜 License

This project is licensed under the MIT License – see LICENSE file for details.
