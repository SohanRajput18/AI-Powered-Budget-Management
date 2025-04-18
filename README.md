# 🧠 AI-Powered Budget Management

## Overview

AI-Powered Budget Management is a smart personal finance assistant that helps users track, analyze, and forecast their expenses using artificial intelligence. It combines automated categorization, predictive budgeting, and real-time alerts to empower users in managing their finances efficiently. The project is developed using modern web technologies including React.js, Node.js, MongoDB, and integrates AI through the OpenAI API and custom machine learning models.

---

## Table of Contents  
- [Introduction](#introduction)  
- [Functional Requirements](#functional-requirements)  
- [Non-Functional Requirements](#non-functional-requirements)  
- [System Design & Implementation](#system-design--implementation)  
  - [MVC Architecture](#mvc-architecture)  
- [Technology Stack](#technology-stack)  
- [Database Description](#database-description)  
- [Module Description](#module-description)  
- [Services](#services)  
- [Results and Discussions](#results-and-discussions)  
- [Testing](#testing)  
- [Conclusion & Future Scope](#conclusion--future-scope)  


---

## 📘 Introduction

The system addresses common issues faced in budgeting, such as manual tracking, overspending, and lack of insights. With this platform, users can link their financial data, receive intelligent insights, detect anomalies, and plan for future expenses based on spending patterns. This AI-based system acts as a financial coach available 24/7.

---

## Screenshots

#### Dashboard
![Dashboard](![Screenshot 2025-04-14 185332](https://github.com/user-attachments/assets/9743c950-90bd-43dc-83dd-9fc766bbfa9a)
)

---

## ✅ Functional Requirements

- **User Authentication:** Secure login and registration system.  
- **Expense Tracker:** Add, categorize, and edit income/expenses.  
- **Real-Time Budget Alerts:** Notifications when spending exceeds thresholds.  
- **Predictive Analysis:** Forecast future expenses using past trends.  
- **Chat & Voice Bot:** Interactive assistant for queries and financial suggestions.  
- **Data Visualization:** Pie charts and line graphs to represent user spending.  

---

## 🛡️ Non-Functional Requirements

- **Performance:** Dashboard renders within 5 seconds on 90% of devices.  
- **Security:** JWT-based authentication and encrypted storage.  
- **Usability:** Clean UI/UX with responsive design.  
- **Scalability:** Handles increased user and transaction data smoothly.  

---

## 🏗️ System Design & Implementation

### MVC Architecture

- **Model:** Handles database schema for users, transactions, and categories.  
- **View:** React-based dynamic user interface.  
- **Controller:** Manages logic for budget limits, categorization, analytics.

---

## 💻 Technology Stack

- **Frontend:** React.js, Chart.js, Tailwind CSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **AI/ML:** Python (Scikit-learn), OpenAI API  
- **Others:** JWT, RESTful APIs, Netlify/Render (for deployment)

---

## 🧾 Database Description

Collections include:

- **Users:** Basic info, preferences, budget limits  
- **Transactions:** Amount, category, type, date  
- **Predictions:** AI-generated forecasts  
- **Alerts:** Triggered when limits are crossed  

---

## 🧩 Module Description

- **User Module:** Registration, login, profile settings  
- **Expense Module:** Add/edit/delete transactions, view history  
- **Insights Module:** Analytics and trends  
- **Alert Module:** Notification engine  
- **Chatbot Module:** AI-based interaction  

---

## 🔧 Services

- **POST /transactions:** Add new expense/income  
- **GET /transactions:** Fetch transactions for a user  
- **POST /predict:** Get AI-predicted expenses  
- **GET /alerts:** Fetch recent alerts  
- **POST /chat:** Interact with chatbot  

---

## 📊 Results and Discussions

- **Increased accuracy** in budgeting with AI predictions.  
- **Time saved** by automating categorization and trend analysis.  
- **Positive user experience** noted during usability tests.

---

## ✅ Testing

Test cases include:

- **Form validation** (amount, category, date)  
- **AI model accuracy** for forecasted budgets  
- **Alert mechanism** testing on transaction thresholds  
- **Chatbot responsiveness** to various queries  
- **Security testing** for JWT tokens and DB access  

---

## 🧠 Conclusion & Future Scope

### Conclusion  
The system effectively simplifies personal finance by automating budgeting tasks, providing users with real-time insights and future predictions. It blends AI with intuitive design to make finance management accessible to all.

### Future Scope  

- Bank account integration (via Plaid API)  
- Offline mobile version  
- Multi-language support  
- Personalized financial tips via ML models  
- Dark mode and accessibility features
