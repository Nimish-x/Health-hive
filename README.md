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

  **[Developed for the MumbaiHacks Hackathon 🧠💡]**
</div>

<br />

## 🌆 The Problem: Urban Overload During Emergencies

During a large-scale emergency, the default approach of sending all patients to the nearest hospital creates a **critical bottleneck**:

- ⚠️ The closest facility becomes **overwhelmed**, leading to long wait times.
- 📉 Nearby alternate hospitals remain **underutilized**.
- 🚑 The result: delayed critical care and **avoidable fatalities**.

Urban healthcare networks lack real-time, city-wide coordination — that’s where our **AI Emergency Load Balancer** comes in.

---

## 🤖 Our Solution: An Agentic AI Coordinator

The system functions as an **autonomous emergency coordinator** following a modern **Sense–Think–Act** cycle:

### 🧠 SENSE
Monitors real-time data from hospitals across the city, including:
- **Bed occupancy** (ICU, Wards)
- **Staff availability** (Surgeons, Nurses)
- **Specialty care units** (e.g., trauma, burn, cardiac units)

### 🤔 THINK
Predicts and plans using state-of-the-art AI:
- An **XGBoost model** forecasts future ER wait times dynamically.
- A proprietary **optimization algorithm** computes a `Time-to-Treatment` score — perfectly balancing ambulance travel time with predicted hospital waiting time.

### 🚑 ACT
Executes dynamic routing and load balancing:
- Suggests **optimized ambulance dispatch routes**.
- **Notifies hospitals** in advance to prep specialized teams.
- Proactively allocates resources to prevent system bottlenecks before they even form.

---

## 🛠️ Tech Stack Architecture

**Backend Engine ⚙️**
- **Framework:** Python / Flask
- **Machine Learning & AI:** Scikit-learn, Pandas, NumPy, XGBoost
- **Core Processing Logic:** Python Subprocess & JSON parsers for complex orchestration

**Frontend Dashboard 💻**
- **Framework:** React.js
- **Build Tool:** Vite for lightning-fast HMR and compilation
- **API Client:** Axios
- **UI & Styling:** Custom modular CSS

---

## 📸 System Previews

<details>
<summary><b>Click to expand screenshots</b></summary>
<br>

| Dashboard Analytics | Routing Interface |
|:---:|:---:|
| <img alt="Dashboard Overview" src="https://github.com/user-attachments/assets/cb9899fe-10c5-4712-aee0-edc0562ecad6" width="100%"> | <img alt="Routing interface" src="https://github.com/user-attachments/assets/3e372aac-f53e-4af4-ad15-46554b51d26d" width="100%"> |

| Notification Center | Live Mapping |
|:---:|:---:|
| <img alt="Notification Interface" src="https://github.com/user-attachments/assets/5077ee85-3ea7-4f8c-9e1a-23f67a7449ee" width="100%"> | <img alt="Map Data" src="https://github.com/user-attachments/assets/32ef97ba-0a77-47c0-a108-7ba6cb636c15" width="100%"> |

| Real-Time Resource Feed |
|:---:|
| <img alt="Live Feed" src="https://github.com/user-attachments/assets/1979e310-d947-4c0b-abfc-c8f62b8efe96" width="100%"> |

</details>

---

## 👥 Meet the Team (Data Dabbawalas)

Brought to life at **MumbaiHacks** by **Team Data Dabbawalas**:
- **Nimish Tilwani**
- **Karan Tulsani**
- **Ved Dange**
- **Dhananjay Yadav**


*Special thanks to the hackathon organizers and mentors for their incredible guidance and support throughout the event.*

---

<div align="center">
  <i>⚙️ AI that saves lives — optimizing emergency response, one decision at a time.</i>
</div>
