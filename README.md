# Stroke Risk Prediction System — Team HeartGuard

## 🔍 Project Overview

Stroke Risk Prediction System is a full-stack web application designed to assess a user’s risk of stroke based on their medical and lifestyle inputs. Built with Django and powered by a trained machine learning model, the system provides real-time stroke risk predictions and visualizes historical trends. Users register and log in securely using OTP-based authentication, submit health data through a dynamic form, and receive a categorized risk assessment (Low, Moderate, or High). The platform emphasizes usability, security, and preventive healthcare awareness.

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

### Running Locally

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
