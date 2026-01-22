# Patent-Project
# 🏥 Medi-Alert

### *An Intelligent Real-Time Patient Monitoring and Alerting System*

---

## 📌 Technical Field of the Invention

The present invention relates to **artificial intelligence–assisted healthcare monitoring systems**, and more particularly to a **software-based method for real-time extraction, analysis, and alerting of patient vital signs from multiparameter patient monitors (MPM)** using optical character recognition (OCR) and machine learning.

---

## 📖 Background of the Invention

In modern hospitals and emergency care environments, patient vital signs are primarily monitored through multiparameter patient monitors. However, observation and interpretation of these vitals often rely on **manual human supervision**, which can lead to **delayed responses, missed critical changes, and recording errors**, especially in high-pressure settings such as ICUs, emergency wards, and ambulances.

Existing solutions typically require **direct hardware integration, proprietary protocols, or expensive infrastructure upgrades**, making them unsuitable for many hospitals, particularly in low-resource or rural regions.

---

## 💡 Summary of the Invention

**Medi-Alert** introduces a **lightweight, device-agnostic software solution** that automatically captures visual data from MPM monitor screens, extracts patient vitals using OCR, evaluates the patient’s health condition using machine learning, and generates **real-time alerts with escalation mechanisms** to assist healthcare professionals in making faster and safer clinical decisions.

The system operates **without modifying existing medical hardware**, enabling seamless deployment across different monitor brands and healthcare environments.

---

## ⚙️ Core Functional Components

### 1. Visual Data Acquisition

* Periodic capture of MPM monitor screen images
* Compatible with multiple monitor layouts and brands

### 2. Intelligent OCR-Based Vital Extraction

* Primary OCR using **EasyOCR** for robust digit recognition under varying lighting and display conditions
* Precision fallback validation for structured numeric patterns (e.g., blood pressure)
* Extraction of:

  * Heart Rate
  * Blood Pressure
  * SpO₂
  * Temperature
  * Respiration Rate

### 3. Machine Learning–Based Health Assessment

* Processed vitals are evaluated using trained ML classification models
* Patient condition categorized into:

  * **Normal**
  * **Warning**
  * **Danger**

### 4. Real-Time Alerting & Escalation

* Immediate alert to the assigned doctor on detecting a danger state
* Automated escalation to nurses or support staff if alerts are not acknowledged
* Prevents alert fatigue through intelligent re-alert timing

### 5. Pre-Hospital & Emergency Extension

* Designed to support ambulance-based monitoring
* Enables early hospital preparedness by transmitting vitals before patient arrival
* Supports emergency routing and bed availability awareness

---

## 🧠 Novelty & Key Advantages

* No dependency on proprietary monitor APIs or hardware modifications
* Works with **legacy MPM devices** through visual extraction
* Low computational overhead; suitable for **low-end systems**
* Reduces human error and response delay
* Extends monitoring beyond hospitals to ambulances and emergency care

---

## 🧪 Technologies Used

* Python
* OpenCV
* EasyOCR & Tesseract OCR (hybrid approach)
* Scikit-learn (Machine Learning)
* Streamlit (prototype dashboard)

---

## 🏥 Intended Applications

* Intensive Care Units (ICU)
* Emergency Departments
* Ambulances and pre-hospital care
* Rural and resource-constrained hospitals
* Health camps and temporary medical units

---

## 📄 Intellectual Property Notice

This project is **patent-protected**.
The contents of this repository are provided for **academic, research, and demonstration purposes only**.
Unauthorized commercial use, reproduction, or deployment without permission is prohibited.

---

## 📬 Contact

For academic collaboration, research discussion, or authorized usage inquiries, please request through G-mail - deathcreatorslegend@gmail.com
