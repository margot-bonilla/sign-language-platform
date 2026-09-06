# Real-Time Sign Language Translator

An interactive, real-time translator that converts sign language into text/speech using Computer Vision. Designed as a free accessibility tool, this project is built on a microservices architecture to ensure scalability and fast inference.

## 🏗 Architecture & Tech Stack

The project is divided into specialized services:

*   **AI Microservice (Vision):** Python, FastAPI (WebSockets), OpenCV, MediaPipe.
*   **Core Microservice (Backend):** Java 17, Spring Boot, Spring Security, PostgreSQL.
*   **Frontend (UI Client):** HTML/JS or React (Webcam Capture & Real-time display).
*   **DevOps & Orchestration:** Docker, Docker Compose.

## 📂 Repository Structure (Monorepo)

*   `/ai-service`: Real-time inference API (Python).
*   `/backend-core`: User management, translation history, and analytics API (Java).
*   `/frontend`: User interface for real-time webcam translation.
