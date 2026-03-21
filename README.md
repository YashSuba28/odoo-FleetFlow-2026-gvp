# 🚛 FleetFlow – Modular Fleet & Logistics Management System

FleetFlow is a modern web-based application designed to simplify and optimize fleet and logistics operations.  
It replaces traditional manual logbooks with a centralized digital system that manages vehicles, drivers, trips, maintenance, and financial tracking efficiently.

---

## 📌 Problem Statement

In many logistics operations, fleet management is still handled manually using logbooks or spreadsheets. This creates several problems:

- Lack of real-time vehicle tracking  
- Inefficient trip assignment and management  
- No proper monitoring of driver performance and safety  
- Poor visibility of expenses and operational costs  
- High chances of human error  

FleetFlow addresses these challenges by providing a centralized and rule-based system that improves efficiency, accuracy, and decision-making.

---

## 🎯 Objective

The objective of FleetFlow is to build a complete fleet management solution that:

- Manages the lifecycle of vehicles  
- Enables efficient trip dispatching  
- Tracks driver performance and compliance  
- Records expenses and fuel usage  
- Provides analytics for better operational decisions  

---

## 👥 Target Users

FleetFlow is designed for different roles within a logistics system:

- Fleet Managers → Manage vehicles, maintenance, and operations  
- Dispatchers → Assign trips and drivers  
- Safety Officers → Monitor driver safety and license validity  
- Financial Analysts → Track expenses and profitability  

---

## 🧩 Core Features

### 1. Authentication System
- Secure login and registration  
- Role-based access control (Manager / Dispatcher)

---

### 2. Dashboard (Command Center)
- Overview of fleet status  
- Active vehicles currently on trip  
- Maintenance alerts  
- Pending cargo tracking  
- Search and filter functionality  

---

### 3. Vehicle Registry
- Add and manage vehicles  
- Store details such as:
  - License plate  
  - Model and type  
  - Capacity  
  - Odometer reading  
- Track vehicle status (Available, On Trip, In Shop)

---

### 4. Trip Dispatcher
- Create and manage trips  
- Assign drivers and vehicles  
- Validate cargo weight against vehicle capacity  
- Track trip lifecycle (Dispatched → Completed)

---

### 5. Maintenance & Service Logs
- Record maintenance and service activities  
- Automatically mark vehicles as "In Shop"  
- Prevent vehicles under maintenance from being assigned to trips  

---

### 6. Expense & Fuel Tracking
- Record fuel and miscellaneous expenses  
- Track operational cost per trip  
- Maintain financial records for each vehicle  

---

### 7. Driver Performance & Safety
- Monitor safety scores  
- Track trip completion rates  
- Record complaints  
- Manage driver compliance (license tracking)  

---

### 8. Analytics Dashboard
- Visual representation of fuel efficiency  
- Cost analysis of vehicles  
- Financial summary reports  
- Charts using Chart.js  

---

## 🔄 System Workflow

1. A vehicle is added to the system → status becomes Available  
2. A driver is registered and validated  
3. A trip is created with assigned vehicle and driver  
4. System validates capacity before dispatch  
5. Trip is completed → status updates automatically  
6. Maintenance logs update vehicle status to "In Shop"  
7. Analytics are generated based on trip and expense data  

---

## 🛠️ Tech Stack

- Frontend: HTML, CSS, JavaScript  
- Storage: LocalStorage (for data simulation)  
- Charts: Chart.js  
- UI Design: Card-based modern interface  

---

## 📁 Project Structure

FleetFlow/
│── index.html  
│── login.html  
│── register.html  
│── dashboard.html  
│── vehicle-registry.html  
│── trip-dispatcher.html  
│── maintenance.html  
│── expense.html  
│── driver-performance.html  
│── analytics.html  
│  
├── css/  
├── js/  

---

## 🚀 How to Run the Project

1. Download or clone the repository  
2. Open the project folder  
3. Run `index.html` in a browser  
4. Register and login  
5. Start using the system  

---

## 🎥 Demo Video

Add your project demo video link here:

https://your-video-link-here

---

## 💡 Key Highlights

- Modular system design  
- Clean and structured UI  
- Real-time simulation using LocalStorage  
- Covers full logistics workflow  
- Easy to understand and use  

---

## 🔮 Future Improvements

- Backend integration (Node.js / Firebase)  
- Database integration (MongoDB / MySQL)  
- Real-time tracking (GPS)  
- Notification system  
- Fully responsive design  

---

## 🏆 Conclusion

FleetFlow is a complete fleet and logistics management solution that demonstrates how digital systems can improve operational efficiency, reduce manual work, and provide valuable insights for decision-making.

---

## 👨‍💻 Author

Yash Suba and Aastha Thakkar
