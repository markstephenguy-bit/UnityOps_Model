# QC Submission
Persona: QC Tech
Goal: Capture QC with moisture %, defect notes, and photo; alert supervisor if threshold exceeded.

Scenarios:
- Happy path: Given connected agent, When submit valid fields & photo, Then record persists, event emits, UI shows success.
- High moisture: … Then supervisor receives alert within 2 min.

Acceptance:
- Required fields: sample_id, line, measured_at, moisture_pct
- Moisture range 0–100%; warn outside 6–19
- Photo optional; max 10 MB; stored in blob; URL recorded
