
---

## 📊 Dataset Information

- **Features**:
  - id: Unique identifier for each record
  - date: Transaction date (YYYY-MM-DD)
  - store_nbr: Store number
  - family: Product family/category
  - sales: Sales volume (can be zero)
  - onpromotion: Number of items on promotion
  - dcoilwtico: Oil price (may contain missing values)
- **Time Range**: 2013-01-01 to 2017-08-15
- **Rows & Columns**: 55,572 rows × 7 columns

---

## 🛠️ Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn)
- Time Series Modeling: ARIMA (statsmodels), LSTM (TensorFlow/Keras)
- Visualization: Matplotlib, Seaborn
- Jupyter Notebook

---

## 🔍 Key Insights

- Sales tend to increase significantly on weekends.
- No sales are recorded on major holidays (e.g., Dec 25 & Jan 1).
- Promotions have a stronger impact on sales than oil prices.
- LSTM outperforms ARIMA in capturing temporal trends in sales data.
- Sales trends show year-over-year growth for beverage products.

---


