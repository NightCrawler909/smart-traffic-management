# 🚦 Smart Traffic Management System

An AI-based smart adaptive traffic management system with real-time monitoring and optimization using Computer Vision.

## 🗒️ Overview

The Smart Adaptive Traffic Management System leverages AI and computer vision to optimize traffic flow at intersections. This system analyzes vehicle counts from video feeds, processes the data using machine learning models, and dynamically adjusts traffic signal timings to reduce congestion and improve traffic flow.

## 📸 Screenshots

| Dashboard | Analysis & Processing | Results |
|:---:|:---:|:---:|
| ![Dashboard](screenshots/1.png) | ![Analysis](screenshots/2.png) | ![Optimization Results](screenshots/3.png) |

## ✨ Features

- **Real-Time Vehicle Detection:** Uses **YOLOv4-tiny** and OpenCV for high-speed, real-time vehicle detection from video feeds.
- **Traffic Optimization Engine:** Employs an algorithmic approach (Genetic Algorithm) to calculate and determine optimal green light times based on live vehicle density.
- **Interactive Web Dashboard:** A responsive React-based interface allowing users to upload traffic videos, view processing results, and receive optimized traffic management recommendations.
- **API-Driven Architecture:** A lightweight Flask backend serving the ML model and integrating smoothly.

## 🛠️ Tech Stack

- **Frontend:** React.js, Axios, HTML/CSS
- **Backend:** Python, Flask, Flask-CORS
- **AI & Computer Vision:** OpenCV, YOLOv4-tiny
- **Optimization:** NumPy, SciPy

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Node.js (v14 or later)
- YOLOv4 weights and configuration files (included in \ackend/\)

## 💻 Local Setup

1. **Clone the repository:**

\\\ash
git clone https://github.com/NightCrawler909/smart-traffic-management.git
cd smart-traffic-management
\\\

2. **Start the backend server:**

\\\ash
cd backend
pip install -r requirements.txt
python app.py
\\\

3. **Start the frontend application:**

Open a new terminal and navigate to the frontend directory:
\\\ash
cd frontend
npm install
npm start
\\\

4. **Upload Traffic Videos & Run:**
Access the web dashboard in your browser (usually \http://localhost:3000\). Upload 4 traffic videos corresponding to different lanes of an intersection. The system will process the footage and display the optimized green light timings.

## 🙏 Acknowledgments

- **YOLOv4:** For fast and efficient vehicle detection.
- **OpenCV:** For robust video frame processing.
- The contributors of the Genetic Algorithm logic for traffic light optimization.
