# Car Price Prediction 🚗💰

## 📌 Project Overview
This project aims to predict the selling price of cars based on various features such as year, present price, kilometers driven, fuel type, seller type, and transmission type. By leveraging Machine Learning models, this project helps in understanding factors influencing car prices and provides accurate predictions for better decision-making.

### 📊 Dataset
The dataset contains information about used cars, including the following columns:

Car_Name – Name of the car

Year – Year of manufacture

Present_Price – Current ex-showroom price (in lakhs)

Kms_Driven – Distance driven in kilometers

Fuel_Type – Petrol/Diesel/CNG

Seller_Type – Dealer/Individual

Transmission – Manual/Automatic

Owner – Number of previous owners

Selling_Price – Target variable (price of the car in lakhs)

### ⚙️ Methodology
Data Cleaning & Preprocessing

Removed irrelevant features

Handled categorical variables (Fuel, Seller, Transmission)

Checked for missing values

Exploratory Data Analysis (EDA)

Visualized distributions and correlations

Analyzed price trends with respect to year, fuel type, etc.

Model Building

Applied Linear Regression

Evaluated model using R² score and error metrics

Prediction

Built a function to predict car prices based on user input features

### 🛠️ Tech Stack
Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)

Jupyter Notebook

GitHub for version control

### ▶️ How to Run
1. Clone this repository
git clone https://github.com/your-username/car-price-prediction.git

cd car-price-prediction

2.Install required libraries
pip install -r requirements.txt

3. Open the notebook
jupyter notebook "Car Price Prediction.ipynb"
Run all cells to see the analysis and predictions

### 📈 Results
The Linear Regression model was able to capture the trend of car prices reasonably well.

R² score: [add your score here]

Visualizations helped understand which features impact car prices the most.

### 🚀 Future Improvements
Try advanced models (Random Forest, XGBoost)

Deploy as a web app using Streamlit/Flask

Use a larger dataset for better generalization

#### 👨‍💻 Author
Deepak GS
