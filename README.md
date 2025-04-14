# 🏎️ Saudi GP F1 Tire Strategy Simulator

A full race strategy simulator for the 2025 Saudi Arabian Grand Prix — powered by data from the 2022, 2023, and 2024 races.

Built using Python, openF1, FastF1, and scikit-learn to model:

- 🔁 Tire degradation curves (soft, medium, hard)
- ⛽ Fuel load compensation
- 🌡️ Temperature sensitivity
- 📉 Track evolution modeling
- 🛑 Pit window optimization
- 🧠 Strategy simulation with pit stops and compound switching
- 📊 Summary dashboard (Matplotlib, Power BI-ready)

## 📂 Project Structure

- `notebooks/` – exploratory modeling notebook
- `scripts/` – modularized simulation code
- `data/` – clean, merged data from openF1 API and FastF1
- `outputs/` – final strategy visualizations (dark AWS style)
- `README.md` – you're here

## 📸 Dashboard Preview

![Strategy Dashboard](outputs/strategy_dashboard.png)

## 🔧 Dependencies

