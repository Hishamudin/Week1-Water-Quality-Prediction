💧 Water Quality Prediction - AICTE Virtual Internship 2025

This project aims to predict multiple water quality parameters using machine learning techniques, developed as part of the **AICTE Virtual Internship** program, in collaboration with **Edunet Foundation** and sponsored by **Shell**.

 📌 Project Overview

Access to clean water is essential for public health and environmental sustainability. This project leverages real-world water quality data to predict the concentration levels of various pollutants, assisting in early detection of contamination.

 🧠 Problem Statement

Given historical water quality readings from multiple monitoring stations, build a machine learning model that can **predict multiple pollutant levels** including:

- `O2` (Oxygen)
- `NO3` (Nitrate)
- `NO2` (Nitrite)
- `SO4` (Sulfate)
- `PO4` (Phosphate)
- `CL` (Chloride)

 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| **Python 3.12** | Programming language |
| **Pandas, NumPy** | Data manipulation |
| **Matplotlib, Seaborn** | Data visualization |
| **Scikit-learn** | Machine learning (modeling & evaluation) |
| **Jupyter/Colab Notebook** | Interactive experimentation |

 📂 Dataset Features

| Column | Description |
|--------|-------------|
| `id` | Monitoring station ID |
| `date` | Timestamp of observation |
| `NH4`, `BSK5`, `Suspended` | Additional water quality metrics |
| `O2`, `NO3`, `NO2`, `SO4`, `PO4`, `CL` | Target pollutants (multi-output regression) |
| `year`, `month` | Extracted from date |

 🔍 Key Milestones

✅ **Week 1**
- Loaded and cleaned the dataset
- Visualized correlations between features
- Built a baseline `MultiOutputRegressor` using `RandomForestRegressor`
- Evaluated model using R² and MSE for each target

 🔁 **Week 2**
- Performed feature engineering (`year`, `month`)
- Sorted by `id` and `date`
- Dropped rows with missing values only in key pollutant columns
- Enhanced model input with temporal features
- Improved model accuracy across targets

📈 Model Evaluation

Each target pollutant is evaluated using:

- **R² Score**: Coefficient of determination
- **MSE**: Mean Squared Error

Results show good performance, with potential for improvement via hyperparameter tuning and more advanced regressors.

🚀 Next Steps

- Hyperparameter tuning for Random Forest
- Try alternate models like XGBoost or LightGBM
- Forecast pollutant levels for future dates
- Build interactive dashboard for real-time monitoring (Power BI / Streamlit)

 📅 Internship Details

- **Internship Type**: AICTE Virtual Internship – Edunet Foundation
- **Sponsor**: Shell
- **Duration**: June 2025 (1 month)
- **Focus Area**: Machine Learning for Environmental Monitoring



