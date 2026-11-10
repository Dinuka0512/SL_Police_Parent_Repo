# 🇱🇰 SL Police – AI & ML Based Public Safety System

An integrated software solution designed to support public safety and police-related operations in Sri Lanka using modern web technologies and machine learning.

## 📌 Project Overview

SL Police is a multi-component software project that combines web applications, backend services, alert management, and machine learning capabilities.

The system is organized into separate repositories to keep each component independent, maintainable, and easier to develop.

## 🏗️ Project Architecture

The project consists of the following components:

| Component | Description | Repository |
|---|---|---|
| Main Application | Main SL Police application | [SL-Police-Alerts](https://github.com/Dinuka0512/SL-Police-Alerts) |
| Main Backend | Backend services for the main application | [sl-police-backend](https://github.com/Dinuka0512/sl-police-backend) |
| Admin Panel | Administrative dashboard | [sl-police-admin-panel](https://github.com/Dinuka0512/sl-police-admin-panel) |
| ML Backend | Machine learning prediction service | [sl-police-ml-backend](https://github.com/Dinuka0512/sl-police-ml-backend) |
| Alerts Backend | Backend services for alert management | [sl-police-alerts-backend](https://github.com/Dinuka0512/sl-police-alerts-backend) |

## 🤖 Machine Learning Component

The project includes a machine learning component developed to analyze historical road accident data and predict accident counts across different districts.

**ML Workflow:**

1. Collect and prepare historical road accident data.
2. Process and analyze data using Python libraries.
3. Train a machine learning model.
4. Save the trained model as a `.pkl` file.
5. Load the saved model through a FastAPI service.
6. Expose prediction functionality through REST API endpoints.
7. Integrate prediction results with the main system.

### Machine Learning Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- LightGBM
- FastAPI
- Pickle

## 🛠️ Technologies

The project uses technologies across multiple development areas:

- **Frontend:** React, TypeScript, Tailwind CSS
- **Backend:** Node.js, REST APIs
- **Machine Learning:** Python, Scikit-learn, LightGBM
- **ML API:** FastAPI
- **Version Control:** Git & GitHub

## 📂 Repository Structure

Each component is maintained in its own GitHub repository:

- `SL-Police-Alerts` – Main application
- `sl-police-backend` – Main backend
- `sl-police-admin-panel` – Admin dashboard
- `sl-police-ml-backend` – Machine learning API
- `sl-police-alerts-backend` – Alert management backend

## 🎯 Project Goals

- Support public safety through technology.
- Apply machine learning to historical road accident data.
- Provide a structured system with independent components.
- Improve maintainability through separated services.
- Explore practical integration between frontend, backend, and ML systems.

## 👨‍💻 Developer

**Heshan Dinuka Lakmal**

- GitHub: [@Dinuka0512](https://github.com/Dinuka0512)
- Portfolio: [dinukadev.com](https://dinukadev.com)

---

*Developed as a software engineering project exploring full-stack development, API integration, and machine learning applications for public safety.*
