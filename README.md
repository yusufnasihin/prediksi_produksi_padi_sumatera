🌾 Rice Production Prediction in Sumatra Using Machine Learning

📌 Project Overview

This project focuses on predicting rice production across the island of Sumatra, Indonesia, using machine learning techniques. It aims to analyze the relationship between agricultural and environmental factors, including harvested area, humidity, rainfall, and average temperature, and their influence on rice production.

Developed using Python and Google Colab (Jupyter Notebook), this project compares the performance of Multiple Linear Regression and K-Nearest Neighbors (KNN) to identify the most effective model for predicting rice production.

The analysis provides insights into agricultural production patterns and demonstrates how machine learning can support data-driven decision-making in the agricultural sector.

🎯 Project Objectives

- Analyze the relationship between harvested area, humidity, rainfall, average temperature, and rice production.
- Explore agricultural and environmental data across Sumatera.
- Develop rice production prediction models using Multiple Linear Regression and K-Nearest Neighbors (KNN).
- Compare model performance using regression evaluation metrics.
- Identify the best-performing model for rice production prediction.
- Provide insights to support agricultural planning and productivity improvement.

🛠️ Technologies & Libraries
This project was developed using:

- Python – Main programming language.
- Google Colab / Jupyter Notebook – Development and analysis environment.
- Pandas – Data manipulation and preprocessing.
- NumPy – Numerical computations.
- Matplotlib – Data visualization.
- Seaborn – Statistical data visualization.
- Scikit-learn – Machine learning model development and evaluation.

📊 Dataset & Features

The analysis uses agricultural and environmental variables to predict rice production.

Feature	Description
- Luas Panen (Harvested Area):	Total agricultural land harvested for rice production
- Kelembapan (Humidity):	Average humidity level
- Curah hujan (Rainfall):	Total rainfall
- Suhu rata-rata (Average Temperature):	Average air temperature
- Produksi (Rice Production):	Target variable representing rice production
  
⚙️ Methodology

The project follows these main steps:

1. Data Collection – Gather agricultural and environmental datasets related to rice production in Sumatra.
2. Data Preprocessing – Clean the dataset, handle missing values, and prepare features for modeling.
3. Exploratory Data Analysis (EDA) – Examine data distributions, relationships, and correlations between variables.
4. Feature Selection – Identify relevant agricultural and environmental variables for prediction.
5. Model Development – Implement two regression algorithms:
6. Multiple Linear Regression
7. K-Nearest Neighbors (KNN)
8. Model Evaluation – Evaluate and compare model performance using R², MAE, and MSE.
9. Model Comparison – Determine the best-performing model based on evaluation results.

📈 Model Performance & Results

Two machine learning algorithms were evaluated to determine their effectiveness in predicting rice production.

Best-performing model: Multiple Linear Regression


Evaluation Metric	Result
- R² Score	0.868
- MAE	324,967.05
- MSE	1.57 × 10¹¹

The Multiple Linear Regression model achieved an R² score of 0.868, indicating that it explains approximately 86.8% of the variation in rice production within the evaluated dataset.

Based on the evaluation results, Multiple Linear Regression outperformed K-Nearest Neighbors (KNN) and was selected as the best-performing model in this comparison.

💡 Key Insights & Contributions

- Identified the relationship between agricultural and environmental factors and rice production.
- Compared two regression-based machine learning approaches.
- Demonstrated the effectiveness of Multiple Linear Regression for predicting rice production in the evaluated dataset.
- Developed a predictive model that can serve as an analytical tool to support agricultural planning and decision-making.
- Provided data-driven insights to support strategies for improving agricultural productivity in Sumatra.

🚀 How to Run the Project

Option 1: Google Colab
1. Clone or download this repository.
2. Open Google Colab.
3. Upload Project1_Remastered.ipynb.
4. Upload the required dataset
5. Run the notebook cells sequentially.

Option 2: Jupyter Notebook
1. Clone the repository

```bash
git clone https://github.com/yusufnasihin/prediksi_produksi_padi_sumatera.git
```
2. Navigate to the project directory
```bash
cd prediksi_produksi_padi_sumatera
```
3. Install the required libraries
```bash
pip install -r requirements.txt
```
4. Launch Jupyter Notebook

5. Open Project1_Remastered.ipynb and run the cells sequentially.

⚠️ Notes & Limitations

The model results represent performance on the evaluated dataset and do not guarantee the same accuracy on unseen future data.
The model is intended as an analytical and decision-support tool, not a replacement for agricultural expertise.
Further improvements could include testing additional machine learning algorithms, hyperparameter tuning, and incorporating more environmental variables.
