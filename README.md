# Height and Weight Prediction using Linear Regression

A machine learning project demonstrating **Simple Linear Regression** using Python, Scikit-Learn, and Pandas to predict a person's height based on their weight.

## 📊 Project Overview
- **Exploratory Data Analysis (EDA):** Visualized the relationship between height and weight using Matplotlib and Seaborn scatter plots.
- **Correlation Analysis:** Discovered a strong positive correlation ($0.93$) between weight and height.
- **Data Preprocessing:** Handled data scaling using Scikit-Learn's `StandardScaler` and split the dataset into training and testing sets.
- **Model Training:** Trained a `LinearRegression` model using Ordinary Least Squares (OLS) optimization.
- **Model Evaluation:** Evaluated performance using key regression metrics:
  - **Mean Absolute Error (MAE):** $\approx 9.82$ cm
  - **Root Mean Squared Error (RMSE):** $\approx 10.47$ cm
  - **R² Score:** $\approx 0.776$ (Model explains ~77.6% of the variance)

## 🛠️ Technologies Used
- Python 3.14
- Pandas & NumPy
- Scikit-Learn
- Matplotlib & Seaborn

## 🚀 How to Run
Clone the repository and open `height_weight.ipynb` in Jupyter Notebook or JupyterLab to run the complete data pipeline and training steps interactively.
