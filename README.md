# 🌦️ AEC-DT-weather-platform
> AI-powered Smart Grid Energy Management System integrating weather forecasting, autonomous software agents, and intelligent optimization techniques for renewable energy management.

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Flask](https://img.shields.io/badge/Flask-Backend-black)
![REST API](https://img.shields.io/badge/API-REST-success)
![MIT License](https://img.shields.io/badge/License-MIT-green)

---

## 📖 Overview

This project is an AI-powered Smart Grid Energy Management System that combines weather forecasting, autonomous software agents, and intelligent optimization to improve renewable energy utilization.

The platform integrates real-time weather data from the NASA POWER API with multiple intelligent agents responsible for photovoltaic energy generation, battery storage, electric vehicle scheduling, cybersecurity monitoring, voltage regulation, and energy optimization.

Built using Python and Flask, the system demonstrates how AI-driven multi-agent architectures can efficiently manage distributed energy resources within a modern smart grid.

---

## ✨ Features

- 🌤️ Weather forecasting using NASA POWER API
- ☀️ PV (Solar) Energy Management
- 🔋 Battery Management Agent
- 🚗 Electric Vehicle (EV) Agent
- 📈 Forecast Agent
- ⚡ Voltage Monitoring
- 🔐 Cyber Security Agent
- 🤖 BDI-inspired Multi-Agent Architecture
- 📊 MPC-based Energy Optimization
- 🌐 REST API Backend
- 💻 Interactive Dashboard

---

## 🏗️ System Architecture

```
                NASA POWER API
                       │
                       ▼
               Forecast Agent
                       │
      ┌────────────────┼────────────────┐
      ▼                ▼                ▼
  PV Agent      Battery Agent      EV Agent
      │                │                │
      └────────────┬───┴───────────────┘
                   ▼
            MPC Optimizer
                   │
                   ▼
            Voltage Agent
                   │
                   ▼
             Cyber Agent
                   │
                   ▼
          Dashboard + REST APIs
```

---

## 🛠️ Tech Stack

### Backend

- Python
- Flask
- REST APIs

### Frontend

- HTML
- CSS
- JavaScript

### Data Processing

- NumPy
- Pandas

### External API

- NASA POWER API

### Concepts

- Multi-Agent Systems
- BDI Architecture
- Model Predictive Control (MPC)
- Smart Grid
- Renewable Energy Management

---

## 📂 Project Structure

```text
weather-forecasting-smart-grid
│
├── agents/
│   ├── pv_agent.py
│   ├── battery_agent.py
│   ├── ev_agent.py
│   ├── forecast_agent.py
│   ├── voltage_agent.py
│   ├── cyber_agent.py
│   ├── mpc_optimizer.py
│   └── dqn_ev_agent.py
│
├── backend/
├── frontend/
├── data/
│
├── server.py
├── requirements.txt
└── README.md
```

---

## 🚀 Getting Started

Clone the repository

```bash
git clone https://github.com/HunarKaur2007/weather-forecasting-smart-grid.git
```

Move into the project directory

```bash
cd weather-forecasting-smart-grid
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
python server.py
```

---

## 🔌 REST API Endpoints

| Endpoint | Description |
|----------|-------------|
| `/api/status` | System Status |
| `/api/weather` | Weather Forecast |
| `/api/location` | Location Lookup |
| `/api/nasa` | NASA Weather Data |
| `/api/agents` | Agent Outputs |
| `/api/messages` | Agent Communication |

---

## 🚀 Future Enhancements

- LSTM-based Weather Forecasting
- Reinforcement Learning Optimization
- Federated Learning
- Physics-Informed Neural Networks (PINNs)
- Docker Deployment
- Cloud Hosting
- IoT Sensor Integration

---

## 👩‍💻 Author

**Hunar Kaur**

Computer Engineering Undergraduate

Thapar Institute of Engineering & Technology

GitHub: https://github.com/HunarKaur2007

LinkedIn: https://linkedin.com/in/hunar-kaur-6a62b830b

---

## 📄 License

This project is licensed under the MIT License.

---

⭐ If you found this project useful, consider giving it a star.
