# Pachaug College Information System (PCS-1.0)

A self-contained, 100% offline-first Flutter mobile application designed to help college students organize their semester syllabi, track upcoming assessments, manage study notes, and filter weekly deadlines without relying on slow web portals.

## Key Features
* **100% Offline-First Storage:** Access all course details, class schedules, and exam types locally on your device with zero external APIs.
* **Dual-Engine Local Persistence:** Organizes academic hierarchies in **SQLite** while storing fast study notes in **Hive**.
* **Semester & Deadline Mapping:** View upcoming exams, project milestones, and coursework in a clean, week-by-week timeline.
* **Quick Study Notes & Sharing:** Jot down lecture notes and share them directly via native email to classmates with a single tap.
* **Privacy & Simplicity:** Protected behind a local profile with zero cloud dependencies or cluttered logins.

## Pre-Code Documentation Pipeline
All specifications are hosted in the **[Project Wiki](https://github.com/HeinoPortfolio/Pachaug-College-Information-System/wiki)**:

1. **[Project Charter](https://github.com/HeinoPortfolio/Pachaug-College-Information-System/wiki/Project-Charter)**
2. **[Operational Scenario](https://github.com/HeinoPortfolio/Pachaug-College-Information-System/wiki/Scenario)**
3. **[Business Requirements (BRD)](https://github.com/HeinoPortfolio/Pachaug-College-Information-System/wiki/Business-Requirements)**
4. **[Software Requirements Specification (SRS)](https://github.com/HeinoPortfolio/Pachaug-College-Information-System/wiki/Software-Requirements-Specification)**
5. **[System Architecture & Data Design (SDD)](https://github.com/HeinoPortfolio/Pachaug-College-Information-System/wiki/System-Architecture-and-Data-Design)**
6. **[Test Plan & Traceability Matrix](https://github.com/HeinoPortfolio/Pachaug-College-Information-System/wiki/Test-Plan-and-Traceability-Matrix)**

## Tech Stack
* **Framework:** Flutter (Dart)
* **Local Relational Database:** SQLite
* **Local Key-Value / NoSQL Storage:** Hive
* **Platform Integrations:** Native OS Notifications, Calendar Date Pickers, and Native Email Client

## Getting Started
```bash
git clone https://github.com
cd Pachaug-College-Information-System
```

## Project Status
* [x] Wiki Documentation Pipeline & Skeleton Setup
* [x] Operational Scenario & Business Requirements Document (`BRD`)
* [ ] Project Charter, SRS, SDD, and Core Implementation

