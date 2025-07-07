*💧 Water Quality Prediction* -
This repository contains a machine learning project developed during a one-month  AICTE Virtual Internship sponsored by Shell in June 2025., focused on predicting key water quality parameters using a multi-output regression approach. The model is built using MultiOutputRegressor with RandomForestRegressor and is evaluated using standard regression metrics.

📌 Project Objective -
The objective of this project is to develop a predictive model that can estimate multiple water quality indicators simultaneously. This aids in environmental monitoring, water treatment planning, and ensuring water safety for various use cases.

🧪 Predicted Parameters -
The model predicts the following water quality parameters:

NH₄ (Ammonium)

BOD5 (Biochemical Oxygen Demand over 5 days)

Colloids

O₂ (Dissolved Oxygen)

NO₃ (Nitrate)

NO₂ (Nitrite)

SO₄ (Sulfate)

PO₄ (Phosphate)

Cl⁻ (Chloride)

⚙️ Technologies & Tools Used
Python -

Pandas & NumPy – Data handling

Scikit-learn – Modeling and evaluation

Jupyter Notebook – Experimentation and analysis

🧠 Model Architecture -
The project uses a MultiOutput Regression pipeline.

Model: MultiOutputRegressor wrapped around RandomForestRegressor

Pipeline Steps:

Data Preprocessing – Handling missing values, removing duplicates, normalizing if required.

Feature Engineering – Selecting relevant features using correlation and domain knowledge.

Model Building – Training the multi-output regression model.

Evaluation – Using multiple regression metrics to assess model performance.

📐 Evaluation Metrics -
Each output parameter is evaluated using:

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

These metrics help understand the prediction accuracy and variance explained by the model.

📅 Internship Summary
Duration: 1 Month

_____________________________________________________________________________________________________________________________________________________________________________________________________________________

Model link - https://drive.google.com/file/d/1Ca_Ml5gWZE4H-Oe2whGuV9hGixwlKH3m/view?usp=sharing








