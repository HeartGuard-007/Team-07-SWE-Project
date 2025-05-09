# 🧠 Stroke Risk Prediction System — Team HealthGuard

## 🔍 Project Overview

This web application predicts the risk of stroke based on user-provided health information. It uses a trained machine learning model (Random Forest Classifier) integrated into a Django backend. Users log in with OTP-based authentication, enter health data, and receive a personalized stroke risk prediction. Results are saved and visualized over time.

---

## 👥 Team Roles

- **Nitesh** – Project Manager  
- **Nihaal** – Backend Developer (ML integration)  
- **Praneeth** – Backend Developer (Authentication + OTP)  
- **Shishir** – Fullstack Developer (Integration + History Chart)  
- **Shreyas** – Frontend Developer (UI/UX + Page Design)  
- **Varun** – Frontend Developer (Validation + Error Handling)

---

## 🚀 Deployment / Running the Project Locally

### ✅ Option 1: Run Locally

#### Prerequisites
- Python 3.8+
- pip
- Virtualenv (recommended)

#### Steps
```bash
# Clone the repository
git clone https://github.com/your-username/stroke-risk-prediction.git
cd stroke-risk-prediction

# Create virtual environment
python -m venv env
source env/bin/activate  # For Linux/macOS
env\Scripts\activate     # For Windows

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Run the server
python manage.py runserver
