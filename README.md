# 🌆 Urban Water Supply & Demand Management System

### System Dynamics Model using **Vensim PLE**

---

## 📌 Project Overview

This project is a **System Dynamics simulation model** developed using **Vensim** to analyze and manage **urban water supply and demand** in a growing city.

It models the dynamic interactions between:

* Population growth
* Water demand
* Rainfall and river inflow
* Reservoir storage
* Groundwater usage
* Water scarcity
* Conservation policies

The model helps in understanding how long-term sustainability can be achieved through **policy interventions, conservation strategies, and smart resource management**.

---

## 🎯 Objectives

* To model urban water supply and demand dynamics
* To analyze effects of population growth on water resources
* To study impact of rainfall variability
* To simulate water scarcity scenarios
* To evaluate conservation strategies
* To support sustainable urban planning

---

## 🧠 System Dynamics Approach

The project follows **System Dynamics methodology**, using:

* **Stocks (Levels)** → Accumulations (e.g., water, population)
* **Flows (Rates)** → Movement/change (e.g., inflow, extraction)
* **Auxiliaries** → Calculations and control variables
* **Feedback loops** → Cause–effect cycles

---

## 🧩 Model Components

### 🔵 Stocks (Levels)

* Water_Reservoir
* Groundwater_Level
* Urban_Population

### 🟢 Flows (Rates)

* Rainfall_Inflow
* River_Inflow
* Water_Extraction
* Evaporation_Loss
* Recharge_Rate
* Groundwater_Extraction
* Population_Growth
* Population_Death

### 🟡 Auxiliaries

* Per_Capita_Water_Use
* Water_Demand
* Rainfall_Rate
* Conservation_Factor
* Leakage_Rate
* Scarcity_Index

---

## 🔁 Feedback Loops

### Reinforcing Loop (R1 – Demand Growth)

Population ↑ → Water Demand ↑ → Extraction ↑ → Reservoir ↓ → Scarcity ↑

### Balancing Loop (B1 – Conservation Control)

Scarcity ↑ → Conservation ↑ → Water Demand ↓ → Extraction ↓ → Reservoir ↑

---

## 🏗 Model Structure

The model is built using a **stock-flow structure** connecting population, supply, demand, and conservation subsystems.

---

## ⚙️ Simulation Settings

* Time Unit: Day
* Initial Time: 0
* Final Time: 365
* Time Step: 1

---

## 📊 Scenarios Simulated

### 1️⃣ Normal Conditions

* Normal rainfall
* No conservation policies

### 2️⃣ Climate Stress Scenario

* Reduced rainfall
* Increased evaporation

### 3️⃣ Conservation Policy Scenario

* Reduced leakage
* Reduced per-capita water use

### 4️⃣ Population Growth Scenario

* Increased population growth rate

---

## 📈 Outputs

The model generates dynamic graphs for:

* Water reservoir level
* Water demand
* Urban population
* Groundwater level
* Scarcity index
* Conservation impact

---

## 🖥 Software Used

* **Vensim PLE** – System Dynamics Modeling Tool

---

## 📂 Repository Structure

```
Urban-Water-Vensim-Project/
│
├── model/
│   └── urban_water_model.mdl
│
├── diagrams/
│   ├── stock_flow_diagram.png
│
├── graphs/
│   ├── Graphs.png
│   └── scenario_Graphs.png
│
│
└── README.md
```

---

## 🎓 Academic Relevance

This project is suitable for:

* System Dynamics coursework
* Smart City modeling
* Urban planning studies
* Sustainability projects
* Environmental systems modeling

---

## 🚀 Future Enhancements

* Seasonal rainfall modeling
* Smart water meters integration
* AI-based demand prediction
* IoT leakage detection
* Dynamic pricing models
* Policy optimization engine

---

## 🧪 How to Run the Model

1. Install **Vensim PLE**
2. Open `urban_water_model.mdl`
3. Click **Simulate ▶️**
4. View graphs using **Graph Tool 📊**
5. Modify parameters for scenario analysis

---


## ⭐ Acknowledgment

Developed as part of an academic project using **System Dynamics modeling principles** and **Vensim simulation framework**.

---

✨ *If you like this project, give it a star ⭐ on GitHub and feel free to use it for learning and academic purposes.*
