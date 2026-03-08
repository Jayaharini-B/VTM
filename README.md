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
