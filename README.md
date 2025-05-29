# Accident-Severity-Analysis-and-Prediction-System
Exploratory analysis, geospatial clustering, and machine learning for accident severity prediction using Baltimore traffic data.


# Accident Severity Analysis and Prediction System

This project focuses on analyzing and predicting the severity of road accidents using crash data from Montgomery County, Baltimore. It combines exploratory data analysis, geospatial heatmaps, clustering, and machine learning classification models to identify risk factors and guide public safety interventions.

## Project Highlights
- Exploratory Data Analysis (EDA): Uncovered key variables like day of the week, time of day, speed zones, and weather contributing to accident severity.
- Geospatial Clustering: Applied DBSCAN and heatmaps to identify crash hotspots in Rockville, Bethesda, and Aspen Hill.
- ML Models Used: XGBoost, Gradient Boosting, Logistic Regression, Bagging Classifiers.
- Balanced Classes: Addressed class imbalance with SMOTE and Tomek Links.
- Best Model F1-score: 0.93 (Gradient Boosting)
- Interactive Dashboard: Visualized key insights using Power BI.

Power BI Dashboard:  
[Power BI Report Link](https://app.powerbi.com/groups/me/reports/e683edf3-2285-4ab7-b523-6765da4e0906/59a11f4f8e071190993b?ctid=5cdc5b43-d7be-4caa-8173-729e3b0a62d9&experience=power-bi&bookmarkGuid=be8209f5-aa9e-4a5e-b0de-316a1417e828)

## Technologies Used
- Python, Jupyter Notebook
- Pandas, NumPy, scikit-learn
- XGBoost, imbalanced-learn (SMOTE)
- DBSCAN, Seaborn, Matplotlib
- Power BI

## Files Included
- `CodeFile.ipynb`: Full project notebook (Tracked via Git LFS, must be downloaded to view)
- `eda_analysis.ipynb`: (Optional lighter version for quick viewing)
- `Predicting_accident_Severity.pdf`: Final report
- `EDA.docx`: Exploratory analysis report

## Data Source
[Montgomery County Crash Data](https://catalog.data.gov/dataset/montgomery-county-crash-data)

## How to Run
1. Clone the repository.
2. Open `CodeFile.ipynb` in Jupyter Notebook (after installing Git LFS).
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
4. Run the notebook cells to perform analysis and view model results.

**Future Improvements**
Deploy the model using Flask or Streamlit for interactive use.
Integrate real-time traffic data for dynamic predictions.
Add deep learning models for multi-class classification of injury types.
