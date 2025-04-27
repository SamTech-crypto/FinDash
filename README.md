# FinDash – Real-Time SME Financial Dashboard (Mock-Driven)

**FinDash** is a lightweight, modular financial analytics backend for SMEs, enabling real-time monitoring of KPIs like revenue, expenses, burn rate, runway, and cash balance across multiple global subsidiaries. This version uses **mock data**, supporting early-stage prototyping, demos, and dashboard development — with Tableau or any BI tool.

---

## Features

- 🌍 Multi-subsidiary financial simulation (Kenya, Nigeria, US, Germany, etc.)
- 💵 Handles multiple currencies (KES, NGN, USD, EUR)
- 📉 Real-time financial metrics: revenue, expenses, net burn, runway
- ⚠️ Basic anomaly flagging for sudden financial spikes
- 📬 Simulated webhook for real-time updates
- 🧪 Mock data for P&L, balance sheet, and transactions
- 🗃️ MySQL backend (configurable)
- 📊 Compatible with Tableau dashboards

---

## 🔧 Stack

- **Backend**: [FastAPI](https://fastapi.tiangolo.com/)
- **Database**: MySQL
- **Data Modeling**: Pydantic
- **Mock Data**: Faker
- **Deployment Ready**: Uvicorn
- **BI Layer**: Tableau (for visuals and drilldowns)

---

## 📦 Folder Structure

```bash
.
├── main.py              # FastAPI app
├── requirements.txt     # Python dependencies
├── README.md            # You are here!
├── .env                 # DB credentials (optional)
