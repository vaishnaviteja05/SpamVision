# 📧 SpamVision – AI-Powered Email Threat Classifier

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![ML](https://img.shields.io/badge/Model-ML%2FNLP-orange)

SpamVision is an **AI-based email classification system** that analyzes incoming emails and classifies them as **Spam**, **Phishing**, **Promotional**, or **Safe** using NLP + Machine Learning models.

It supports real-time monitoring and works with multiple email inboxes.

---

## 📜 About the Project

SpamVision intelligently categorizes emails into:

- 📮 **Safe** – Normal, legitimate emails  
- 🚫 **Spam** – Junk mail or bulk advertisements  
- 🎣 **Phishing** – Fraud attempts to steal data  
- 🛍️ **Promotional** – Marketing & offer-based emails  

The model uses a vectorizer + ML classifier trained on email datasets (available in the `training/` folder).

---

## 🚀 Features

- ✔ Machine Learning–based email classification  
- ✔ Real-time monitoring using Python script  
- ✔ Lightweight & fast  
- ✔ Works on any IMAP-supported inbox  
- ✔ Training scripts included  
- ✔ Notification support (desktop alerts)

---

## 🛠️ Tech Stack

- **Python 3.10+**  
- **Libraries:** scikit-learn, numpy, pandas, nltk  
- **Model Type:** ML classifier (trained model `.pkl`)  
- **Techniques:** Bag-of-Words / TF-IDF, preprocessing, tokenization  

---

## 📁 Repository Contents

| File/Folder | Description |
|------------|-------------|
| `spamvision_model.pkl` | Trained machine learning email classifier |
| `vectorizer.pkl` | Vectorizer used to preprocess email text |
| `spamvision_monitor.py` | Real-time email monitoring script |
| `training/` | Training scripts & datasets used for model development |
| `requirements.txt` | List of Python packages |
| `sample_emails.csv` | Sample training/validation dataset |
| `NotificationDetected.jpg` | Screenshot of desktop notification |
| `ZohoMailbox.png` | Screenshot of email inbox |
| `ProjectDemo.mp4` | Demo video of the system running |
| `.gitattributes` | Git attribute configuration |

---

## 📂 Project Structure

```plaintext
spamvision/
├── training/
├── spamvision_monitor.py
├── spamvision_model.pkl
├── vectorizer.pkl
├── sample_emails.csv
├── requirements.txt
├── ProjectDemo.mp4
├── ZohoMailbox.png
├── NotificationDetected.jpg
└── README.md
```
---

## 📸 Screenshots
![Zoho Mailbox](https://github.com/vaishnaviteja05/SmartVision-A-smart-email-classifier/blob/main/ZohoMailbox.png?raw=true)
![Notification Detected](https://github.com/vaishnaviteja05/SmartVision-A-smart-email-classifier/blob/main/NotificationDetected.jpg?raw=true)

---

## 📂 Installation

### Clone the repository
```bash
git clone https://github.com/vaishnaviteja05/SmartVision-A-smart-email-classifier.git
cd spam-vision
```
### Install Dependencies 
```bash
pip install -r requirements.txt
```
### Run the application
```bash
python spamvision_monitor.py
```
