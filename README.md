# 📊 Business Social Network Analysis with Gephi

> Network analysis of product co-purchases (**Q2**) and feature influence on buying decisions (**Q16**) using **Gephi**, based on e-commerce and car sales datasets.

---

## 📖 Project Overview

This repository contains **social network analysis** projects applied to real-world business datasets using **Gephi**.  
It focuses on two key questions:

- **Q2:** Which products are commonly purchased together in an e-commerce dataset?  
- **Q16:** Which product features most influence car purchase decisions in a car sales dataset?  

Both analyses involve:

- **Data preprocessing**  
- **Network construction**  
- **Visualization**  
- **Interpretation of results**

---

## 📌 Datasets

### 🛍️ E-Commerce Dataset (Q2)
**Source:** [An Online Shop Business – Gabriel Ramos (Kaggle)](https://www.kaggle.com/datasets/gabrielramos87/an-online-shop-business/data)  
**Description:** Transactional data from an online shop.

| Feature         | Description |
|-----------------|-------------|
| `TransactionNo` | Unique transaction ID (starting with 'C' → cancellations) |
| `Date`          | Transaction date & time |
| `ProductNo`     | Unique product ID |
| `ProductName`   | Product name or description |
| `Price`         | Unit price in GBP (£) |
| `Quantity`      | Units purchased (negative = cancellations) |
| `CustomerNo`    | Unique customer ID |
| `Country`       | Customer's country |

---

### 🚗 Car Sales Dataset (Q16)
**Source:** [Car Sales Report – MissionJee (Kaggle)](https://www.kaggle.com/datasets/missionjee/car-sales-report/data)  
**Description:** Sales data with car attributes and customer details.

| Feature         | Description |
|-----------------|-------------|
| `Car_id`        | Unique car ID |
| `Date`          | Sale date |
| `Customer Name` | Name of the buyer |
| `Gender`        | Gender of the buyer |
| `Annual Income` | Annual income |
| `Dealer_Name`   | Car dealer name |
| `Company`       | Car brand |
| `Model`         | Car model |
| `Engine`        | Engine specifications |
| `Transmission`  | Automatic / Manual |
| `Color`         | Exterior color |
| `Price ($)`     | Sale price |
| `Dealer_No`     | Dealer ID |
| `Body Style`    | Sedan, SUV, etc. |
| `Dealer_Region` | Dealer's geographic region |

---

## 📷 Visualizations

### **Q2 – Product Co-Purchase Network**
| | |
|---|---|
| ![Q2 Network 1](https://github.com/farzadmohseni-ir/business-social-network-analysis/blob/main/Q2/Image%20output/Screenshot%202025-08-08%20080200.jpg) | ![Q2 Network 2](https://github.com/farzadmohseni-ir/business-social-network-analysis/blob/main/Q2/Weighted%20Degree/Screenshot%202025-08-08%20105841.jpg) |
| ![Q2 Network 3](https://github.com/farzadmohseni-ir/business-social-network-analysis/blob/main/Q2/Combined/100/100-2.png) | ![Q2 Network 4](https://github.com/farzadmohseni-ir/business-social-network-analysis/blob/main/Q2/Betweenness%20Centrality/screenshot_120207.png) |

---

### **Q16 – Car Sales Feature Network**
| | |
|---|---|
| ![Q16 Network 1](https://github.com/farzadmohseni-ir/business-social-network-analysis/blob/main/Q16/Image%20output/5.jpg) | ![Q16 Network 2](https://github.com/farzadmohseni-ir/business-social-network-analysis/blob/main/Q16/Image%20output/7.jpg) |
| ![Q16 Network 3](https://github.com/farzadmohseni-ir/business-social-network-analysis/blob/main/Q16/Image%20output/6.png) | ![Q16 Network 4](https://github.com/farzadmohseni-ir/business-social-network-analysis/blob/main/Q16/Betweenness%20Centrality/3.png) |

---

## 🛠 Tools & Techniques
- **Gephi** – Visualization & metrics calculation  
- **Python** – Data preprocessing & network export  

💼 LinkedIn: [Your LinkedIn URL]  
🐙 GitHub: [Your GitHub Profile]
