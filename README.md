1. Architecture
React → calls Flask API
Flask → handles business logic
SQLite → stores tasks
2. Key decisions (important for marks)
Used Flask for simplicity
Used SQLite → no setup required
Kept API RESTful
Used CORS for frontend-backend communication
3. Evaluation criteria mapping
✔ Structure → separated frontend/backend
✔ Simplicity → easy readable code
✔ Correctness → DB constraints + API checks
✔ Interface Safety → JSON validation
✔ Change resilience → modular endpoints
✔ Observability → simple debug logs
✔ AI usage → (you can say you used AI to scaffold and reviewed manually)
