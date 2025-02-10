# **Predicting Solar Power Output using Linear Regression** ☀️🔍  

## **Overview**  
This project predicts **solar power output** using **Linear Regression**. The model takes various environmental and technical parameters as input and provides an estimated power generation value.  

It includes:
- **Data Preprocessing** (Handling missing values, duplicate removal, visualization)
- **Machine Learning Model** (Linear Regression with Scikit-Learn)
- **Performance Evaluation** (R² Score, RMSE, MAE)
- **Interactive UI** (Built with Tkinter for user-friendly predictions)

---

## **Tools and Technologies Used** 🛠️  
- **Programming Language:** Python  
- **Libraries:**  
  - `pandas` → Data handling  
  - `numpy` → Numerical operations  
  - `matplotlib` & `seaborn` → Data visualization  
  - `scikit-learn` → Machine learning  
  - `tkinter` → GUI-based user interaction  
- **Jupyter Notebook** for interactive development  

---

## **Installation** ⚙️  
Follow these steps to set up the project on your local machine:

### **1. Clone the Repository**
```bash
git clone https://github.com/Dipan46/Predicting-Solar-Power-Output-using-Linear-Regression.git
cd solar-power-prediction
```

### **2. Install Dependencies**
```bash
pip install -r requirements.txt
```
> *(Make sure you have Python installed on your system.)*

---

## **Usage** 🚀  

### **Run the Model**
```bash
python solar_power_prediction.py
```
OR  
Run the **Jupyter Notebook**:  
```bash
jupyter notebook
```

### **Interact with the UI**
1. **Enter feature values** (e.g., temperature, humidity, irradiance).
2. Click **"Predict"** to get the estimated solar power output.
3. View predictions instantly in a pop-up message.

---

## **Methodology** 🔬  
1. **Data Loading**: Read dataset using `pandas`.  
2. **Exploratory Data Analysis**: Handle missing values, check distributions.  
3. **Feature Selection & Engineering**: Choose relevant variables for prediction.  
4. **Model Training**:  
   - Use `train_test_split` to divide data.  
   - Apply `LinearRegression` from Scikit-Learn.  
5. **Model Evaluation**:  
   - Calculate **Root Mean Squared Error (RMSE)**.  
   - Compute **R² Score** for accuracy.  
   - Measure **Mean Absolute Error (MAE)** for better error understanding.  
6. **GUI Integration**: Use `tkinter` for user-friendly input & output.  

---

## **Results** 📊  

### **Model Performance**  
| Metric               | Value |
|----------------------|-------|
| **Root Mean Squared Error (RMSE)** | `507.53` |
| **R-squared Score (R²)** | `0.718` |
| **Mean Absolute Error (MAE) - 1st run** | `391.79` |
| **Mean Absolute Error (MAE) - 2nd run** | `392.42` |

### **Interpretation**  
- **R² Score (`0.718`)**: The model explains **71.8% of the variance** in solar power output.  
- **RMSE (`507.53`)**: The model's average error magnitude is **507.53 kW**, indicating some scope for improvement.  
- **MAE (`~392 kW`)**: The average absolute difference between predictions and actual values is **around 392 kW**.  

> **Conclusion**: The model performs reasonably well but can be improved with feature engineering and additional data sources.

---

## **Screenshots** 🖼️  
### 📌 **Data Visualization**
![Heatmap](screenshots/heatmap.png)

### 📌 **Model Performance**
![Scatter Plot](screenshots/actual_vs_predicted.png)

### 📌 **User Interface**
![GUI](screenshots/gui.png)

*(Make sure to add actual screenshots in the `screenshots/` folder.)*

---

## **Contributing** 🤝  
We welcome contributions!  
1. Fork the repository.  
2. Create a new branch (`feature-branch`).  
3. Commit your changes and push them.  
4. Submit a pull request!  
