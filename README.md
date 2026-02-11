# 🚛 TransFleet Pro – Fleet Management System

## 📌 Project Overview

**TransFleet Pro** is a desktop-based Transportation & Fleet Management System developed using Java Swing and MySQL.

The system is designed to manage:

- Customers  
- Vehicles  
- Drivers  
- Routes  
- Delivery Orders  
- Payments & Expenses  

It automates order handling, optimizes fleet allocation, and generates analytical reports to support operational decision-making.

This project was developed as part of the **Enterprise Application Development (EAD) coursework** for the Diploma in Computer System Design.

---

## 🎥 Demo Video

Watch the full system demonstration here:  
[Click here to view the demo](PASTE_YOUR_VIDEO_LINK_HERE)


## 🏗️ System Architecture

The system follows the **MVC (Model–View–Controller)** architecture.

- **Model** → Entity classes representing database tables  
- **View** → Java Swing UI screens  
- **Controller (DAO Layer)** → Business logic and database operations  

This separation improves:

- Maintainability  
- Scalability  
- Code readability  
- Professional structure  

---

## 🛠️ Technology Stack

- **Language:** Java (JDK 8+)  
- **UI Framework:** Java Swing  
- **Database:** MySQL 8.0  
- **Reporting:** JasperReports  
- **Architecture:** MVC  

### Design Patterns Used
- Singleton (Database Connection)  
- DAO Pattern  
- Strategy Pattern  
- Factory Pattern  

---

## ⚙️ Core Features

### 🚚 Order Management
- Create and manage delivery orders  
- Assign vehicles and drivers  
- Order lifecycle tracking:
  - Pending  
  - Assigned  
  - In-Transit  
  - Delivered  
  - Cancelled  

### 💰 Dynamic Pricing Engine
Uses Strategy Pattern to calculate pricing based on:
- Customer type  
- Distance  
- Priority level  

### 🚛 Fleet & Driver Management
- Vehicle availability tracking  
- Driver assignment management  
- Automatic resource locking & releasing  

### 📊 Reporting System
- Fleet performance reports  
- Profitability analysis  
- Utilization metrics  
- Professional PDF report generation using JasperReports  

### ✅ Validation & Error Handling
- Centralized validation utility  
- Custom business exceptions  
- Capacity and availability checks  

---

## 🗂️ Project Structure

com.transfleet
│

├── config       # Database connection (Singleton)

├── model        # Entity classes

├── dao          # Database operations (CRUD)

├── view         # Swing UI screens

├── strategy     # Pricing strategies

├── util         # Validation helpers

├── exceptions   # Custom business exceptions

├── reports      # Jasper report handlers

└── resources    # Report templates (JRXML)

---

## 🗄️ Database Design

- Normalized to 3NF  
- Foreign key constraints  
- ENUM usage for controlled values  
- Indexed fields for performance  

The `orders` table acts as the central linking entity connecting:
- Customers  
- Vehicles  
- Drivers  
- Routes  
- Payments  
- Expenses  

---

## ▶️ How to Run the Project

1. Start MySQL server  
2. Import `transfleet_db.sql` into MySQL  
3. Open the project in NetBeans  
4. Add required JAR libraries  
5. Run `MainDashboard.java`

---

## 👩‍💻 Developed By

**Meleesha Bahardeen**  
Diploma in Computer System Design  
Enterprise Application Development (EAD) – Coursework
