# Smart_agro_advisor
Smart Agro Advisor is an AI-powered decision support system designed to assist farmers in making informed choices about crop selection, yield prediction, and financial planning. By leveraging machine learning, data analytics, and visualization tools, this project aims to enhance agricultural productivity and profitability.

Features
Crop Prediction: Suggests the best crop based on soil type, NPK levels, temperature, and rainfall.
Weather & Soil Analysis: Provides insights on climate and soil conditions.
Market Trend Analysis: Examines historical price trends and market conditions.
Financial Forecasting: Uses machine learning models to predict revenue based on crop yield and pricing.
Interactive Dashboard: Deployed using IPyWidgets for real-time predictions.
📂 Project Structure
bash
Copy
Edit
Smart-Agro-Advisor/
│── data/                      # Raw and processed agricultural datasets
│── models/                    # Trained ML models
│── notebooks/                 # Jupyter Notebooks for model development
│── visualizations/            # Charts and graphs for analysis
│── scripts/                   # Python scripts for preprocessing and training
│── deployment/                # IPyWidgets-based model deployment
│── README.md                  # Project documentation
│── requirements.txt           # List of dependencies
│── LICENSE                    # License information
🔧 Installation
Clone the repository:
bash
Copy
Edit
git clone https://github.com/yourusername/Smart-Agro-Advisor.git
cd Smart-Agro-Advisor
Install dependencies:
bash
Copy
Edit
pip install -r requirements.txt
Run Jupyter Notebook:
bash
Copy
Edit
jupyter notebook
Open and execute the notebooks to train models and explore visualizations.
📊 Dataset Used
Soil & Weather Data (NPK values, rainfall, temperature)
Crop Yield Statistics (Yield per hectare, crop-specific trends)
Market Data (MSP vs. selling price, farmer income trends)
⚙️ Model Training
Feature Selection: Identifying important variables affecting crop yield.
Algorithm Comparison: Evaluated different models (Random Forest, XGBoost, SVM) for best accuracy.
Time-Series Analysis: Forecasted market trends using ARIMA & regression models.
📈 Visualizations
Feature Distribution (Soil & climate impact on crop yield)
Rainfall vs. Crop Type
Temperature vs. Humidity by Crop
Market Trends Over the Years
🚀 Deployment
The model is deployed using IPyWidgets for interactive user inputs and predictions.

📜 License
This project is licensed under the MIT License.

🤝 Contributing
Contributions are welcome! Feel free to fork the repository, create a new branch, and submit a pull request.
