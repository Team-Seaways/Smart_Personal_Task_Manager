# 🧠 Smart Personal Task Manager (SPTM)

A modern full-stack task management system designed to improve productivity by applying **Franklin Covey’s priority-based model**. It provides advanced features such as recurring tasks, calendar visualization, intelligent reminders, and analytics — all within a responsive and intuitive web interface.

This project is developed as part of **CSE443 - Rapid Application Development** course.

---

## 📌 Purpose & Scope

SPTM transforms a traditional to-do list into a dynamic productivity platform with:

- ✅ Project-based task organization
- ✅ A/B/C/D **priority classification** (Franklin Covey Method)
- ✅ **Recurring task** automation (daily/weekly/monthly/custom)
- ✅ **Real-time reminders** (Email + In-App notifications)
- ✅ Calendar views (Daily / Weekly / Monthly)
- ✅ Advanced search & filtering
- ✅ Productivity analytics and reports

The system aims to support both **personal and professional** workload management with intelligent automation and visual clarity.

---

## ✨ Key Features

| Module | Capabilities |
|--------|--------------|
| ✔ User Management | Registration, login, JWT authentication, profile editing |
| ✔ Project Management | Create, update, delete, archive, completion stats |
| ✔ Task Management | CRUD tasks with description, priority, context, reminders, status tracking |
| ✔ Recurring Tasks | Custom recurrence patterns, editable instances |
| ✔ Calendar Views | Drag & drop scheduling, color-coded priorities |
| ✔ Notifications | Email & popup reminders, snooze, overdue alerts |
| ✔ Search & Filter | Priority, status, context, project, date range |
| ✔ Data Export | JSON export & import support |
| ✔ Progress Tracking | Statistics, charts & completion history |

---

## 🏗️ System Architecture

| Layer | Technology |
|------|------------|
| Frontend (SPA) | React 18 + TypeScript |
| Backend (API) | Java 17 + Spring Boot 3 |
| Database | PostgreSQL 15 |
| Authentication | JWT Security |
| Notifications | Email + WebSocket |
| Deployment | Docker & Maven packages |
| Design Patterns | Strategy, Observer, Factory, Repository, MVC |

---

## 📂 Branch Strategy

| Branch | Description |
|--------|-------------|
| `main` | Stable releases only |
| `development` | Feature integration branch |
| `documents` | Requirement docs, reports, UML, presentations (already exists ✅) |
| `feature/<name>` | One feature per branch |
| `hotfix/<name>` | Production fixes |

> PRs must target **development branch** ✅  
> All documentation → **documents branch** ✅

---

## 👥 Contributors

(Add GitHub profile links later)

| Name |
|------|
| Yavuz Selman Haltaş |
| Ünal Sarıemir |
| Yusuf Alperen Dönmez |
| Emre Can Tuncer |
| Alperen Özdelen |
|
|
|
|
|

(You asked for blank lines — feel free to fill them with IDs or roles later)

---

## 🚀 Getting Started

### ✅ Prerequisites
- Java 17+
- Node.js + npm/yarn
- PostgreSQL installed
- Maven installed

### 🔧 Backend Setup
```bash
cd backend
mvn clean install
mvn spring-boot:run
