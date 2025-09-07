# Webshop Cart Anomaly & Notification System

This project uses an **Isolation Forest model** to detect anomalies in webshop cart activity and also **triggers email alerts** when abnormal patterns occur — such as **too many orders** (suspicious spike) or **zero orders** (possible outage).

## 🚀 Features
- Detects unusual webshop order/cart behavior using Isolation Forest.
- Identifies edge cases like **zero orders** or **sudden order spikes**.
- Sends email notifications when anomalies are detected.

## 📂 What’s inside
- **Notebook**: `notebooks/webshop_cart_anomaly.ipynb`  
- **Training**: Example workflow to fit an Isolation Forest on webshop data.  
- **Notifications**: Email alert logic when anomalies cross a threshold.  

## ⚡ Quickstart
1. Open the notebook in Google Colab.  
2. Upload or connect your webshop order dataset (CSV).  
3. Run all cells to:
   - Train the anomaly detection model
   - Evaluate recent order activity
   - Trigger an **email notification** if:
     - Orders = 0  
     - Orders exceed a defined limit  

## 🔔 Notifications
You can configure:
- **Recipient email**  
- **Thresholds** (e.g., orders > 1000 or = 0)  

Notification is sent automatically when conditions are met.

## 📜 License
MIT
