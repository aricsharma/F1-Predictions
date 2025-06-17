# 🏎️ Monaco Grand Prix 2025 Podium Prediction

This project predicts the **podium finishers** for the 2025 Monaco Grand Prix using machine learning and multi-source data integration. It leverages real-world F1 telemetry, weather forecasts, and performance metrics to simulate race outcomes.

---

## 📊 Features Used

- **FastF1 API**: Retrieves session telemetry data.
- **Weather API (OpenWeatherMap)**: Fetches rain probability and temperature.
- **Qualifying Data**: Predicted or actual Monaco GP 2025 qualifying results.
- **Clean Air Race Pace**: Average driver pace in traffic-free conditions.
- **Team Performance Score**: Normalized based on constructor standings.
- **Track-Specific Trends**: Monaco’s average position change behavior.

---

## 🛠️ Technologies & Libraries

- Python 3.8+
- `fastf1`
- `pandas`, `numpy`
- `matplotlib`
- `scikit-learn`
- `requests`

---

## 🏁 Predicted 2025 Monaco GP Winner 🏁

  Driver     PredictedRaceTime (s)
0   NOR        93.22
1   VER        93.41
2   PIA        93.56

Model Error (MAE): 0.47 seconds

🏆 Predicted in the Top 3 🏆
🥇 P1: NOR
🥈 P2: VER
🥉 P3: PIA

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/monaco-gp-prediction.git
cd monaco-gp-prediction

# Install required libraries
pip install fastf1 pandas numpy matplotlib scikit-learn requests
