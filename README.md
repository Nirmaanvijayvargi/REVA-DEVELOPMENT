# REVA | Smart Waste Management System 🗑️🌱

**An IoT-powered solution for sustainable campus hygiene.**
REVA is an IoT-enabled smart waste management prototype built to explore how software systems can improve campus hygiene through better visibility and decision-making.

This project was developed as a demonstration / academic prototype, not a production deployment. The focus was on designing a clear system, usable dashboards, and meaningful alerts rather than shipping a finished product.

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge)](https://reva-development.vercel.app/)
[![Vercel Status](https://img.shields.io/badge/Vercel-Deployed-black?style=for-the-badge&logo=vercel)](https://reva-development.vercel.app/)

---

## 📌 Overview
On large campuses, waste collection is usually manual and periodic. This often results in bins being cleaned too early, too late, or without any real data backing those decisions.

REVA explores a simple idea: What if cleaning staff and administrators could clearly see bin status in real time and act only when needed?

The system connects sensor data from bins to a web-based dashboard that shows activity, status, and alerts in one place.

### 🚀 Key Features
**Dashboard for Monitoring: A clean, readable interface to view bin activity and status**

**Real-time Fill-Level Representation: Visual indicators based on sensor input**

**Role-based Access (Prototype): Interfaces designed with different users in mind (staff, admin, visitors)**

**Alert & Alarm System: Audio alerts designed to be noticeable without being disruptive**

**Sustainability-Oriented Thinking: Reduces unnecessary checks and manual effort**

---

## 🛠️ Tech Stack
* **Frontend:** HTML5, Tailwind CSS
* **Hosting:** Vercel
* **Version Control:** Git & GitHub
* **Hardware (Conceptual):** Arduino/ESP32, Ultrasonic Sensors (HC-SR04)
  

---

🧠 My Role

I worked on the entire software side of REVA:

full-stack development

system and data-flow design

dashboard UI and interaction logic

Other team members focused on the hardware setup and physical prototype.

---

⚙️ What I Worked On

designing and building the dashboard interface

implementing login and basic access flow

displaying live bin activity on the dashboard

visualizing sensor data using graphs

updating bin status dynamically based on sensor input

The emphasis was always on clarity and usability, not just functionality.

---

🔧 Hardest Technical Challenge

Designing the alarm system was the most challenging part.

It wasn’t only about triggering a sound, but about usability. I experimented with:

different alert sounds

pitch and tone suitability

repetition frequency

avoiding alerts that were either annoying or easy to ignore

The goal was an alert that clearly signals action without overwhelming the user.


---

📊 Project Status

✅ Working prototype

🚫 Not deployed in real-world use

REVA was built as a personal academic project to explore system design and UI-driven monitoring.


---


## 👥 The Team
* **Nirmaan Vijay Vargi** - Lead Developer
* **Nakshatra Vijay Vargi** - Hardware Lead
* **Thunga Chandrahas** - IoT Specialist

---

## 📂 Project Structure
```text
├── index.html        # Main Dashboard
├── about.html        # Team & Contact Information
├── vercel.json       # Deployment configuration
└── assets/           # Images and icons (To be added)
---
```


🎯 What I’m Proud Of

translating a real-world campus problem into a working prototype

designing a dashboard usable by non-technical users

connecting physical sensor activity to meaningful UI updates

thinking through alert design from a user’s perspective

---

📚 Learnings

good dashboards prioritize clarity over visual complexity

alert systems require both technical and human judgment

system design is as much about user behavior as it is about code

REVA helped shape how I think about building useful systems, not just functional ones.
