# Smart Supply – Inventory Management System

## 👥 Team Details

**Team Number:** 92
**Team Name:** Smart Supply
**Members:**

* Sharavari Kulkarni
* Srushti Raut
* Priya Gundale
* Himani Gupta

---

## 📌 Problem Statement

Grocery stores often face two major issues:

* Products go **out of stock**, leading to lost sales
* Products **expire on shelves**, causing wastage

This happens due to lack of **real-time inventory tracking** and inefficient manual systems.

---

## 💡 Solution

Smart Supply is a **full-stack inventory management system** that provides:

* Real-time stock tracking
* Automated alerts
* Smart demand prediction

All operations are optimized using **custom-built Data Structures in Java** for efficient performance.

---

## 🛠️ Tech Stack

* **Backend:** Java 21, Spring Boot, Maven
* **Frontend:** React, Vite, JavaScript
* **Core Concepts:** Data Structures & Algorithms

---

## ⚙️ Key Features

### 🔹 Product Management

* Add, update, delete, and search products
* Implemented using **HashMap (O(1))**

### 🔹 Billing System

* Fast product lookup and quantity update
* Logs every transaction with timestamp

### 🔹 Undo Last Transaction

* Uses **Stack (O(1))** to reverse last sale

### 🔹 Low Stock Alerts

* Uses **MinHeap** to track minimum stock items
* Alerts triggered automatically

### 🔹 Expiry Alerts

* Separate **MinHeap** tracks expiring products

### 🔹 Sales Analytics

* Uses **TreeMap** for date-range queries

### 🔹 Range Queries

* **AVL Tree** enables efficient price/stock filtering

### 🔹 Demand Prediction

* Uses **sliding window technique (ArrayList)**
* Predicts future demand based on past sales

---

## 🧠 Data Structures Used

| Data Structure | Purpose           | Complexity |
| -------------- | ----------------- | ---------- |
| HashMap        | Product storage   | O(1)       |
| Stack          | Undo operation    | O(1)       |
| MinHeap        | Alerts system     | O(log n)   |
| AVL Tree       | Range queries     | O(log n)   |
| TreeMap        | Sales history     | O(log n)   |
| ArrayList      | Demand prediction | O(n)       |

---

## 📂 Project Structure

```
Team 92 - Smart Supply
├── backend/
│   └── src/main/java/com/inventory/
├── frontend/
│   └── src/
├── pom.xml
└── README.md
```

---

## 🚀 How to Run

### Backend:

1. Navigate to backend folder
2. Run:

```
mvn spring-boot:run
```

### Frontend:

1. Navigate to frontend folder
2. Run:

```
npm install
npm run dev
```

---

## 🎯 Future Improvements

* AI-based demand prediction
* Mobile app integration
* Cloud deployment

---

## 🏁 Conclusion

Smart Supply improves inventory efficiency by combining **DSA + real-time systems**, helping businesses reduce losses and optimize operations.

---

## 📎 Submission Info

This project is submitted for **Buffer 7.0 Hackathon**
Drive link:https://drive.google.com/file/d/1rWKcrnQAR7uIp8y6emI3YU04mKAcId6t/view?usp=sharing
