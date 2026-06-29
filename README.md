# 🎓 Campus Events & Opportunities Platform - Event Opps 

A modern, high-converting, Unstop-inspired event management and tracking platform built tailored for **IGDTUW**. The application features a clean, responsive UI styled around the signature collegiate green theme and operates entirely as a modular frontend prototype. 
<br>
UNSTOP FOR IGDTUW

---

## 🚀 Features

### 👤 Student Dashboard
* **Trending Highlights:** A dedicated top-tier grid recommending the most registered and popular active campus sessions.
* **Opportunities Feed:** Comprehensive grid displaying titles, hosting societies, and dynamic live registration metrics.
* **Interactive Event Modal:** Pop-up workspace revealing rich event breakdowns, timelines, prizes, and coordinator contact information.
* **Eligibility Guardrails:** Auto-evaluates user profiles; checks for host-mandated constraints (e.g., locking registrations exclusively to `@igdtuw.ac.in` domains).
* **My RSVPs Tracker:** A personalized history panel compiling a student's past, current, and confirmed session logs.

### 🏢 Host & Society Dashboard
* **Chronological Event Tracking:** Clear tabbed views organizing society operations into **Past**, **Ongoing**, and **Future** statuses.
* **Past Events Ledger:** View historic analytical metrics and log final event winners.
* **Ongoing Management Hub:** Access full participant rosters, manage real-time attendee data lists, and modify active details.
* **Future Upload Console:** Strategic form wizard to publish upcoming opportunities complete with strict or open eligibility toggles.

### 🔐 Authentication System
* Dual-mode portal allowing seamless switching between **Student Signup** (capturing branch, graduation year, course, and verification actions) and **Host Registration** (requiring verification against a verified `@igdtuw.ac.in` profile).

---

## 📂 Project Architecture

The project has been refactored away from a monolithic block into a clean, decoupled development structure:

```text
├── index.html   # Semantic layout structure & core multi-view DOM elements
├── styles.css   # Document architecture, custom green palette properties, & micro-animations
└── app.js       # Client-side routing, state manipulation, validation, & persistent data mocking
```

## ❤️ **Team CloudTitans**
* Jinal Agarwal (Team Member 1 - Team Leader, Frontend Developer)
* Gauri Kumari (Team Member 2 - Cloud Architect)
* Ishita Sharmaa (Team Member 3 - Backend Developer)
