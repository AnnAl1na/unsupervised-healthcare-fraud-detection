# unsupervised-healthcare-fraud-detection
Unsupervised anomaly detection on healthcare provider data using machine learning techniques. Covers exploratory data analysis (EDA), encoding, standardization, anomaly detection using ML models, hyperparameter tuning, autoencoder-based anomaly detection, and model comparison. Includes detailed visualizations and evaluations.

## Setup Instructions

### 1. Create a Virtual Environment
It is recommended to use a virtual environment to manage dependencies.

```sh
python -m venv venv
```

### 2. Activate the Virtual Environment
- **Windows:**
  ```sh
  venv\Scripts\activate
  ```
- **Mac/Linux:**
  ```sh
  source venv/bin/activate
  ```

### 3. Install Required Packages
Ensure all required dependencies are installed using:

```sh
pip install -r requirements.txt
```

## Project Files and Execution Order

### 1. Exploratory Data Analysis (EDA)
**File:** `1_EDA.py`
- Performs initial data exploration, statistical summaries, and visualization.
- Helps understand the distribution of data and possible anomalies.

### 2. Encoding and Standardization
**File:** `2_Encoding_Standardization.py`
- Applies encoding to categorical features.
- Standardizes numerical features for better model performance.

### 3. Machine Learning-Based Anomaly Detection
**File:** `3_ML_Anomaly_Detection.py`
- Implements unsupervised ML techniques: Isolation Forest, LOF, DBSCAN, and One-Class SVM.
- Identifies anomalies in the dataset.

### 4. ML Algorithm Comparison
**File:** `4_ML_Algorithm_Comparison.py`
- Compares different anomaly detection models.
- Evaluates models using clustering metrics and visualizations.

### 5. Hyperparameter Tuning
**File:** `5_Hyperparameter_Tuning.py`
- Optimizes hyperparameters of ML models to improve detection accuracy.

### 6. Autoencoder-Based Anomaly Detection
**File:** `6_Autoencoder_Anomaly_Detection.py`
- Uses deep learning autoencoders for anomaly detection.

## Dataset
- **File:** `Healthcare_Providers.csv`
- Contains healthcare provider data used for anomaly detection.


## How to Run the Scripts
After setting up the virtual environment and installing dependencies, run each script in sequence:
```sh
python 1_EDA.py
python 2_Encoding_Standardization.py
python 3_ML_Anomaly_Detection.py
python 4_ML_Algorithm_Comparison.py
python 5_Hyperparameter_Tuning.py
python 6_Autoencoder_Anomaly_Detection.py
```

## Contributions
Feel free to fork this repository, raise issues, or submit pull requests for improvements.

---
### Author
**Aleena Ann Tomy** 

