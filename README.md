🚗 CareDrive Duo

Smart Road Safety for Vulnerable Drivers

🧠 Overview

CareDrive Duo is a dual-application mobile safety solution designed to protect elderly and vulnerable drivers.
Using only smartphone sensors, it detects risky behaviors, identifies fatigue, monitors navigation, and alerts a trusted person in real-time.

This project consists of two connected applications:

App	Role
📱 CareDrive Senior	Installed on driver’s phone — risk detection & emergency alerts
🧑‍🦳 CareDrive Guardian	Monitoring app for trusted family member or caregiver
🎯 Objectives

Improve driver safety without reducing autonomy

Alert a guardian in case of accident or abnormal behavior

Enable fast intervention (emergency services, police…)

Provide non-intrusive monitoring with consent

🧩 Features
🔹 CareDrive Senior (Driver App)

🚦 Speed monitoring (GPS vs speed limits)

🛣 Route deviation detection

💤 Fatigue identification (camera-based: micro-sleep, prolonged eye closure…)

💥 Crash / sudden stop detection (accelerometer + gyroscope)

🚨 Intelligent alerts:

⚠️ Warning alerts (risk detected)

🚨 Critical alerts (accident, non-responsive driver)

🎥 Secure streaming/video recording during incidents

🔐 Privacy control with user consent

🔹 CareDrive Guardian (Family/Caregiver App)

📍 Real-time location & status (speed, movement, battery)

👁 Remote visual confirmation (front/back camera — with driver approval)

🆘 Emergency actions:

🚑 Call ambulance

🚓 Contact police

🔧 Road assistance

📞 Direct call / Navigation to driver

📜 Alert & incident history

🧠 Technology & Sensors
Component	Purpose
GPS	Speed, routing, position tracking
Cameras (front/back)	Fatigue detection & accident recording
Accelerometer / Gyroscope	Collision + abnormal motion detection
Microphone (optional)	Health/attention assessment
WebSocket	Real-time messaging
Backend API	Secure data storage & alerts

👁‍🗨 AI Embedded: MediaPipe + rule-based anomaly detection

🏗 System Architecture
📱 CareDrive Senior App
   ⇅  (WebSocket + Secure API)
☁️ Backend Server — Real-Time Event Management
   ⇅
👨‍👩‍👦 CareDrive Guardian App

🚀 Development Roadmap
Phase	Features	Status
1. Base Platform (3–5 days)	UI/UX + GPS tracking + WebSocket	⏳ Planned
2. Risk Monitoring (5–7 days)	Fatigue detection + guardian dashboard + camera access	⏳
3. Emergency Management	Video recording + survival timers + alert history + real tests	⏳
🔐 Privacy & Ethical Design

No tracking without explicit driver consent

Camera access never hidden

Auto-permissions only during a confirmed accident

Data encrypted & minimal collection

➡ Supports families without disrupting driver independence

📄 License

To be defined (MIT/Apache-2.0 recommended)

👥 Contributing

Pull requests are welcome!
Please open an Issue for major changes or feature proposals.
