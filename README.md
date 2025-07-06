# GHG Emissions Prediction 🌍

## 🧠 Project Overview

This project aims to predict greenhouse gas (GHG) emissions associated with industries and commodity supply chains using machine learning. By leveraging historical emissions data, it delivers actionable insights—empowering both researchers and decision-makers to monitor and mitigate environmental impact.

## 🚀 Folder & File Access

All essential project files including data, notebooks, models, and the Streamlit app are available here:
👉 [Google Drive Folder](https://drive.google.com/drive/folders/1KcZ9UjSjTfUjFwc8_isuBHMfFtK2y_6k?usp=sharing)

## 🔧 Project Structure

```
├── data/                 # Raw and processed datasets (Excel format .xlsx)
├── notebooks/            # Jupyter notebooks for data exploration & modeling
├── models/               # Saved model files (.joblib)
├── app.py                # Streamlit application code
└── requirements.txt      # Python dependencies
```

## 🧭 Methodology

1. **Data Collection**
   Sourced industrial and commodity emissions data (Excel files).

2. **Data Preprocessing**
   — Handling missing data
   — Encoding categorical features
   — Feature scaling and normalization

3. **Exploratory Data Analysis (EDA)**
   — Visualized trends and identified patterns
   — Used plots to explore industry and commodity variance

4. **Modeling**

   * **Linear Regression:** Baseline model for quick and interpretable results
   * **Random Forest Regressor:** Ensemble model for capturing complex, non-linear relationships

5. **Evaluation Metrics**
   — R² Score
   — Mean Absolute Error (MAE)
   — Root Mean Squared Error (RMSE)

6. **Hyperparameter Tuning**
   — Parameter optimization using `GridSearchCV`

7. **Deployment**
   — Developed a Streamlit web app for live prediction
   — Model serialization handled via `joblib`

## 🛠️ Tools & Technologies

* **Language & Environments:** Python, Jupyter Notebook, VS Code
* **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `joblib`, `streamlit`
* **File Formats:** `.xlsx` for datasets, `.joblib` for model files

## 📈 Usage Instructions

1. **Clone the repository** (or download from Drive).
2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Streamlit app:**

   ```bash
   python -m streamlit run app.py
   ```
4. **Use the interface** to upload your dataset and get real-time GHG prediction outputs.

## 📊 Model Performance

Here’s a snapshot of model effectiveness:

| Model                   | R² Score | MAE  | RMSE |
| ----------------------- | -------- | ---- | ---- |
| Linear Regression       | 0.76     | 1.42 | 2.01 |
| Random Forest Regressor | 0.91     | 0.89 | 1.12 |

**Random Forest’s** superior performance led to its selection for deployment.

## 🧩 Future Enhancements

* Incorporate additional features (e.g., energy source, production volume).
* Explore advanced algorithms (e.g., XGBoost, neural networks).
* Improve app UI/UX and include interactive visualizations.
* Scale deployment (e.g., hosted on cloud with REST APIs).

---

## 🙋‍♂️ Contact

For any queries or suggestions, feel free to reach out:
Divyani Prashant Deshmukh
divyanideshmukh8@gmail.com

