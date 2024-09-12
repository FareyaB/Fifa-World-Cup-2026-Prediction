# FIFA World Cup 2026 Prediction Model
This project aims to predict the outcomes of FIFA World Cup 2026 matches using machine learning techniques. A Random Forest classifier is used to train on historical match data and generate predictions. Additionally, the model accuracy is improved using feature engineering, and the results are visualized using seaborn and matplotlib.

# Project Structure
main_code.ipynb: Contains the main code for loading data, feature engineering, training the model, and visualizations.
wc_results.csv: Historical match results used for training the model.
wc_all_matches.csv: All match data, including team scores, used for feature extraction.
README.md: Project documentation.

# Key dependencies:

numpy
pandas
matplotlib
seaborn
scikit-learn

# Running the Model
1. Load and Preprocess Data:
Data is read from the wc_results.csv and wc_all_matches.csv files.
Features such as home and away team rankings, goals scored, goals conceded, and match outcomes are extracted.

2. Model Training:
A Random Forest classifier is used to predict match outcomes. You can also experiment with other models such as XGBoost and LightGBM.
Hyperparameter tuning and feature engineering steps are included to improve model accuracy.

3. Visualization:
Several plots are generated to analyze the results, such as confusion matrices and team-wise accuracy bar plots.

3. Prediction:
The model is trained to predict the outcomes of FIFA World Cup 2026 matches based on historical data. The final predictions are displayed along with the model accuracy.



