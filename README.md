📱 AI-Powered Mobile Security & Privacy Guard (Android)

Advanced Android Security App • AI + Heuristics • Jetpack Compose • Clean Architecture

A modern Android application that protects users from malicious apps, privacy leaks, phishing/spam SMS, and unsafe networks — powered by on-device AI, system-level heuristics, and real-time monitoring.

This project demonstrates serious mobile engineering skills: AI integration, Android internals, permissions, background services, Clean Architecture, Jetpack Compose, and Kotlin coroutines.

⭐ Key Features
🔍 1. AI-Based App Risk Scanner

Analyzes installed apps using both heuristics and AI:

✔ Risk Factors (Heuristics)

Dangerous permission combinations

Background service count

Install source (Play Store / Sideloaded)

Update age

APK metadata anomalies

High-risk categories (unknown keyboard apps, VPN apps, etc.)

✔ AI (TensorFlow Lite Model)

The on-device model classifies apps into:

Safe

Potentially Risky

Dangerous

Input features include:
permission counts, service counts, installed source, API target, size, etc.

📡 2. Network Security Scanner

Real-time checks for unsafe network environments:

Wi-Fi encryption type: WPA3 / WPA2 / Open

ARP spoofing detection

Suspicious devices connected to hotspot

Unknown VPN detection

DNS hijacking indicators

Identifies captive portals

Produces a Network Risk Score.

✉️ 3. Spam & Phishing SMS Detector (AI)

On-device text classification using ML Kit or TF Lite NLP model.

Detects:

Phishing attempts

Scam messages

Fake bank OTP messages

URL-based fraud

Promo spam

Stores all flagged messages in a secure local log.

👁️ 4. App Behavior Monitor

Monitors suspicious runtime behavior:

App using camera/mic in background

Clipboard access (Android 12+)

Abnormal CPU usage heuristics

Excessive background data transfer

Sudden wake-lock activity

System event monitoring

Triggers notifications like:

“⚠️ App X accessed your microphone in the background.”

🛡 5. Security Dashboard

A single place to view:

Overall Security Score (0–100)

App risk score

Network risk score

Spam/phishing risk

Behavior alerts

One-tap “Optimize Security” suggestions

🧰 6. Privacy Tools

Permission manager

Clipboard protection

Unknown app installer monitor

Camera/mic usage visualizer