🧠 Nutrition and Child Growth Analysis (Synthetic Public Health Project)


📌 Project Overview

This project simulates a public health data science pipeline focused on analyzing how nutrition, socioeconomic conditions, and health factors influence child growth outcomes such as stunting, wasting, and underweight status.

A large-scale synthetic dataset (10,000 records) is generated to model real-world relationships between:

Nutrition intake
Household conditions
Disease exposure
Growth outcomes

The project includes:

Synthetic data generation
Exploratory Data Analysis (EDA)
Machine learning prediction model
GIS-style malnutrition risk mapping


🎯 Objectives

Understand how nutrition impacts child growth
Identify key risk factors for malnutrition
Simulate real-world public health surveillance data
Build predictive models for child growth status
Visualize regional malnutrition risk using GIS techniques


📊 Dataset Description

The synthetic dataset includes:

👶 Demographics
Age (months)
Gender
Region (Urban, Rural, Semi-Urban)
Income level
Mother education level


🍎 Nutrition Indicators

Calorie intake
Protein intake
Meal diversity score
Breastfeeding duration
Vitamin A intake
Iron intake


🏥 Health Indicators

Diarrheal episodes
Immunization status
Sanitation access


📈 Growth Outcomes

Height (cm)
Weight (kg)
BMI
Stunting (Yes/No)
Wasting (Yes/No)
Underweight (Yes/No)
Growth status (Healthy / At Risk / Malnourished)


⚙️ Methodology

1. Synthetic Data Generation
Realistic distributions used for nutrition and health variables
Logical correlations embedded (e.g., poor nutrition → lower growth outcomes)
2. Exploratory Data Analysis (EDA)
Correlation analysis
Distribution of malnutrition categories
Regional disparities
Nutrition vs growth visualization
3. Machine Learning Model
Random Forest Classifier
Predicts child growth status
Feature importance analysis
4. GIS Heatmap Analysis
Risk scoring system for malnutrition
Region-based aggregation
Interactive heatmap visualization (Folium)

🧠 Key Insights

Rural regions show higher malnutrition risk
Low protein and calorie intake strongly predict stunting
Poor sanitation increases disease exposure and growth impairment
Dietary diversity is a strong protective factor


📦 Installation

pip install numpy pandas matplotlib seaborn scikit-learn folium
🚀 How to Run
Clone the repository
git clone https://github.com/bbjonah/Nutrition-and-Child-Growth-Analysis/.git
Run the Python script or Jupyter Notebook:
python main.py

or

jupyter notebook
Generate outputs:
Synthetic dataset CSV
EDA plots
ML model results
GIS heatmap HTML file


🗺️ GIS Output

The project generates an interactive file:

malnutrition_heatmap.html

This visualizes spatial malnutrition risk distribution across regions.

📈 Machine Learning Performance

Model: Random Forest Classifier
Output: Growth Status Prediction
Evaluation: Accuracy + Classification Report
Feature Importance: Nutrition + Health variables dominate predictions


🔮 Future Improvements

Integration with real WHO/UNICEF datasets
Time-series outbreak prediction
Deep learning-based risk modeling
Streamlit dashboard deployment
Real geospatial shapefile mapping (GeoPandas)


👨‍💻 Author

**Buka Jonah**


📄 License

This project is for educational and research purposes only.
