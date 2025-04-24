---

**Abstract**
In the production of roll grinding machine, a significant challenge lies in selecting the optimal processing steps and parameter configurations to achieve high-quality results. Small adjustments to parameters often lead to notable variations in output quality, making it difficult for operators to consistently find the "Right" parameters that optimize performance. This thesis leverages artificial intelligence (AI) to analyze extensive production data collected throughout the machining processes, with the goal of establishing a “Golden State” (an ideal set of steps and parameters for achieving optimal processing results; a defined state within the context of the use case company). In order to achieve this objective, initially, a structured SQL database, which stores input parameters, measurement results, and derived analysis data was setup, where i have automated the collection and evaluation of production data. Then by integrating predictive AI models (like LSTM Networks, Random Forest, GRU Networks), the optimal parameters were defined, curated and featured but also to provide real-time feedback during production, validating if the current process remains on the optimal path. The results yielded minimum error rate with respect to optimal grinding time, indicating the implications for the so-called golden state. This thesis contributes to the practice-centered use of machine data with AI algorithms in order to establish the boundaries of data-driven manufacturing, validated through the context of our use case company. This approach promises to improve decision making for machine tool production, reduce variability, and enhance product quality through data-driven predictive insights. In the later stages, the AI will further suggest parameter adjustments needed to realign the process with the "Golden State". 

Keywords: Data Analysis, SQL Database, Data-driven Insights, Predictive Analytics

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

