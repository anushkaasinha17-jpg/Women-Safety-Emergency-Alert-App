# 🅿 ParkEase – Campus Parking Slot Booking System

> **Subject:** Software Project Management  
> **Topic:** Parking Slot Booking for Campus  
> **Academic Year:** 2024–25

---

## 📌 Project Overview

**ParkEase** is a web-based campus parking management system that allows students, faculty, and staff to **reserve parking slots in advance**, view **real-time availability**, and enter/exit campus using a **QR code**. It eliminates the inefficiency of manually searching for parking spots on a busy campus.

---

## 🎯 Objectives

- Reduce vehicle congestion at campus entry points
- Provide a digital, contactless parking experience
- Give administrators real-time visibility of parking utilization
- Ensure fair allocation of limited parking resources

---

## 🗂️ Repository Structure

```
parking-slot-booking/
│
├── index.html          # Main UI – Home, Booking, Live Map, Team
├── style.css           # Full responsive stylesheet
├── README.md           # Project documentation (this file)
│
├── diagrams/
│   ├── use_case_diagram.png        # UML Use Case Diagram
│   ├── er_diagram.png              # Entity-Relationship Diagram
│   ├── dfd_level0.png              # DFD Level 0 (Context Diagram)
│   ├── dfd_level1.png              # DFD Level 1
│   ├── class_diagram.png           # Class Diagram
│   ├── sequence_diagram.png        # Sequence Diagram – Booking Flow
│   └── system_architecture.png     # System Architecture Overview
│
└── report/
    └── SPM_ParkEase_Report.pdf     # Full project report
```

---

## ⚙️ Key Features

| Feature | Description |
|--------|-------------|
| 🔐 Campus SSO Login | Authenticate via university credentials |
| 📍 Real-Time Slot Map | Live view of available / occupied / reserved slots |
| 📅 Advance Booking | Reserve slot up to 7 days in advance |
| 📱 QR Code Entry | Auto-generated QR for contactless gate access |
| 🔔 Notifications | Email/SMS alerts for confirmations and reminders |
| 📊 Admin Dashboard | Utilization analytics, violation tracking |
| ♿ Priority Zones | Dedicated slots for faculty, EV, differently-abled |

---

## 🛠️ Tech Stack (Proposed)

| Layer | Technology |
|-------|-----------|
| Frontend | HTML5, CSS3, JavaScript |
| Backend | Node.js / Django REST API |
| Database | MySQL / PostgreSQL |
| Auth | JWT + University SSO (OAuth2) |
| Notifications | Firebase Cloud Messaging / Twilio SMS |
| Deployment | AWS / Heroku / College Server |

---

## 🧩 System Modules

1. **User Authentication Module** – Role-based access (Student / Faculty / Admin)
2. **Booking Module** – Slot selection, time window, vehicle info
3. **Slot Management Module** – Real-time sensor/status updates
4. **QR Gate Module** – Code generation and gate integration
5. **Admin Module** – Dashboard, reports, override controls
6. **Notification Module** – Email/SMS triggers

---

## 🗺️ Diagrams Included

- ✅ Use Case Diagram
- ✅ Entity-Relationship (ER) Diagram
- ✅ Data Flow Diagram – Level 0 & Level 1
- ✅ Class Diagram
- ✅ Sequence Diagram (Booking Flow)
- ✅ System Architecture Diagram

---

## 📋 SPM Artifacts

- **SRS** – Software Requirements Specification
- **Project Schedule** – Gantt Chart (in Report PDF)
- **Risk Register** – Identified risks and mitigation strategies
- **WBS** – Work Breakdown Structure
- **Test Plan** – Unit, Integration, and UAT test cases

---

## 👩‍💻 Team

| Role | Responsibility |
|------|---------------|
| Project Lead | System Design, Architecture, Coordination |
| Backend Developer | Database Design, REST API |
| Frontend Developer | UI/UX, Prototyping, index.html |
| QA Engineer | Test Planning, Documentation |

---

## 📄 License

This project is created for academic purposes under the Software Project Management course.  
© 2025 – All rights reserved by the project team.
