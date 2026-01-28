# GTPL_UG – UG Management System

## 📌 Overview

**GTPL_UG** is a **UG (Underground) Work Management System** designed to manage and track work assignments between an organization (Admin / UG Management) and Vendors.

The system enables:
- Admins to assign work to vendors
- Vendors to update work progress
- Vendors to upload photos as proof of work
- Vendors to request new work assignments
- Secure storage of data using a cloud database

This project is under **active development** and is being built step-by-step with a focus on **clean architecture, scalability, and security**.

---

## 🎯 Project Goals

- Centralized UG work management
- Transparent communication between Admin and Vendors
- Digital proof of work via photo uploads
- Secure, cloud-based data storage
- Role-based access control
- Scalable backend architecture

---

## 👥 User Roles

### 🔑 Admin (UG Management)
- Create and manage vendors
- Assign work to vendors
- View vendor progress
- Review uploaded work proof (photos)
- Approve or reject work requests

### 🧑‍🔧 Vendor
- View assigned work
- Update work status and details
- Upload photos as proof of work
- Request new work assignments
- Communicate work updates to Admin

---

## 🛠️ Technology Stack

### Backend
- **Java**
- **Gradle** (Groovy DSL)
- **Spring Boot** (planned)
- RESTful API architecture

### Database (Planned)
- **Cloud Database** (Firebase / Supabase – final decision pending)
- Secure data storage
- Cloud file storage for images

### Version Control
- **Git**
- **GitHub**

---

## 📂 Project Structure (Current)

GTPL_UG/
├── app/
│ ├── src/
│ │ ├── main/java/
│ │ └── test/java/
│ └── build.gradle
│
├── gradle/
│ └── wrapper/
│
├── gradlew
├── gradlew.bat
├── settings.gradle
├── gradle.properties
└── README.md