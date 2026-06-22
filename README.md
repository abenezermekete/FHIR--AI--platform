# FHIR--AI--platform
# FHIR AI Interoperability Platform


##  Overview
This project demonstrates a healthcare interoperability platform
based on HL7 FHIR standards, combined with a simple AI model for
clinical risk prediction.

It simulates how Electronic Health Record (EHR) systems can exchange
data and integrate intelligent decision-support tools.

---

##  Features

- ✅ FHIR-based Patient resource
- ✅ REST API using FastAPI
- ✅ PostgreSQL database integration
- ✅ AI risk prediction module
- ✅ Deodorized environment

---

##  Architecture

Client → FastAPI → PostgreSQL  
                     ↓  
                   AI Model  

---

##  Tech Stack

- Python (FastAPI)
- PostgreSQL
- SQLAlchemy
- Docker
- HL7 FHIR (data structure)

---

## 🧪API Endpoints

### Create Patient
POST `/patients/`

### Get Patients
GET `/patients/`

### Predict Risk
GET `/predict-risk?age=60`

---

##  AI Component

A simple predictive function estimates patient risk based on age.
This demonstrates how AI models can be integrated into clinical workflows.

---

## Why This Project Matters

Healthcare systems often suffer from fragmented data across different systems.



##  How to Run (Docker)

```bash
docker-compose up --build
