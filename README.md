# Solar Power Output Prediction Using Linear Regression

## Project Overview
This project aims to predict solar power output (`generated_power_kw`) based on various meteorological and environmental features using **Linear Regression**. The dataset includes parameters such as temperature, humidity, cloud cover, wind speed, and solar radiation, which are used to model the relationship between these features and the generated solar power.

The project demonstrates the end-to-end process of data analysis, feature selection, model training, and evaluation, providing insights into how environmental factors influence solar power generation.

---

## Dataset
The dataset contains the following features:
- **Meteorological Data**:
  - Temperature at 2 meters above ground (`temperature_2_m_above_gnd`)
  - Relative humidity at 2 meters above ground (`relative_humidity_2_m_above_gnd`)
  - Mean sea level pressure (`mean_sea_level_pressure_MSL`)
  - Total precipitation (`total_precipitation_sfc`)
  - Snowfall amount (`snowfall_amount_sfc`)
  - Cloud cover (total, high, medium, low layers)
  - Shortwave radiation (`shortwave_radiation_backwards_sfc`)
- **Wind Data**:
  - Wind speed and direction at 10m, 80m, and 900mb levels
- **Solar Geometry**:
  - Angle of incidence, zenith angle, and azimuth angle
- **Target Variable**:
  - Generated solar power (`generated_power_kw`)

---

## Methodology
1. **Data Preprocessing**:
   - Handle missing values (if any).
   - Normalize or standardize features if necessary.
2. **Exploratory Data Analysis (EDA)**:
   - Visualize relationships between features and the target variable using pairplots and correlation heatmaps.
3. **Model Training**:
   - Split the data into training and testing sets.
   - Train a **Linear Regression** model to predict solar power output.
4. **Model Evaluation**:
   - Evaluate the model using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared.
   - Visualize model performance using scatter plots (actual vs predicted values) and residual plots.
5. **Feature Importance**:
   - Analyze the contribution of each feature to the model using regression coefficients.

---

## Results
- The Linear Regression model achieved an **R-squared value of X** and an **RMSE of Y**, indicating its ability to predict solar power output based on the given features.
- Key features influencing solar power generation include:
  - **Shortwave radiation**: Strong positive correlation with generated power.
  - **Temperature**: Moderate positive correlation.
  - **Cloud cover**: Negative correlation, as higher cloud cover reduces solar radiation.

---

## Visualizations
1. **Pairplot**: Visualizes relationships between selected features and the target variable.
2. **Correlation Heatmap**: Highlights the correlation between features and the target.
3. **Scatter Plot (Actual vs Predicted)**: Compares actual and predicted solar power output.
4. **Residual Plot**: Analyzes the distribution of errors (residuals) in the model.
5. **Feature Importance Plot**: Displays the contribution of each feature to the model.

---

## How to Run the Code
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/solar-power-prediction.git
