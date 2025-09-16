
# 🛡️ Phishing Website Detection using AI/ML

This project implements a **Random Forest-based Machine Learning model** to detect phishing websites using URL-based features. It leverages a curated dataset of phishing and legitimate URLs, extracts features, and trains a classifier that achieves **96.8% accuracy**.  

The repository includes the **Jupyter Notebook**, **research report**, **dataset**, and an **illustrative figure**, showcasing end-to-end phishing detection.

---

## 📂 Repository Structure

├── Phishing_Detector_Enhanced_Colab.ipynb # Jupyter Notebook (model training + testing)  
├── Phishing_RF_Report.docx # Research report with methodology & results  
├── PhiUSIIL_Phishing_URL_Dataset.csv # Dataset of phishing & legitimate URLs  
├── c8cf1012-1865-4202-86ba-617638220d2e.png # Project image/logo  
└── README.md # Project documentation

## 📖 Abstract
Phishing attacks are one of the most common cybercrimes, targeting users to steal sensitive data.  
This project explores a **machine learning approach using Random Forest** to classify URLs as phishing or legitimate.  

- **Accuracy:** 96.8%  
- **Precision:** 95.7%  
- **Recall:** 97.2%  
- **F1-Score:** 96.4%  

These results demonstrate the model’s capability to be deployed in **real-time detection systems** such as browser extensions or email filters.

---

## ⚙️ Features Extracted
The following URL-based features are used for classification:
- Presence of IP address in URL  
- Use of `@` symbol  
- URL length  
- Number of subdomains  
- Presence of HTTPS  
- Hyphen usage in domain  
- Redirection in path (`//`)  


### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/Phishing-Website-Detection-AI.git
cd Phishing-Website-Detection-AI
```
### 2. Run the Notebook

Open Jupyter Notebook and run:
```bash
jupyter notebook Phishing_Detector_Enhanced_Colab.ipynb
```

## 🏫 Authors

- **Muzammil Akhtar**
    
- **Ibtisam Khaleeq**
      
- **Momin**
    

**Institution:** Air University, Islamabad


