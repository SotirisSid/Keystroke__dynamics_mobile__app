# 📱 Keystroke Dynamics Mobile Application

A cross-platform Flutter mobile application implementing **Keystroke Dynamics** as a behavioral biometric authentication mechanism.

This project was developed as part of a thesis on behavioral biometrics and continuous authentication.

---

## 🧠 Project Overview

This application captures and analyzes user typing behavior in order to authenticate users based on **how they type**, rather than just what they type.

The system works in combination with a Flask backend server that performs:

- Keystroke data processing
- Feature extraction
- Machine learning model training
- Identity verification

⚠️ The mobile application **requires the Flask backend server** to run.

Backend Repository:
👉 https://github.com/SotirisSid/Flask_server

---

## 🚀 Features

- User Registration
- User Login
- Keystroke Dynamics Training Mode
- Behavioral Biometric Data Collection
- Password Typing Pattern Capture
- REST API Communication with Flask Backend
- Cross-platform Support:
  - Android
  - iOS
  - Web
  - Windows
  - macOS
  - Linux

---

## 📊 Collected Keystroke Features

The application captures:

- Key press timestamps
- Key release timestamps
- Hold time (key press duration)
- Flight time (time between consecutive key presses)
- Typing rhythm patterns

These features are used for behavioral biometric authentication.

---

## 🛠 Tech Stack

### Mobile Application
- Flutter
- Dart
- REST API communication
- Secure storage

### Backend (Required)
- Python
- Flask
- Machine Learning libraries (see backend repository)

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Mobile App Repository

```bash
git clone https://github.com/SotirisSid/Keystroke__dynamics_mobile__app
.git
cd Keystroke__dynamics_mobile__app

