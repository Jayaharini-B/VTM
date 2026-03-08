🎙 Smart Secure Voice ATM with Fingerprint Authentication
📌 Project Overview

Smart Secure Voice ATM is a multilingual, voice-enabled ATM system integrated with:

🔐 Dual Fingerprint Authentication

🎤 Voice Command-Based Transactions

🌍 Multi-language Support (English, Tamil, Hindi)

📩 SMS Transaction Alerts

💳 Secure Debit Confirmation

🔌 Arduino-based Cash Dispensing System

This system enhances ATM accessibility for visually impaired and elderly users while ensuring high security through double biometric verification.

🚀 Key Features
✅ 1. Fingerprint Authentication

User identification using fingerprint sensor

Second fingerprint verification before cash dispensing

✅ 2. Voice-Based Navigation

User says:

"Proceed"

"Check Balance"

"Debit"

Amount commands (One thousand, Two thousand, etc.)

"Confirm"

✅ 3. Multilingual Support

English

Tamil

Hindi

✅ 4. Secure Transaction Flow

Amount confirmation

Double fingerprint validation

Serial command sent to Arduino for dispensing

✅ 5. SMS Transaction Alert

After successful withdrawal:

Smart Secure ATM Alert
Branch: Smart Secure Voice ATM - Khar Branch
User: Arun
Amount Withdrawn: ₹5000
Status: Successful Transaction
🛠 Technologies Used
Technology	Purpose
Python	Core programming
VOSK	Offline speech recognition
gTTS	Text-to-Speech
Twilio API	SMS notifications
Arduino	Cash dispensing control
PySerial	Serial communication
SoundDevice	Voice input capture
🏗 System Architecture

Fingerprint sensor verifies user

Voice recognition captures transaction command

System confirms amount

Second fingerprint verification

Arduino receives dispense command

SMS alert sent to registered number




🏦 ATM AI Security Monitoring System
(ESP32 + Camera + YOLOv4-Tiny + RTSP + Web Dashboard)
📌 Project Overview

This project implements an AI-powered ATM security monitoring system using an ESP32 camera module with real-time object detection.

The system:

Detects number of persons in front of ATM

Triggers buzzer if multiple persons detected

Streams live RTSP video

Hosts a live monitoring web dashboard

Displays SAFE / ALERT status

This enhances ATM security by preventing shoulder surfing and suspicious crowding.

🚀 Key Features
✅ Real-Time Person Detection

Uses YOLOv4-Tiny model

Detects objects in video stream

Counts number of persons

✅ Security Logic

SAFE → 0 or 1 person detected

ALERT → More than 1 person detected

Buzzer activates during ALERT mode

✅ Live RTSP Video Streaming

Access camera stream using:

rtsp://<ESP32_IP>:<PORT>
✅ Web-Based Monitoring Dashboard

Access via browser:

http://<ESP32_IP>

Auto-refreshes every 2 seconds.

🛠 Technologies Used
Technology	Purpose
ESP32 Camera	Video capture
YOLOv4-Tiny	Object detection
RTSP	Live streaming
WiFi Server	Web dashboard
C++ (Arduino)	Firmware development
🏗 System Architecture

Camera captures video

YOLO model detects objects

System counts "person" objects

If person_count > 1:

Buzzer ON

Status = ALERT

Web dashboard displays live status

RTSP stream available for monitoring
