<div align="center">

# SağlıkAI

**AI-assisted health-data research prototype** · TÜBİTAK 2209-A graduation project

</div>

> Research prototype. Not a medical device, does not diagnose. No real patient data is stored in any repository.

## Architecture

| Layer | Repo | Stack |
|---|---|---|
| Platform | `health-platform` | Angular · Spring Boot · MySQL · OpenAPI contract |
| AI service | `health-ai` | FastAPI · document extraction · rules · evaluation |

The two services talk through a versioned OpenAPI contract, checked by CI (SHA-256 lock) so they never drift.

## Focus

- Document and lab-report information extraction
- Rule layer and explainable evaluation
- Trend analysis and ML models (planned)

Source repositories are private while the prototype is in development.
