# 💗 SafeHer – Women Safety Emergency Alert App

> **Subject:** Software Project Management  
> **Topic:** Women Safety Emergency Alert App — SOS + Location Sharing Prototype  
> **Academic Year:** 2024–25

---

## 🌸 Project Overview

**SafeHer** is a mobile-first emergency safety application designed for women. It enables users to send an **instant SOS alert** with their **live GPS location** to a trusted circle of contacts and campus/local authorities — in a single tap, even from a locked screen.

The project addresses the critical real-world need for accessible, real-time safety tools for women on college campuses and beyond.

---

## 🎯 Objectives

- Enable instant SOS alerts with one tap or gesture (no unlocking needed)
- Share live GPS location with trusted contacts in real-time
- Provide covert safety features (fake call, silent recording)
- Empower women with preventive tools (safe route planner, heatmap)
- Create an admin/authority dashboard for incident tracking

---

## 🗂️ Repository Structure

```
safeher-sos-app/
│
├── index.html              # Main UI prototype — all screens
├── style.css               # Blush rose gold aesthetic stylesheet
├── README.md               # Project documentation (this file)
│
├── diagrams/
│   ├── use_case_diagram.svg         # UML Use Case Diagram
│   ├── er_diagram.svg               # Entity-Relationship Diagram
│   ├── dfd_level0.svg               # DFD Level 0 (Context Diagram)
│   ├── sequence_diagram.svg         # Sequence Diagram – SOS Flow
│   └── system_architecture.svg      # Full System Architecture
│
└── report/
    └── SPM_SafeHer_Report.pdf       # Full project report (add here)
```

---

## 🚨 Core Features

| Feature | Description |
|--------|-------------|
| 🆘 One-Tap SOS | Triggers emergency alert even from lock screen |
| 📍 Live Location Sharing | Real-time GPS sent to trusted contacts + authorities |
| 🎙️ Covert Audio Recording | Silent evidence recording stored securely in cloud |
| 👭 Trusted Circle | Up to 10 contacts notified via SMS + push notification |
| 📞 Fake Call | Triggers a fake incoming call to escape a situation |
| ✅ Check-In Reminders | Auto SOS if check-in is missed within time window |
| 🗺️ Safe Route Planner | AI-suggested routes avoiding high-incident zones |
| 📊 Incident Heatmap | Community-powered safety awareness map |

---

## 🛠️ Tech Stack (Proposed)

| Layer | Technology |
|-------|-----------|
| Frontend | HTML5, CSS3, JavaScript (Prototype) |
| Mobile App | Flutter / React Native |
| Backend | Node.js + Express REST API |
| Database | Firebase Firestore (real-time) + PostgreSQL |
| Auth | Firebase Authentication (Phone OTP) |
| Location | Google Maps API + GPS |
| Notifications | Firebase Cloud Messaging + Twilio SMS |
| Storage | Firebase Storage (audio evidence) |
| Deployment | Google Cloud / AWS |

---

## 🧩 System Modules

1. **User Authentication Module** — Phone OTP verification, profile setup
2. **SOS Trigger Module** — One-tap / gesture / shake detection
3. **Location Module** — Real-time GPS sharing, route tracking, trail storage
4. **Notification Module** — Push notification + SMS to trusted contacts
5. **Trusted Contacts Module** — Add/remove/manage emergency circle
6. **Fake Call Module** — Fake incoming call simulation
7. **Check-In Module** — Timed check-in with auto SOS fallback
8. **Admin/Authority Module** — Dashboard for campus security, police portal
9. **Heatmap Module** — Community incident reports and zone visualization
10. **Evidence Module** — Secure cloud storage for audio, location trails

---

## 🗺️ Diagrams Included

- ✅ Use Case Diagram
- ✅ Entity-Relationship (ER) Diagram
- ✅ Data Flow Diagram – Level 0 (Context Diagram)
- ✅ Sequence Diagram – SOS Alert Flow
- ✅ System Architecture Diagram

---

## 📋 SPM Artifacts

- **SRS** – Software Requirements Specification (Functional + Non-Functional)
- **WBS** – Work Breakdown Structure
- **Gantt Chart** – Project timeline (in Report PDF)
- **Risk Register** – Identified risks with mitigation strategies
- **Test Plan** – Unit tests, Integration tests, UAT for all modules
- **Use Case Specifications** – Detailed use case write-ups

---

## 📱 UI Prototype Screens (index.html)

The prototype demonstrates:
- ✅ Home screen with SOS button and live status
- ✅ Trusted contacts panel
- ✅ Fake call overlay
- ✅ Check-in timer
- ✅ Custom SOS message editor
- ✅ SOS activation overlay with contact notification simulation

---

## 👩‍💻 Team

| Role | Responsibility |
|------|---------------|
| Project Lead | System Design, Planning, Architecture, SPM docs |
| Backend Developer | API, Database, Firebase, Location Engine |
| Frontend Developer | UI/UX, Prototype, index.html + style.css |
| QA Engineer | Test Planning, SRS Documentation, Reports |

---

## 💗 Why SafeHer?

> *"1 in 3 women globally experience physical or sexual violence. Technology cannot solve everything — but it can buy time, alert help, and save lives."*

SafeHer is not just an academic project. It is a prototype with real-world potential for deployment on any college campus, giving every woman a direct line to safety in her pocket.

---

## 📄 License

Created for academic purposes under the Software Project Management course.  
© 2025 – SafeHer Team. All rights reserved.
