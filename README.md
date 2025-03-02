# 💖 TelMedSphere

An open-source telemedicine platform designed to provide easy access to healthcare for both doctors and patients. Patients can book consultations, manage health records, and make payments. Doctors can manage appointments, provide prescriptions, and offer effective healthcare services through video consultations.

🔗 **GitHub Repo**: [Link to GitHub](#)

---

## 🧾 Table of Contents
- 📌 [Introduction](#introduction)
- 💡 [Features](#features)
- 🚀 [Technology Used](#technology-used)
- ⭐ [Overview](#overview)
- 💥 [Getting Started](#getting-started)
- 🐳 [Docker Setup](#docker-setup)
- 📑 [API Documentation](#api-documentation)
- ⚡ [Project Admin & Mentors](#project-admin--mentors)
- 💬 [Join Chatting Server](#join-chatting-server)
- 📑 [Contributing Guidelines](#contributing-guidelines)
- 📑 [Code Of Conduct](#code-of-conduct)
- 📑 [License](#license)

---

## 📌 Introduction

TelMedSphere is designed to make healthcare simple and accessible for both doctors and patients. It allows patients to connect with doctors via video calls, manage health records, and make payments. Doctors can manage appointments, write prescriptions, and schedule consultations effectively.

---

## 💡 Features

### For Patients:
- **Book Video Calls**: Schedule video consultations with doctors.
- **Share Feedback**: Rate and review the doctor post-consultation.
- **Manage Profile**: View and update personal details.
- **View Past Records**: Access previous prescriptions and records.
- **Easy Payments**: Secure payment system powered by Stripe.

### For Doctors:
- **Set Up Profile**: Add your information and services.
- **Manage Availability**: Set your working hours.
- **Join Video Calls**: Connect with patients at the scheduled time.
- **Write Prescriptions**: Share prescriptions directly with patients.
- **Queue System**: Organize appointments efficiently with smart queue management.

---

## 🚀 Technology Used
- **Frontend**: ReactJS
- **Styling**: TailwindCSS
- **Backend**: Python, Flask
- **Database**: MongoDB Atlas
- **Containerization**: Docker

---

## ⭐ Overview
Live Project Demo ↗️ [Demo Link](#)

---

## 💥 Getting Started

### Local Setup

1. **Fork and Clone the Repository**
    - Fork the repository on GitHub.
    - Clone your forked repo:
    ```bash
    git clone https://github.com/<your-github-username>/TelMedSphere.git
    ```

2. **Frontend Setup**
    - Navigate to the frontend directory:
    ```bash
    cd frontend
    ```
    - Install npm packages:
    ```bash
    npm ci
    ```
    - Set up the `.env` file:
    ```bash
    cp .env.example .env
    ```
    - Start the frontend development server:
    ```bash
    npm run dev
    ```

3. **Backend Setup**
    - Navigate to the backend directory:
    ```bash
    cd backend
    ```
    - Set up the `.env` file:
    ```bash
    cp .env.example .env
    ```
    - Create and activate the virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # For Linux/MacOS
    venv\Scripts\activate     # For Windows
    ```
    - Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
    - Run the Flask server:
    ```bash
    flask run
    ```
    - Deactivate the virtual environment after you're done:
    ```bash
    deactivate
    ```

---

## 🐳 Docker Setup

### Prerequisites
- Install Docker and Docker Compose.

### Steps to Run with Docker
1. Clone the repository and set up environment variables.
2. Start the application:
    ```bash
    docker-compose up --build -d
    ```
    - Frontend: [http://localhost:3000](http://localhost:3000)
    - Backend: [http://localhost:5000](http://localhost:5000)

To stop the application:
    ```bash
    docker-compose down
    ```
To remove the container:
    ```bash
    docker-compose kill
    ```

---

## 📑 API Documentation

TelMedSphere provides a complete REST API documented via Swagger.

- Start Flask locally:
    ```bash
    flask run
    ```
- Open the Swagger UI at:
    [http://127.0.0.1:5000/api/docs](http://127.0.0.1:5000/api/docs)

---

## ⚡ Project Admin & Mentors
- **Project Admin**: Pratik Mane
- **Mentors**:
    - KWoC Mentor: Harshwardhan Patil
    - SWoC Mentor: Aditya Bavadekar
    - DWoC Mentor: Raj Khanke

**Contributors**: Swami Malode, Pushpak Gadhe, Himanshu Patil, Chetan Khaole

---

## 💬 Join Chatting Server
Join our Discord: [Discord Link](#)

---

## 📑 Contributing Guidelines
Please refer to the [Contributing Guidelines](#) for details on how to propose bug fixes, improvements, and contribute to the project.

---

## 📑 Code Of Conduct
The project adheres to a Code of Conduct. By participating, you agree to follow it.

---

## 📑 License
This project is licensed under the Apache License 2.0. See the LICENSE file for more details.

© 2025 Pratik Mane, Swami Malode, Pushpak Gadhe, Himanshu Patil, Chetan Khaole
