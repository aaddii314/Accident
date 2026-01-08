# Traffic Accident Severity Prediction

##  What the project does
This project implements an end-to-end Machine Learning pipeline to analyze and predict the severity of traffic accidents. Based on data from Data.gov, the system classifies accidents into two categories:
1.  **Injury / Fatal** (High Severity)
2.  **Property Damage Only** (Low Severity)

The project includes extensive data cleaning (handling MNAR - Missing Not At Random), feature engineering, supervised modeling (XGBoost, KNN, Logistic Regression, Random Forest), and unsupervised anomaly detection (Isolation Forest & K-Means).

## Why the project is useful
Traffic accidents are chaotic events, but they follow statistical patterns. This project is useful for:
* **Emergency Response Optimization:** By predicting severity based on initial reports (weather, vehicle type, collision type), dispatchers can prioritize medical resources for high-risk incidents.
* **Policy Making:** The analysis highlights specific risk factors (e.g., Motorcycle involvement vs. Sideswipes) that can guide infrastructure improvements.
* **Data Integrity:** The project demonstrates a methodology for handling "lazy reporting" (unknown values) in police reports, providing a cleaner dataset for future research.

## How users can get started with the project

### Prerequisites
* Python 3.8 or higher
* Jupyter Notebook

### Installation Steps

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/aaddii314/Accident.git]
    cd Accident
    ```

2.  **Install dependencies:**
    Ensure you have the `requirements.txt` file in the directory.
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the analysis:**
    Open the main notebook to view the code, visualizations, and results.
    ```bash
    jupyter notebook ACCIDENT1.ipynb
    ```

## Project Structure
* `data/` - Folder containing the dataset.
* `ACCIDENT1.ipynb` - Main Jupyter Notebook with code and analysis.
* `requirements.txt` - Python dependencies.
* `Course Project.pdf` - Original project guidelines.

This project was created by: Orel Hagai & David Turgeman


*Submitted as the Final Project for the Advanced topics in Machine Learning (Data Mining) Course, 2026.*
