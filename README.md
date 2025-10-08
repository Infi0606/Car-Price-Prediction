🚗 Car Price Prediction ML Model
📌 Overview

The Car Price Prediction project is a machine learning-based regression model that predicts the selling price of a used car based on various features such as year, mileage, engine capacity, power, transmission type, fuel type, and seller type.

The project demonstrates the complete end-to-end data science workflow — from data collection and cleaning, to EDA (Exploratory Data Analysis), feature engineering, model training, and deployment using a Tkinter-based desktop application and Power BI dashboards for visualization.

🧠 Features

✅ Data Cleaning & Preprocessing: Handled 4+ lakh unstructured rows (missing values, duplicates, data formatting).

📊 Exploratory Data Analysis (EDA): Identified insights such as price trends by vehicle age, fuel type, and transmission type.

🧩 Feature Engineering: Created and encoded categorical variables for model input.

🤖 Model Building: Implemented and compared multiple regression models:

Linear Regression

Ridge & Lasso Regression

Support Vector Regressor (SVR)

Decision Tree Regressor

Random Forest Regressor

🏆 Best Model: Random Forest Regressor achieved the highest accuracy for predicting car prices.

💻 Deployment: Built a Tkinter desktop application to allow users to input car details and get instant price predictions.

📈 Visualization: Created Power BI dashboards to visualize pricing trends, seller performance, and market segmentation.

🧰 Tech Stack

Languages: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Tkinter

Visualization Tools: Power BI

Database: MySQL (for storing and querying data)

📂 Project Structure
Car-Price-Prediction/
│
├── data/                     # Dataset files
├── notebooks/                # Jupyter notebooks for EDA and model training
├── scripts/                  # Python scripts for preprocessing and training
├── app/                      # Tkinter desktop app code
├── dashboards/               # Power BI visualizations
├── README.md                 # Project documentation
└── requirements.txt          # Dependencies

🚀 How to Run

Clone this repository:

git clone https://github.com/Infi0606/Car-Price-Prediction
cd Car-Price-Prediction


Install dependencies:

pip install -r requirements.txt


Run the application:

python app/main.py

📊 Results

Model Used: Random Forest Regressor

Accuracy: ~93%

Key Insight: Car price decreases with age and varies strongly with fuel type and seller type.

🧾 Power BI Dashboard

Visualized average selling price across brands, fuel types, and transmission modes.

Included interactive filters for year, seller type, and fuel type.

🏅 Achievements

Processed and analyzed 4+ lakh records efficiently.

Achieved 93% model accuracy.

Deployed a fully functional Tkinter GUI for real-time predictions.

🔗 Links

📁 Dataset Source
 https://raw.githubusercontent.com/mohitmahiyt/cardataset/refs/heads/main/cars_dataset.csv

🧠 Power BI Dashboard
 <img width="1917" height="1037" alt="1" src="https://github.com/user-attachments/assets/6590ccfb-5909-421e-bee2-a991a42672ef" />
<img width="1918" height="1000" alt="3" src="https://github.com/user-attachments/assets/4e1bc4fb-2ad1-4ad8-b5fe-013368ce7270" />


💻 Tkinter App Screenshot
 <img width="1918" height="1030" alt="dashboard" src="https://github.com/user-attachments/assets/8c10cfc9-be7f-41dd-8acc-8869bdd6706f" />


📜 License

This project is licensed under the MIT License – feel free to use and modify with attribution.
