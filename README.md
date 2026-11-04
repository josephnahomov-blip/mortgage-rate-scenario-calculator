# Canadian Mortgage Rate Scenario Simulator

A modern, accurate desktop/web app for comparing **Fixed** vs **Variable** mortgage rates under a customizable rate-hike path.

Built for Canadian mortgages using the official **semi-annual compounding** convention.

---

## Quick Start

```bash
# 1. Install dependencies
pip install -r requirements.txt

# 2. Launch the app
streamlit run mortgage_scenario_simulator.py
```

The app opens automatically in your browser at `http://localhost:8501`.

---

## Features

- **Pinpoint accuracy** – Canadian semi-annual compounding:  
  `monthly rate = (1 + annual/2)^(1/6) − 1`
- Full monthly amortization schedule for the comparison term
- Three parallel tracks: Fixed • Variable (no hikes) • Variable (with hikes)
- Two payment strategies:
  - Keep initial variable payment (supports negative amortization)
  - Recalculate payment after each hike
- Green / Red visual outcome for interest savings or loss
- Live rate-hike timeline
- Downloadable CSV of the full monthly schedule
- Clean, modern dark UI

---

## Notes

This is an illustrative model. Always confirm payment adjustment rules and trigger rates with the actual lender.
