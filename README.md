# 🚀 Shan Enterprises ERP (Showcase Version)
This is Demo Repository for my work of a full-stack **Enterprise Resource Planning (ERP)** system developed to streamline logistics, billing, and dealer management operations for Shan Enterprises.

> ⚠️ This is a **showcase version** of the project. Core business logic and production-sensitive code are intentionally excluded.

---

## 📌 Overview

This ERP system is designed to automate and simplify complex business workflows such as:

- Transport and destination management  
- Dealer-based billing system  
- Work order range/slab calculations  
- Invoice generation with GST  

The system reduces manual effort, improves accuracy, and enhances operational efficiency.

---

## 🛠️ Tech Stack

**Frontend**
- React.js
- Component-based architecture
- Dynamic forms & reusable UI blocks

**Backend**
- Python
- Django
- Django REST Framework (DRF)

**Other Tools**
- JWT Authentication
- SQLite and Postgresql (optimized for large-scale data handling)
- Tauri (for desktop application packaging)
- ReportLab (PDF generation)

---

## ✨ Key Features

### 📦 Dealer & Place Management
- Full CRUD operations  
- Search, pagination, and filtering  
- Bulk selection and deletion  

### 🚚 Destination & Transport System
- Destination-based entries  
- Work order range (slab) system  
- Dealer selection based on distance  

### 🧮 Billing Engine
- Sub-bill creation and linking  
- Automatic calculations:
  - MT (Metric Ton)
  - KM (Distance)
  - MTK (MT × KM)
  - Amount (Rate × MTK)  
- GST integration  

### 📊 Data Organization
- Grouping entries by range/slab  
- Total per group and grand totals  
- Clean tabular structure  

### 🧾 Invoice & Export
- Real-time bill preview  
- Professional PDF generation  
- Amount in words  

---

## 🧠 System Highlights

- Designed for **scalability** (handles large dealer datasets)  
- Clean API architecture with filtering, sorting, pagination  
- Modular React components for maintainability  
- Optimized calculation workflows for logistics-based billing  

---


## Demo Link

https://shan-enterprises-erp-1.onrender.com/