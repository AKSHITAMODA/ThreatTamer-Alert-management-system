# ⚠️ ThreatTamer - Smart Alert Management System

ThreatTamer is an **AI-powered intelligent alert classification and suppression system** designed to filter out false positives from noisy security logs. Built using **Python, scikit-learn, SHAP, and Streamlit**, the system integrates rule-based logic, machine learning, and real-time feedback loops to assist security analysts in managing high-volume alert streams.

![ThreatTamer Demo](https://github.com/AKSHITAMODA/ThreatTamer-Alert-management-system/assets/demo.gif)

---


[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/ML-scikit--learn-yellow?logo=scikit-learn)](https://scikit-learn.org/)
[![Streamlit](https://img.shields.io/badge/UI-Streamlit-orange?logo=streamlit)](https://streamlit.io/)
[![SHAP](https://img.shields.io/badge/Explainability-SHAP-red)](https://github.com/slundberg/shap)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)


---

## 💻 Tech Stack

| Category             | Tools & Frameworks                              |
|----------------------|--------------------------------------------------|
| **Language**         | Python 3.10                                      |
| **ML & Explainability** | scikit-learn, SHAP                            |
| **Frontend / UI**    | Streamlit, pyngrok (for Google Colab tunneling) |
| **Data Handling**    | pandas, numpy, pyyaml                            |
| **Visualization**    | matplotlib, SHAP                                 |
| **Model Persistence**| joblib                                           |
| **Deployment**       | Google Colab / Local / Streamlit Sharing         |
| **Logging & Versioning** | model_metrics_log.csv, audit_log.txt         |
| **Config Management**| YAML (rules.yaml)                                |

---



## 🚀 Features

- ✅ **ML-Powered Alert Classification** (Random Forest Classifier)
- 🧠 **SHAP Explainability** for transparency
- ⚙️ **Rule-based Overrides** (ignore known ports, whitelisted IPs)
- 🔁 **Feedback-based Retraining** from analysts
- 📥 **Real-Time Alert Simulation** using CSV ingestion
- 📊 **Streamlit GUI** for user-friendly interaction
- 🧾 **Audit Logging** & classification history
- 📦 **Model Versioning** and performance tracking

---

## 🚧 Roadmap / Future Enhancements

- [ ] Enable multi-class alert risk categorization
- [ ] Add anomaly detection with Isolation Forest
- [ ] Integrate with Elastic SIEM via API
- [ ] Build analyst feedback dashboard (interactive SHAP)
- [ ] Auto-retrain scheduling via cron or Streamlit button
- [ ] Dockerize for deployment on SOC servers

---

## 📬 Contact

Made with ❤️ by [Akshita Moda](https://linkedin.com/in/akshita-moda-a4997a28a/)

Live Video Demonstration: https://drive.google.com/file/d/1LsCaHPzR9E-ntjrzu4gYioJ_ab3jjJeM/view?usp=sharing

For support, feedback, or questions:
📧 akshitamoda@gmail.com  
🐙 [GitHub](https://github.com/AKSHITAMODA)

--- 

## 📂 Project Structure

```bash
ThreatTamer/
├── app.py                      # Streamlit App
├── train_model.py              # Training script
├── classify_alerts.py          # Classification logic
├── preprocess.py               # Data preprocessing
├── alerts.csv                  # Sample alert dataset
├── rules.yaml                  # Custom rule definitions
├── classified_alerts.csv       # Output after classification
├── audit_log.txt               # Logs with timestamp and decisions
├── models/
│   └── alert_classifier.pkl    # Trained ML model
├── shap_realtime_explanation.png
└── README.md


