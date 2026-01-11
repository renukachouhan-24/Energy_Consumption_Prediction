⚡ Smart Energy Consumption Forecasting
This project predicts future electricity demand using Machine Learning. By analyzing past consumption patterns and production sources, the model helps in balancing the grid and reducing energy wastage.

📌 Project Overview
Electricity is difficult to store at scale. This system provides a 24-hour ahead forecast to help power plants optimize production and avoid sudden grid failures or load shedding.

🚀 Key Features
Accurate Predictions: Achieved an R² Score of 95.71%.

Time-Series Analysis: Captures daily (Peak/Off-peak), weekly, and seasonal patterns.

Feature Importance: Analyzes which factors (Nuclear, Solar, Hour, etc.) impact energy demand the most.

🛠️ Tech Stack
Language: Python

Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib

Algorithm: Random Forest Regressor (Chosen for its ability to handle complex, non-linear energy patterns).

📊 Results & Visualization
The model's predictions closely follow the actual consumption trends.

Model Accuracy: 95.7%

Key Insight: Time (Hour) and Energy Production sources are the biggest drivers of demand.

(Note: You can see the 'Actual vs Predicted' graph in the Jupyter Notebook).

📂 Project Structure
Energy_Consumption_Prediction.ipynb: Complete code for data cleaning, training, and visualization.

Electricity.csv: The dataset used for training the model.

energy_model.pkl: The final trained model (Saved using Pickle).

README.md: Project documentation.

💡 Purpose of this Project
Balancing Supply & Demand: To produce only what is needed and reduce waste.

Grid Stability: To prevent power cuts during peak hours.

Cost Optimization: Helping power plants plan their fuel and resource usage efficiently.

Developed by: Renuka Chouhan

