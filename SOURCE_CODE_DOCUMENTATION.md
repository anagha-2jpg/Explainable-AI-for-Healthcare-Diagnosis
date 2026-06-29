# Source Code Documentation

## Suggested src Structure
```text
src/
 assets/
 components/
 pages/
 services/
 api/
 utils/
 styles/
 App.jsx
```

## Components
- Navbar
- Sidebar
- Hero
- Dashboard Cards
- Prediction Form
- SHAP Chart
- LIME Report
- Trust Gauge
- Report Viewer

## Backend
```text
backend/
 app.py
 routes/
 models/
 services/
 database.py
```

### Main APIs
- POST /login
- POST /register
- POST /patient
- POST /predict/diabetes
- POST /predict/heart
- POST /predict/kidney
- POST /predict/liver
- GET /report

## Prediction Flow
UI → Flask API → ML Model → SHAP/LIME → JSON Response → Dashboard.

## Database Tables
Users, Patients, Predictions, Reports, Logs.
