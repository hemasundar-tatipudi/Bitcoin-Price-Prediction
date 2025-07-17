# Bitcoin Price Prediction

A Python-based data science project that uses multiple linear regression to predict Bitcoin’s market price using historical blockchain and market data.

---

## 📝 Project Summary

**Bitcoin Price Prediction** analyzes historical Bitcoin data and applies machine learning techniques to forecast Bitcoin’s market price. The project includes data visualization, preprocessing, feature engineering, regression modeling, and model evaluation, all implemented using Python’s popular data science libraries. The workflow demonstrates how blockchain features like market capitalization, transaction counts, and mining difficulty can be used to predict price movements.

---

## ⚙️ Tech Stack

* **Programming Language:** Python
* **Data Manipulation:** pandas, numpy
* **Visualization:** matplotlib, seaborn
* **Modeling:** statsmodels, scikit-learn
* **Environment:** Jupyter Notebook or Python script

---

## 🚀 Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/Bitcoin-Price-Prediction.git
   cd Bitcoin-Price-Prediction
   ```

2. **Install required packages:**

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
   ```

3. **Run the notebook or script:**

   * Open the Jupyter notebook, or run the script with your Python environment.
   * The script loads and preprocesses Bitcoin data, builds a linear regression model, evaluates it, and predicts future prices.

---

## 📂 How It Works

* **Data Loading:**
  Imports Bitcoin historical data directly from CSV URLs.

* **Visualization:**
  Uses Seaborn and Matplotlib for exploratory analysis to understand relationships between features and market price.

* **Preprocessing:**
  Handles missing values and prepares features for modeling.

* **Modeling:**
  Builds a multiple linear regression model to predict Bitcoin market price.

* **Evaluation:**
  Calculates Mean Squared Error (MSE) to evaluate model accuracy.

* **Prediction:**
  Uses the trained model to predict Bitcoin prices on a separate test set.

---

## 📈 Example Output

```
MSE: 529309.2821
The price on 1 february is 9234.21
The price on 2 february is 9500.34
...
```

---

## 🛠️ Features & Future Ideas

* Exploratory data visualization.
* Linear regression modeling.
* Model evaluation and test set prediction.
* **Potential extensions:**

  * Experiment with other ML models (Random Forest, XGBoost)
  * Add feature engineering or external data sources (news sentiment, etc.)
  * Deploy as a simple web app.
