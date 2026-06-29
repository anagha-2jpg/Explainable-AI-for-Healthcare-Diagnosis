# Reports Documentation

## Sequence Diagram
```text
User
 │
 ▼
Login
 │
 ▼
Dashboard
 │
 ▼
Patient Form
 │
 ▼
Prediction API
 │
 ▼
ML Model
 │
 ├─SHAP
 └─LIME
 │
 ▼
Result
 │
 ▼
PDF Report
```

## SHAP Notes
- Explains feature contribution.
- Positive and negative impact.
- Global and local explanations.

## LIME Notes
- Local surrogate model.
- Model agnostic.
- Explains individual predictions.

## API Summary

|Endpoint|Purpose|
|---|---|
|POST /login|Authentication|
|POST /patient|Save patient|
|POST /predict/*|Disease prediction|
|GET /report|Fetch report|
|POST /report/pdf|Generate PDF|

## Future Scope
- Deep learning
- Multi-language
- Cloud deployment
- Doctor collaboration
- Real-time EHR integration
