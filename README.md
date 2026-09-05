# 🏏 IPL First Innings Score Prediction
A Machine Learning model to predict the final total score of an IPL match based on live match situation.

### 📊 Dataset
- **Source:** `ipl.csv` - Ball-by-ball data from 2008 to 2017
- **Rows:** 76,014
- **Features Used:** `bat_team`, `bowl_team`, `venue`, `runs`, `wickets`, `overs`, `runs_last_5`, `wickets_last_5`, `striker`, `non-striker`

### 🧠 Models Evaluated
| Model | R2 Score | MSE | MAE | RMSE |
| :--- | :--- | :--- | :--- | :--- |
| Linear Regression | 0.48 | - | - | 22.82 |
| **Random Forest Regressor (Best)** | **0.675** | **328.55** | **13.66** | **18.12** |

**Best Model:** `RandomForestRegressor` with 100+ trees

### 🔮 Sample Prediction
