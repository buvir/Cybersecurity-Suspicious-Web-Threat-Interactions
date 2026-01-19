# Cybersecurity: Suspicious Web Threat Interactions 🔐

## 📌 Project Overview
In modern cloud environments, cybersecurity threats are frequent and complex.  
This project focuses on analyzing web traffic data collected from AWS CloudWatch to identify **suspicious or malicious web interactions** using **data analytics and machine learning techniques**.

The project demonstrates how machine learning models can assist in **automated threat detection**, reducing manual monitoring efforts.

---

## 🎯 Objective
- Analyze suspicious web traffic logs
- Identify abnormal traffic patterns
- Detect potential cyber threats using Machine Learning
- Build a clean, end-to-end data analytics workflow

---

## 🗂 Dataset Description
- **Source:** AWS CloudWatch Web Traffic Logs
- **Records:** 282
- **Format:** CSV
- **Domain:** Cybersecurity / Data Analytics

### Key Features:
- `bytes_in` – Incoming traffic size  
- `bytes_out` – Outgoing traffic size  
- `src_ip` – Source IP address  
- `src_ip_country_code` – Country of origin  
- `protocol` – HTTP/HTTPS  
- `dst_port` – Destination port  
- `detection_types` – WAF detection rule  
- `creation_time`, `end_time` – Session timestamps  

---

## 🛠️ Technologies Used
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn  
- **Tools:** Jupyter Notebook, VS Code  
- **Domain:** Data Analytics & Machine Learning  

---

## 🔄 Project Workflow
1. Data Loading
2. Data Cleaning & Preprocessing
3. Feature Engineering
4. Exploratory Data Analysis (EDA)
5. Machine Learning Model Building
6. Model Evaluation
7. Insights & Conclusion

---

## 📊 Exploratory Data Analysis
- Distribution of Bytes In vs Bytes Out
- Country-wise traffic analysis
- Correlation heatmap
- Detection frequency patterns

---

## 🤖 Machine Learning Model
### Model Used:
- **Random Forest Classifier**

### Target Variable:
- `is_suspicious`  
  - 1 → Suspicious (WAF rule detected)  
  - 0 → Normal traffic  

### Evaluation Metrics:
- Accuracy
- Classification Report
- Confusion Matrix

📈 **Result:**  
The model achieved **high accuracy**, indicating strong pattern separation in the dataset.

---

## 📈 Results & Insights
- Strong correlation between incoming and outgoing traffic
- Certain countries generate higher suspicious traffic volume
- Machine learning effectively detects abnormal behavior
- Suitable for automated cybersecurity monitoring systems

---

## ✅ Conclusion
This project demonstrates the effectiveness of machine learning in identifying suspicious web activities within cloud environments.  
By combining data analytics with supervised learning models, organizations can improve real-time threat detection and response.

---

## 🔮 Future Enhancements
- Real-time traffic stream analysis
- Larger and more diverse datasets
- Deep learning models for packet-level inspection
- Integration with SIEM tools

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/buvir/cybersecurity-web-threat-detection.git
cd cybersecurity-web-threat-detection


2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run Jupyter Notebook
jupyter notebook


Open the final notebook and run cells step by step.

📁 Project Structure
├── CloudWatch_Traffic_Web_Attack.csv
├── Cybersecurity_Web_Threat_Detection.ipynb
├── requirements.txt
├── README.md
├── .gitignore

👤 Author

Name: Buvi
Domain: Data Analytics / Machine Learning
Project Type: Academic / Portfolio Project