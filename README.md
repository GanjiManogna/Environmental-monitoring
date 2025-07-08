# Environment Monitoring: Air Quality Classification with AI

This project leverages Artificial Intelligence (AI) and Machine Learning to monitor and classify air quality using real-world environmental data. The workflow includes data preprocessing, exploratory data analysis (EDA), feature engineering, model building with Random Forest, and comprehensive evaluation and visualization of results.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [How to Run](#how-to-run)
- [Key Steps](#key-steps)
- [Results & Visualizations](#results--visualizations)
- [References](#references)

---

## Project Overview

The goal of this AI project is to automatically classify air quality into categories (Very Poor, Poor, Moderate, Good) based on environmental sensor data. The project demonstrates:
- Data loading and cleaning
- Exploratory data analysis (EDA)
- Feature engineering and scaling
- Building and evaluating a Random Forest Classifier
- Visualizing results and feature importance

This project was completed as part of my academic coursework in Artificial Intelligence.

---

## Technologies Used

- Python (Pandas, NumPy)
- Data Visualization: Matplotlib, Seaborn
- Machine Learning: scikit-learn (Random Forest)
- Jupyter Notebook or any Python IDE

---

## Dataset

- **File:** `air_quality_dataset.csv`
- **Source:** [Kaggle - Environmental Monitoring Data for Multiple Sites] 
- **Target Variable:** Air_Quality_Category (derived from a composite index)
- **Features:** All numeric environmental measurements (e.g., PM2.5, PM10, NO2, SO2, CO, O3, etc.)

---

## Project Structure

```
.
├── environment_monitoring_ai.py      # Python script with all code
├── air_quality_dataset.csv           # Dataset
└── README.md                        # Project documentation
```

---

## How to Run

1. **Install dependencies:**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
2. **Place `air_quality_dataset.csv` in your working directory.**
3. **Run the script:**
   ```bash
   python environment_monitoring_ai.py
   ```
   Or run the code in a Jupyter Notebook cell by cell.

---

## Key Steps

1. **Data Loading:**  
   Load the dataset using Pandas.

2. **Data Cleaning:**  
   - Convert date columns to datetime
   - Convert numeric columns to numeric dtype
   - Fill missing values with the mean

3. **Exploratory Data Analysis (EDA):**  
   - Visualize distributions and boxplots for all numeric variables
   - Plot correlation heatmap
   - Show class balance for air quality categories

4. **Feature Engineering:**  
   - Standardize numeric features
   - Create a composite air quality index
   - Categorize air quality into four classes

5. **Model Training:**  
   Train a Random Forest Classifier on the processed data.

6. **Model Evaluation:**  
   - Accuracy and classification report
   - Confusion matrix plot
   - Feature importance plot

---

## Results & Visualizations

- **Distribution Plots:** For all numeric features
- **Boxplots:** For outlier detection
- **Correlation Heatmap:** To understand feature relationships
- **Class Balance Plot:** For air quality categories
- **Confusion Matrix:** For model performance
- **Feature Importance Plot:** To interpret model decisions

*(You can add screenshots of your plots here if desired.)*

![Screenshot 2025-07-08 175835](https://github.com/user-attachments/assets/9c876684-61c9-4ab5-95ad-b61a9d2524a9)
![Screenshot 2025-07-08 175847](https://github.com/user-attachments/assets/46fded55-870d-4f3e-8d83-3a734d257bc0)
![Screenshot 2025-07-08 175900](https://github.com/user-attachments/assets/378fd782-07f7-4401-acb4-717974ea674e)

---


**This project was completed as part of my Artificial Intelligence coursework.**
