# NeuraDiag Project Architecture

## Table of Contents
1. Overview
2. Architecture
3. Technology Stack
4. Workflow
5. Pages
6. Button Actions

## Overview
NeuraDiag is an Explainable AI healthcare diagnosis platform supporting Diabetes, Heart, Kidney and Liver prediction using ML with SHAP and LIME.

## High Level Architecture
```text
User
 ↓
Landing
 ↓
Login/Register
 ↓
Dashboard
 ↓
Patient Info
 ↓
Prediction Engine
 ↓
ML Model
 ├─ SHAP
 ├─ LIME
 ↓
Transparency
 ↓
Report Generator
```

## Tech Stack
Frontend: HTML/CSS/JS
Backend: Flask (planned)
Database: SQLite
ML: Scikit-learn
XAI: SHAP, LIME
PDF: ReportLab

## Page Details
### Landing
Shows project, objectives and CTA.
Buttons:
- Start Diagnosis → Login/App
- Explore Features → Scroll.

### Login/Register
Authenticates user then redirects Dashboard.

### Dashboard
Displays statistics, charts and prediction history.

### Patient Info
Collects demographics and medical history.
Save button validates then stores patient.

### Prediction
Select disease card → form opens → Run AI Prediction sends data to backend → prediction, confidence, risk and health score returned.

### XAI
Displays SHAP waterfall and LIME explanation.

### Transparency
Shows Trust, Reliability, Stability, Consistency, Confidence and AI recommendations.

### Reports
Preview and export PDF.

### Admin
User management and model monitoring.

### Profile
Edit user profile.
