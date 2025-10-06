# Fleet-Track-Cloud-Based-Fleet-Management-Platform
## 📘 Overview  
**Fleet Track** is a cloud-based fleet management system that enables real-time tracking, monitoring, and performance analytics of vehicles in a distributed environment.  
It integrates data from the **CARLA Simulator**, processes it through a **Flask backend**, and visualizes live results through a user-friendly **GUI dashboard**.  
This project highlights advanced concepts in **Programming**, **Cloud integration**, and **Data visualization** to simulate and manage 1000+ vehicles efficiently.

## ⚙️ Key Features  
**Real-Time Vehicle Telemetry** – Capture live vehicle metrics like speed, route, and fuel consumption via CARLA Simulator.   
**Cloud-Hosted Backend** – Flask API backend handles routing, concurrency, and live data streaming.   
**Dual Database Integration** – Combines **MySQL** (for structured trip data) and **MongoDB** (for telemetry and logs).   
**Dynamic GUI Dashboard** – Visualize live fleet analytics, performance, and health monitoring.   
**User Management System** – Secure login and access control.   

## Setup Instructions   

### 1. Clone the Repository   
```bash
git clone https://github.com/Divija3009/FleetTrack.git
cd FleetTrack
```
### 2. Create and Activate a Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate     # Windows
source venv/bin/activate  # macOS/Linux
```
### 3. Install Dependencies
```
pip install -r requirements.txt
```
### 4. Configure Databases 
Set up a MySQL instance and update credentials in mysqldata.py.
Optionally configure MongoDB Atlas for telemetry storage.
### 5. Run the Application
```
python main.py
```
### 6. Start CARLA Simulator 
```
python maincarla.py
```

