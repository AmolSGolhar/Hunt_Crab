# Hunt_Crab
# Hunt Crab Attack - Simulating Zero-Day Phishing

A cybersecurity simulation project designed to emulate zero-day phishing scenarios in a sandboxed environment. This research-based system aims to raise awareness about phishing techniques and evaluate user behavior, system responses, and detection mechanisms.

> ⚠️ This project is for **academic and ethical research purposes only**. No part of this repository should be used for malicious or unauthorized activity.

## 📖 Overview

Hunt Crab Attack simulates realistic phishing campaigns to study:
- User interactions with phishing messages.
- Behavioral patterns under urgency cues.
- The effectiveness of detection systems (IDS, MFA, etc.).
- Safe malware emulation and telemetry collection.

## 🛠️ Tech Stack

- **Frontend Simulation**: [Gophish](https://getgophish.com/), Social-Engineer Toolkit (SET)
- **Emulated Malware**: Python + Bash (for system behavior simulation)
- **Backend Dashboard**: Flask server with JSON logging
- **Infrastructure**: SSH/Ngrôk for controlled tunnel access

## 🎯 Features

- Simulated phishing emails, SMS, and chat messages
- Click/credential capture with safe redirection
- Emulated malware behaviors (no real system harm)
- Data collection: timestamped logs, audio/image telemetry
- Dashboard for monitoring attack simulation lifecycle

## 🔒 Ethical Boundaries

- All simulations are confined to **isolated virtual machines (VMs)**.
- No real user data is captured or transmitted.
- The system is designed with **fail-safe mechanisms** and **controlled scripts**.
- **Usage of this system outside controlled environments is strictly prohibited.**

## 🖼️ Screenshots

![Phishing Dashboard](screenshots/dashboard.png)
![Ngrok Tunnel](screenshots/ngrok.png)

## 🚀 Getting Started (for research labs)

```bash
# Clone repo
git clone https://github.com/your-username/hunt-crab-attack.git

# Navigate
cd hunt-crab-attack

# Set up Flask server
pip install -r requirements.txt
python server.py

# Launch simulation in VM (with Gophish or SET)

