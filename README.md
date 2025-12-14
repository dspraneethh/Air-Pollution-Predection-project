**Air Pollution Prediction Project💨🏭:**

Purpose: Build and evaluate a machine-learning model to predict Air Quality Index (AQI) from city-level pollutant measurements and visualize trends.
Data: Uses a city-day air-quality dataset (local CSV) with features like PM2.5, PM10, NOx, CO, O3, Benzene, Toluene, Xylene, etc.

**What I Did:**

Data prep: Cleaned and preprocessed the dataset (dropped missing values, parsed dates).
Feature selection: Selected pollutant measurements as model inputs.
Scaling: Standardized features with StandardScaler.
Modeling: Trained an MLPRegressor (neural-network style) with warm-start partial fitting and recorded training/validation loss.
Evaluation: Captured train/validation MSE and plotted loss curves.
Visualization: Created time-series and box plots (Plotly) to show AQI trends and distributions.

**Agenda / Objectives:**

Predict: Provide accurate AQI predictions from pollutant readings.
Understand: Visualize temporal AQI trends and per-city distributions.

Executed outputs required: GitHub shows visuals only if the notebook contains saved outputs.
(The repo now includes a Line chart (time-series) and a Box plot (box-and-whisker) with a Loss curve (training/validation line plot).
Interactivity: Plotly interactivity is not supported inside GitHub’s notebook viewer; use the exported HTML for interactive charts.

**Conclusion:**

The project produces a working AQI prediction notebook, static and interactive visual reports, and a persisted model/scaler.
Next steps: improve model performance (feature engineering, cross-validation, hyperparameter search), add automated evaluation scripts, and deploy predictions as an API or dashboard.
