# Tuberculosis (TB) Tracking, Prediction, and Treatment Analysis using AI and Transformers
# 📑 Project Overview
This project presents a comprehensive AI-driven framework to analyze, predict, and optimize the treatment success rates of Tuberculosis (TB), one of the deadliest infectious diseases worldwide. Leveraging Transformer-based deep learning models, this system not only predicts TB treatment outcomes with high accuracy but also aids in identifying risk factors, tracking spread patterns, and proposing treatment optimization strategies using generative models.

# 💡 Key Features
1. Tracking and Monitoring of TB Spread
   
Analysis of temporal and spatial data trends in TB incidence and treatment outcomes.

Visualization of yearly trends and success rates for better understanding of regional impacts.

Correlation of socio-economic and healthcare factors influencing TB.

2. Treatment Success Rate Prediction
   
Transformer-based deep learning model trained on diverse features such as healthcare access, co-infection rates, lifestyle factors, and demographics.

Predictive analytics to estimate Treatment Success Rate (%) for TB based on complex real-world datasets.

High model performance evaluated via MAE, MSE, and R² score to ensure robust and accurate predictions.

3. Generative AI for Treatment Optimization and Drug Discovery
   
Framework outlined for using Variational Autoencoders (VAEs) and Molecular GANs (MolGANs) for designing novel drugs and repurposing existing medications.

Personalization of TB treatment plans using synthetic patient data generated via AI for precision medicine.

# 🚀 Model and Pipeline
Data Preprocessing:
Handling missing values.
Encoding categorical variables (Gender, Country, Age Group).
Feature normalization using MinMaxScaler.
Model Architecture:
Transformer-based Encoder for understanding complex dependencies in healthcare data.
Layers used: MultiHeadAttention, LayerNormalization, Dense, GlobalAveragePooling1D.
Training and Evaluation:
Trained on real-world TB datasets with a focus on Treatment Success Rate prediction.
Evaluation Metrics:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R² Score (Coefficient of Determination)
# ![Screenshot 2025-03-08 140546](https://github.com/user-attachments/assets/caff73e8-a041-47cf-a4bd-3dd5b9aa3f22)
![Screenshot 2025-03-08 135536](https://github.com/user-attachments/assets/31738938-a2fc-4ff1-adc9-56cdf88c074a)
![Screenshot 2025-03-08 134951](https://github.com/user-attachments/assets/2bebb3ab-a36b-4645-bb4d-17d1a0ac743f)
📊 Visualizations
Distribution of Treatment Success Rate (Histogram).
Yearly Trends of TB Treatment Success Rates (Line Plot).
Data-driven insights on how treatment rates have evolved over time globally or regionally.
