<div align="center">
  <img src="https://github.com/user-attachments/assets/879b6ea7-60e4-4b5b-9246-999836bcf304" alt="HealthHIVE Logo" width="150" />

  # 🚨 HealthHIVE 2.0
  **AI Emergency Load Balancer for Urban Hospital Networks**
  
  <p align="center">
    <a href="https://mumbai-hacks-five.vercel.app"><img src="https://img.shields.io/badge/Live%20Demo-Vercel-black?style=for-the-badge&logo=vercel" alt="Live Demo"></a>
    <img src="https://img.shields.io/badge/Python-Flask-blue?style=for-the-badge&logo=python" alt="Python Flask">
    <img src="https://img.shields.io/badge/React-Vite-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React">
    <img src="https://img.shields.io/badge/ML-XGBoost-orange?style=for-the-badge&logo=scikitlearn" alt="XGBoost">
  </p>
  
  <p align="center">
    <i>An <b>intelligent agent</b> designed to optimize patient routing during <b>mass casualty incidents</b> in dense urban environments (e.g., Mumbai). Ensuring patients reach the fastest available care, not just the closest hospital.</i>
  </p>

  **[🏆 Developed for the MumbaiHacks Hackathon]**
</div>

<br />

## 🌆 The Problem: Urban Overload During Emergencies

During a large-scale emergency, the default approach of sending all patients to the nearest hospital creates a **critical bottleneck**:

- ⚠️ **The Immediate Crisis:** The closest facility becomes **overwhelmed**, leading to severe congestion in triage and long wait times for life-saving care.
- 📉 **The Inefficiency:** Nearby alternate hospitals with available beds and specialized staff often remain **underutilized** simply because they were slightly further away geographically.
- 🚑 **The Result:** Delayed critical care and **avoidable fatalities**.

Urban healthcare networks lack real-time, city-wide coordination. Traditional dispatch systems are reactive. That’s where our **AI Emergency Load Balancer** steps in to make the network proactive.

---

## 🤖 Our Solution: An Agentic AI Coordinator

The system functions as an **autonomous emergency coordinator** orchestrating resources city-wide. It operates on a continuous **Sense–Think–Act** loop:

### 🧠 SENSE (Real-time Telemetry)
HealthHIVE constantly ingests and monitors live data streams from hospitals across the city network:
- **Bed Occupancy:** General wards, ICUs, and specialized recovery rooms.
- **Staff Availability:** Tracking surgeons, nurses, and specialized trauma teams on shift.
- **Specialty Units:** Live status of trauma centers, burn units, and cardiac care facilities.

### 🤔 THINK (Predictive ML Engine)
The core intelligence predicts and plans using state-of-the-art machine learning:
- **Forecasting:** An **XGBoost model** analyzes historical and current data to forecast future ER wait times.
- **Smart Routing:** A proprietary **optimization algorithm** computes a dynamic `Time-to-Treatment` score. It perfectly balances the *ambulance travel time* against the *predicted hospital waiting time* to find the true fastest path to care.

### 🚑 ACT (Execution & Dispatch)
Executes dynamic routing and load balancing:
- **Optimized Dispatch:** Suggests alternate, faster routes bypassing congested local hubs.
- **Pre-Arrival Alerts:** Notifies receiving hospitals in advance so specialized teams can prep for incoming cases.
- **Proactive Balancing:** Dynamically redirects flow to distribute the load evenly across the healthcare grid, preventing operational bottlenecks before they form.

---

## 🛠️ System Architecture & Tech Stack

HealthHIVE is built on a decoupled, highly responsive architecture designed for high availability during critical events.

### **Backend Engine ⚙️**
The backend serves as the brain, processing the heavy ML models and managing the complex state of the city's hospital network.
- **Framework:** Python / Flask (Chosen for speed of iteration and ML ecosystem integration)
- **Machine Learning & AI:** Scikit-learn, Pandas, NumPy, XGBoost
- **Core Processing Logic:** Python Subprocess & JSON parsers for orchestrating prediction tasks asynchronously.

### **Frontend Dashboard 💻**
The frontend is built for incident commanders and dispatchers, requiring real-time updates without page reloads.
- **Framework:** React.js
- **Build Tool:** Vite (Lightning-fast HMR and optimized production compilation)
- **State & Data Management:** Axios for robust API polling.
- **UI & Styling:** Custom modular CSS designed for high contrast and readability in high-stress control rooms.

---

## 📸 System Previews & Features

Explore the various interfaces of the HealthHIVE command center.

<details>
<summary><b>Click here to expand the gallery of screenshots</b></summary>
<br>

**1. Main Dashboard & Analytics**  
*Overview of city-wide strain and incoming incidents.*
<img alt="Dashboard Overview" src="https://github.com/user-attachments/assets/cb9899fe-10c5-4712-aee0-edc0562ecad6" width="100%">

**2. Intelligent Routing Interface**  
*The AI suggesting the fastest `Time-to-Treatment` path.*
<img alt="Routing interface" src="https://github.com/user-attachments/assets/3e372aac-f53e-4af4-ad15-46554b51d26d" width="100%">

**3. Hospital Notification Center**  
*Alerts received by the hospital to prepare trauma teams.*
<img alt="Notification Interface" src="https://github.com/user-attachments/assets/5077ee85-3ea7-4f8c-9e1a-23f67a7449ee" width="100%">

**4. Live Geographical Mapping**  
*Visualizing the spread of incidents across the grid.*
<img alt="Map Data" src="https://github.com/user-attachments/assets/32ef97ba-0a77-47c0-a108-7ba6cb636c15" width="100%">

**5. Real-Time Resource Feed**  
*Live data stream of resource utilization.*
<img alt="Live Feed" src="https://github.com/user-attachments/assets/1979e310-d947-4c0b-abfc-c8f62b8efe96" width="100%">

</details>

---

## 👥 Meet the Team (Data Dabbawalas)

Brought to life at **MumbaiHacks** by **Team Data Dabbawalas**. We are passionate about using data and AI to solve critical physical-world problems.

- **Nimish Tilwani**
- **Karan Tulsani**
- **Ved Dange**
- **Dhananjay Yadav**

*Special thanks to the hackathon organizers and mentors for their incredible guidance and support throughout the 24-hour build sprint!*

---

<div align="center">
  <i>⚙️ <b>HealthHIVE:</b> AI that saves lives — optimizing emergency response, one decision at a time.</i>
</div>
