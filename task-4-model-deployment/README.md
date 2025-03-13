# Model Deployment - Flood Prediction and Management (Research Phase)
## Overview
This folder contains research, findings, and deployment scripts for deploying the flood prediction model as part of the Omdena AI Karimganj Assam Chapter project. The goal is to ensure a scalable, efficient, and reliable deployment pipeline for real-time predictions. Additionally, integrating an alert system for flood warnings.

### Folder Structure
```bash
task-4-model-deployment/
│── research/              # Research and findings on deployment strategies  
│── deployment_scripts/    # Scripts for deploying the model
│── frontend/              # Streamlit frontend code  
│── Dockerfile             # Containerization setup (TBD)  
│── requirements.txt       # Dependencies for the deployment  
│── main.py                # API script for serving predictions  
│── config/                # Configuration files  
│── README.md              # Documentation
```
### Deployment Process
1. Setup Environment
Ensure you have the required dependencies installed:

```bash
pip install -r requirements.txt
```
2. Run Locally
If the model is served via an API (e.g., FastAPI/Flask), you can start the server locally:

```bash
python main.py
```
Access the API at: http://localhost:8000

3. Run Frontend
To start the Streamlit UI:

```bash
streamlit run frontend/app.py
```

### Technology Stack
- **Model Framework:** TensorFlow/PyTorch/Scikit-learn - TBD
- API Framework: FastAPI/Flask
- Frontend - Streamlit
- Containerization: Docker (if applicable) - TBD
- Cloud Provider: GCP/AWS/Azure - TBD

### Contributions & Next Steps
- Twilio API is used to send SMS alerts to users if a flood is predicted
- Database for users ie users.csv
- Further optimizations for scalability ie Cloud & Docker
- Replace mock model with a trained flood prediction model
- For any contributions, please follow the project guidelines.
