# ⚡ Smart Home Energy Monitoring System

An AI-Powered Smart Home Energy Monitoring System built using Python, Streamlit, and IoT Simulation concepts.

The system simulates real-world household energy consumption, monitors appliance-level power usage, estimates electricity bills, tracks carbon footprint, generates smart recommendations, and visualizes energy analytics through an interactive dashboard.

---

# 📌 Project Overview

Electricity consumption is increasing rapidly in modern homes due to the growing number of appliances and smart devices.

Many homeowners are unaware of:

- Which appliances consume the most electricity
- Daily energy consumption trends
- Monthly electricity costs
- Energy wastage
- Environmental impact

This project helps users monitor, analyze, and optimize their energy consumption through a smart dashboard.

---

# 🎯 Objectives

- Monitor household energy consumption
- Simulate appliance-level power usage
- Calculate electricity cost
- Estimate monthly and yearly bills
- Detect high energy consumption
- Generate smart energy-saving recommendations
- Track carbon emissions
- Visualize historical energy data
- Export reports for analysis

---

# 🏗️ System Architecture

```text
Appliance Selection
        │
        ▼
Energy Simulator
        │
        ▼
Power Calculation Engine
        │
        ▼
Energy Analytics Engine
        │
        ▼
CSV Data Logger
        │
        ▼
Alert Engine
        │
        ▼
Streamlit Dashboard
        │
        ▼
User Insights & Reports
```

---

# 🚀 Features

## ⚡ Real-Time Energy Monitoring

Monitor:

- Voltage
- Current
- Power Consumption
- Energy Usage

---

## 💰 Electricity Bill Estimation

Calculate:

- Current Cost
- Daily Cost
- Monthly Bill Prediction
- Yearly Bill Prediction

---

## 🌱 Carbon Footprint Tracking

Estimate:

- CO₂ Emissions
- Environmental Impact
- Tree Offset Requirement

---

## 📈 Energy Analytics

Interactive visualizations:

- Power Trend
- Energy Usage Trend
- Cost Trend

---

## 🏠 Appliance Analytics

Monitor energy consumption of:

- Fan
- LED Bulb
- TV
- Laptop
- Refrigerator
- Microwave
- Air Conditioner
- Water Heater
- Washing Machine
- Router
- Desktop PC
- Water Pump

---

## 🚨 Smart Alert System

Detect:

- High Energy Usage
- Overload Risk
- Inefficient Consumption

Provides recommendations to reduce energy waste.

---

## 🏆 Energy Efficiency Rating

Generates:

- Efficiency Score
- Efficiency Grade

Example:

```text
A+
A
B
C
D
```

---

## 📜 Consumption History

Stores historical records:

- Timestamp
- Voltage
- Current
- Power
- Energy
- Cost
- Carbon Emissions

---

## 📥 CSV Export

Download historical energy consumption records for:

- Reporting
- Analysis
- Documentation

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Core Development |
| Streamlit | Dashboard Development |
| Pandas | Data Processing |
| Plotly | Data Visualization |
| CSV Storage | Historical Logging |
| Git | Version Control |
| GitHub | Project Hosting |

---

# 📂 Project Structure

```text
Smart-Home-Energy-Monitoring-System/

│
├── .gitignore
├── README.md
├── requirements.txt
├── app.py
│
├── src/
│   ├── simulator.py
│   ├── energy_engine.py
│   ├── alerts.py
│   ├── logger.py
│   └── config.py
│
├── data/
│   ├── energy_log.csv
│   └── appliance_data.csv
│
├── reports/

│
├── assets/

│
├── sample_data/
│ 
│
└── docs/
   
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/arshkaur2405/Smart-Home-Energy-Monitoring-System.git
```

```bash
cd Smart-Home-Energy-Monitoring-System
```

---

# 🐍 Create Virtual Environment

Windows:

```bash
python -m venv venv
```

Activate:

```bash
venv\Scripts\activate
```

---

# Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run Project

```bash
streamlit run app.py
```

---

# 📊 Dashboard Modules

### Live Monitoring

Displays:

- Voltage
- Current
- Power
- Cost

---

### Smart Home Overview

Displays:

- Connected Devices
- Running Devices
- System Health
- Potential Savings

---

### Energy Analytics

Displays:

- Power Trend
- Cost Trend
- Energy Usage Trend

---

### Environmental Analytics

Displays:

- Carbon Emissions
- Tree Offset Requirement

---

### Recommendations

Provides:

- Energy Saving Tips
- High Usage Warnings
- Efficiency Suggestions

---

# 📈 Sample Output

```text
Voltage: 228.5 V

Current: 4.3 A

Power: 980 W

Energy: 0.98 kWh

Cost: ₹7.84

Efficiency Grade: A

Carbon Emission: 0.80 kg
```

---

# 📸 Screenshots

Add screenshots in:

```text
assets/screenshots/
```

Recommended screenshots:

- Dashboard Home
- Appliance Analytics
- Power Trend Graph
- Cost Trend Graph
- Carbon Footprint Section
- Bill Prediction Section
- Consumption History
- CSV Export

---

# 🌍 Real-World Applications

Used in:

### Smart Homes

Monitor and reduce electricity consumption.

### Smart Buildings

Track energy efficiency across floors and departments.

### Commercial Offices

Optimize power utilization.

### Energy Management Companies

Analyze customer energy behavior.

### Sustainability Programs

Track carbon footprint and environmental impact.

---

# 🔮 Future Enhancements

- ESP32 Integration
- ACS712 Current Sensor Integration
- MQTT Connectivity
- Blynk Dashboard
- ThingSpeak Cloud Integration
- Mobile Notifications
- AI-Based Energy Forecasting
- Appliance Failure Detection
- Smart Load Scheduling
- Renewable Energy Monitoring

---

# 🎓 Learning Outcomes

This project demonstrates:

- IoT System Design
- Energy Monitoring Concepts
- Data Analytics
- Dashboard Development
- Streamlit Development
- Software Architecture
- Git & GitHub Workflow

---

# 👨‍💻 Author

Arshdeep Kaur

B.Tech Student

Smart Home Energy Monitoring System Project

---

# ⭐ Support

If you found this project useful:

⭐ Star the repository

🍴 Fork the repository

📢 Share with others
