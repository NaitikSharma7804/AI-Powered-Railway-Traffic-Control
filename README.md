# 🚆 Maximizing Section Throughput Using AI-Powered Precise Train Traffic Control

An AI-powered railway traffic control and optimization system developed for the **Smart India Hackathon (SIH)**.

The project uses discrete-event simulation to explore how intelligent traffic control can improve railway section throughput, train punctuality, and delay management compared with conventional rule-based approaches.

Built using **Python, SimPy, Streamlit, and scikit-learn**, the system provides an interactive environment for simulating railway operations and comparing different traffic control strategies.

## 🎯 Problem Statement

Railway traffic management requires efficient coordination of trains operating across limited railway sections and platforms.

Delays, congestion, platform conflicts, and unexpected disruptions can affect railway throughput and punctuality.

This project explores an AI-assisted railway traffic control approach to:

- Improve railway section throughput.
- Reduce average train delays.
- Improve train punctuality.
- Support intelligent platform allocation.
- Evaluate operational performance under different scenarios.

## 🚀 Key Features

### 1. Dual Simulation: AI vs. Non-AI
- Runs two parallel railway traffic simulations.
- Compares AI-assisted control with conventional rule-based control.
- Evaluates the impact of different allocation strategies.

### 2. AI-Powered Traffic Control
- Uses mock scikit-learn models for AI-based demonstrations.
- Predicts potential train delays.
- Supports intelligent platform allocation.
- Demonstrates predictive decision-making in railway operations.

### 3. Interactive Streamlit Dashboard
- Configure simulation parameters.
- Run railway traffic simulations.
- Visualize operational performance.
- Compare AI and non-AI simulation results.

### 4. Key Performance Indicators (KPIs)

The system evaluates:

| KPI | Purpose |
|---|---|
| Train Punctuality | Evaluate on-time train operations |
| Average Delay | Measure train delays |
| Section Throughput | Measure railway section efficiency |
| Platform Utilization | Analyze platform usage |

### 5. Scenario Modeling
- Disaster Mode for evaluating disruption scenarios.
- What-If analysis for testing alternative operating conditions.
- Simulation-based resilience evaluation.

### 6. Modular Architecture
The project separates AI components, simulation logic, dashboard functionality, and data management into dedicated modules.

## 🏗️ System Architecture

```text
              USER
                |
                v
        STREAMLIT DASHBOARD
                |
                v
       SIMULATION PARAMETERS
                |
                v
       DISCRETE-EVENT ENGINE
              (SimPy)
                |
          +-----+-----+
          |           |
          v           v
      AI-BASED    RULE-BASED
       CONTROL      CONTROL
          |           |
          v           v
       PLATFORM AND TRAFFIC
          ALLOCATION LOGIC
          |           |
          +-----+-----+
                |
                v
        PERFORMANCE ANALYSIS
                |
                v
           KPI COMPARISON
                |
                v
        RESULTS VISUALIZATION
```

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Core development |
| SimPy | Discrete-event simulation |
| Streamlit | Interactive dashboard |
| scikit-learn | Machine learning model demonstrations |

## 📂 Project Structure

```text
SIH-Project/
│
├── ai/
│   └── AI-related modules
│
├── dashboard/
│   └── Dashboard components
│
├── data/
│   └── Simulation data
│
├── simulation/
│   └── Railway simulation modules
│
├── app.py
├── requirements.txt
└── README.md
```

## ⚙️ Installation and Setup

### Prerequisites
- Python 3.9 or later
- pip package manager

### 1. Clone the Repository

```bash
git clone https://github.com/NaitikSharma7804/SIH-Project.git
```

### 2. Navigate to the Project Directory

```bash
cd SIH-Project
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Environment

**Windows PowerShell:**

```powershell
.\venv\Scripts\Activate.ps1
```

**Linux/macOS:**

```bash
source venv/bin/activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the Application

```bash
streamlit run app.py
```

Open the local URL displayed in your terminal to access the dashboard.

## 📊 Expected Outcomes

The simulation is designed to help evaluate:

- Differences between AI-assisted and rule-based railway traffic control.
- Changes in train throughput.
- Improvements or deterioration in punctuality.
- Average train delay.
- Railway platform utilization.
- System behavior during disruption scenarios.

Actual performance improvements should be established using simulation results rather than assumed in advance.

## 🔮 Future Enhancements

- Integrate real-time railway traffic data.
- Develop more advanced machine learning models for delay prediction.
- Incorporate dynamic platform allocation.
- Add live railway network visualization.
- Explore traffic-aware route optimization.
- Integrate historical train movement datasets.
- Improve disruption prediction and recovery strategies.

## 🎓 Project Information

**Project:** Maximizing Section Throughput Using AI-Powered Precise Train Traffic Control

**Event:** Smart India Hackathon (SIH)

**Domain:** Artificial Intelligence, Machine Learning, Railway Optimization, Simulation

## 👨‍💻 Author

**Naitik Sharma**

B.Tech Computer Science and Engineering  
MIT World Peace University, Pune

GitHub: [@NaitikSharma7804](https://github.com/NaitikSharma7804)

## 📄 License

No license has been specified yet. Add an appropriate open-source license if you intend to permit reuse and modification.

---

**Building smarter railway operations through AI, simulation, and intelligent decision-making.**
