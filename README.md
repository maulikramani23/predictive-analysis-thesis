
---

## 🔬 Methodology

1. **Data Collection:**  
   Machine logs, sensor data, and grinding outcomes collected from industrial roll grinding machines at Herkules.

2. **ETL & Database Setup:**  
   Design and implementation of a structured SQL schema for production data.

3. **Modeling & Evaluation:**  
   Supervised models evaluated include LSTM, GRU, Random Forest, XGBoost, SVM, GBR, and ensemble methods.

4. **Real-Time Feedback Loop:**  
   AI modules provide real-time validation of current process states with alerting for deviations from the "Golden State".

5. **Validation & Results:**  
   Performance metrics (MAE, RMSE, accuracy) were analyzed to compare model efficacy across varying configurations.

---

## 📊 Key Results

| Model Used           | Accuracy | MAE   | Notable Features                            |
|----------------------|----------|-------|----------------------------------------------|
| Random Forest        | High     | Low   | Good baseline performance, explainability    |
| Ensemble (GRU+XGB)   | High     | Low   | Best overall predictive performance       |
| LSTM                 | Very High| Very Low   | Time-series sensitivity, long memory depth   |

> 📌 The LSTM model yielded the lowest training error and highest predictive consistency for grinding time optimization.


## 🧭 Use Cases & Applications

- Intelligent Process Control in CNC Machines
- Predictive Quality Assurance in Industrial Automation
- Smart Factory Integration via MES/SCADA and SQL Data Pipelines
- Data-Driven Decision Making in Manufacturing Operations

---

## 🧾 Citation

**Maulik Ramani** (2025). *Analysis of Production Data and Predictive Analytics during the Production of Machine Tools*. MSc Thesis, University of Siegen. Supervised by Prof. Dr. Volker Wulf and Mr. Hussain Abid Syed.

---

## 📫 Contact

- 📧 Email: maulik.ramani23@gmail.com  
- 🔗 LinkedIn: [linkedin.com/in/yourusername](https://www.linkedin.com/in/maulik-ramani/)  
- 🏙️ Location: Siegen, Germany

---

## 📄 License

This project is released for academic and demonstration purposes only. For collaborations or industrial applications, please contact the author.

