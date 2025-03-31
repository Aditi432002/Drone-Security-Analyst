Drone Security Analyst Agent

Overview
This project implements a Drone Security Analyst Agent that processes simulated drone telemetry and video frames to detect objects, generate security alerts, and index video frames for retrieval.

Features
Automated monitoring and security alerts.
Video frame and telemetry data processing.
Object detection and event logging.
Frame-by-frame indexing for querying by time or object.

Requirements
Python 3.x
OpenCV
SQLite
FFmpeg

Google Colab 

Installation & Setup
Install dependencies:
pip install opencv-python sqlite3 ffmpeg-python
Clone the repository:
git clone https://github.com/Aditi432002/Drone-Security-Analyst.git
Navigate to the project folder:
cd drone-security-agent
Run the main script:
python main.py
Design & Architecture
Data Pipeline: Simulated telemetry and video frames are processed.
Storage: Indexed in an SQLite database.
Alert System: Detects specific security events.
Retrieval: Query-based search for indexed frames.
AI Integration
AI-driven object detection logic.
AI-generated alert rules for anomaly detection.
Log verification.
Alert triggering tests.
Indexing and retrieval validation.

Usage

Run the script to simulate drone monitoring.
View logs and alerts in the database.

Aditi Borade

