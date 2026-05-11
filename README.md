# 🚦 Traffic Congestion Prediction using Machine Learning & Deep Learning

A Machine Learning and Deep Learning based traffic forecasting system developed using the **Metro Interstate Traffic Volume Dataset** to predict traffic congestion trends from historical traffic and weather data.

The project applies data preprocessing, exploratory data analysis, feature engineering, and predictive modeling techniques to analyze traffic patterns and forecast congestion levels effectively.

---

# 📌 Project Highlights

✅ Traffic Congestion Prediction using historical traffic data  
✅ Time-Series Forecasting using LSTM  
✅ Comparative analysis of ML and DL models  
✅ Exploratory Data Analysis & Visualization  
✅ Feature Engineering for temporal patterns  
✅ Implemented using Google Colab  

---

# 🧠 Models Implemented

### 🔹 Linear Regression
- Baseline regression model
- Assumes linear relationship between traffic features and target variable

### 🔹 Random Forest Regressor
- Ensemble Machine Learning algorithm
- Handles non-linear traffic patterns effectively
- Reduces overfitting and improves prediction accuracy

### 🔹 LSTM (Long Short-Term Memory)
- Deep Learning model for sequential/time-series prediction
- Captures temporal dependencies in traffic data
- Achieved best overall prediction performance

---

# 📂 Dataset Information

### Dataset Used:
**Metro Interstate Traffic Volume Dataset**

### Dataset Features:
- Traffic Volume
- Date & Time
- Temperature
- Weather Conditions
- Rain/Snow Information
- Holiday Information

---

# ⚙️ Technologies & Libraries Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras
- Jupyter Notebook

---

# 🔍 Data Preprocessing

The following preprocessing techniques were applied:

- Handling missing values
- Date-time transformation
- Feature extraction
- Categorical encoding
- Feature scaling & normalization
- Train-test splitting

### Engineered Features:
- Hour of Day
- Day of Week
- Month
- Weather Categories

---

# 📊 Exploratory Data Analysis (EDA)

EDA was performed to analyze traffic behavior and congestion trends.

### Key Observations:
- Peak traffic observed during rush hours
- Weekdays show higher congestion than weekends
- Weather conditions significantly affect traffic volume
- Temporal patterns strongly influence congestion prediction

---

# 📈 Model Evaluation Metrics

Models were evaluated using:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

---

# 📌 Performance Comparison

| Model | Performance |
|------|-------------|
| Linear Regression | Moderate Accuracy |
| Random Forest Regressor | High Accuracy |
| LSTM | Best Performance |

### Final Observation:
LSTM outperformed other models due to its ability to capture sequential and temporal dependencies in traffic data.

---

# 📁 Project Structure

```bash
Traffic-Congestion-Prediction/
│
├── data/
│   └── Metro_Interstate_Traffic_Volume.csv
│
├── notebook/
│   └── Traffic_Congestion_Prediction.ipynb
│
├── README.md
└── .gitignore
```

---

# 🚀 Future Improvements

- Real-time traffic forecasting
- Integration with live traffic APIs
- Smart traffic management system
- Web application deployment
- Integration of accident/event-based traffic data

---

# 💡 Conclusion

This project demonstrates the effectiveness of Machine Learning and Deep Learning techniques in traffic congestion prediction.

The study highlights how temporal patterns, weather conditions, and historical traffic trends can be utilized to forecast congestion levels accurately. Among all implemented models, **LSTM achieved the best performance** for traffic forecasting tasks.

---

# 👩‍💻 Author

### Ankita Rani Patro

---

# 📚 References

- Metro Interstate Traffic Volume Dataset
- TensorFlow Documentation
- Scikit-learn Documentation
- Research Papers on Traffic Prediction
