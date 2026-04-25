# ⚡ ML Pipeline Studio

An interactive **end-to-end Machine Learning pipeline builder** built using **Streamlit**.
This app allows users to go from raw data → preprocessing → model training → evaluation → prediction — all in a guided UI.

## 🚀 Features

### 🧭 Guided Pipeline (Step-by-Step)

1. Problem Type Selection (Classification / Regression)
2. Data Upload (CSV or Sample Datasets)
3. Exploratory Data Analysis (EDA)
4. Data Cleaning & Engineering
5. Feature Selection
6. Train-Test Split
7. Model Selection
8. Training with K-Fold Cross Validation
9. Performance Evaluation
10. Hyperparameter Tuning
11. Real-time Predictions

## 📊 Key Capabilities

* 📁 Upload your own dataset or use built-in datasets
* 🔍 Automatic problem type detection
* 📈 Interactive visualizations (Plotly)
* 🧹 Missing value handling & outlier detection
* 🧠 Feature selection (Variance, Correlation, Mutual Info)
* 🤖 Multiple ML models:

  * Logistic Regression
  * Linear Regression
  * Random Forest
  * SVM
  * KNN
  * Ridge Regression
* 🔁 K-Fold Cross Validation
* ⚙️ Hyperparameter tuning (Grid / Random Search)
* 📉 Model performance diagnostics (overfitting/underfitting)
* 🎯 Real-time prediction interface

## 🏗️ Tech Stack

* **Frontend/UI**: Streamlit
* **Data Processing**: Pandas, NumPy
* **Visualization**: Plotly
* **Machine Learning**: Scikit-learn

## 📂 Project Structure

ml-pipeline-studio/
│── app.py                # Main Streamlit app (your code)
│── requirements.txt     # Dependencies
│── README.md            # Project documentation

## 🧠 How It Works

The application uses a **state-driven pipeline system**:

* Each step is controlled via `st.session_state`
* User inputs are stored and passed across steps
* Models are trained using **Scikit-learn**
* Visualizations are dynamically generated using **Plotly**

## 📌 Example Workflow

1. Select **Classification**
2. Load **Iris dataset**
3. Perform EDA (distribution, correlation)
4. Clean data & remove outliers
5. Select important features
6. Split dataset
7. Train Random Forest
8. Evaluate accuracy
9. Tune hyperparameters
10. Make predictions

## 🎯 Use Cases

* ML beginners learning pipelines
* Rapid prototyping of ML models
* Teaching & demonstrations
* Data science projects
  
## 🔄 Future Improvements

* Add Deep Learning models (TensorFlow / PyTorch)
* Model export (pickle / joblib)
* API deployment (FastAPI)
* AutoML integration
* Save & reload pipelines

## ⚠️ Notes

* Works best with clean, structured datasets
* Large datasets may slow down UI performance
* Ensure numeric features for PCA & modeling steps
