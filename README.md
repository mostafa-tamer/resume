# Mostafa Tamer Mostafa Mohammed  

📍 **Cairo, Egypt** 📞 **+20 115 511 1844** 📧 **m.tamer.fcai@gmail.com** 🔗 [**LinkedIn**](https://www.linkedin.com/in/mostafa-tamer/) 🖥️ [**GitHub**](https://github.com/mostafa-tamer)

---

## Profile Summary
Backend Software Engineer with a strong academic background (Cairo University, Very Good, A+ project) and proven experience designing and developing resilient backend systems at Pulse for Integrated Solutions GmbH.

---

## Work Experience

### Java Software Engineer (Backend) @ **Pulse for Integrated Solutions GmbH** _(Dec 2024 – Present)_

#### Role Overview
Develop and maintain the backend that communicates with ECG medical devices using a custom **binary protocol (Pulse Exchange - PX)**.  
Responsible for implementing the server logic that manages device sessions, data streaming, and resilience mechanisms using Java & Jakarta EE for fault-tolerant operation.
Also handle **system documentation**, **architecture diagrams**, and **refactoring legacy modules** to ensure clean, maintainable design.

---

#### Achievements

**Device Manager**  
The Device Manager is the core component responsible for maintaining the state and behavior of all connected ECG devices. It interprets incoming events and executes actions such as assign, session, streaming, and SD card operations based on the current state.

It ensures that each action happens in the right order and under the right conditions.  
For example, it won’t start a streaming session before confirming that a device is assigned.  
It also detects and handles failures gracefully — whether it’s a command timing out, a network delay, or a device responding incorrectly.  
When something goes wrong, it retries, or triggers recovery flows to keep the system stable.

The Device Manager integrates with the **task pipeline** I developed, which ensures atomic execution of related operations and prevents partial failures.  
It also performs **device health checks**, such as verifying session and stream readiness.  

---

**SD Card Management**  
Handles everything related to the SD card’s health and lifecycle on ECG devices.  
- Continuously monitors SD card capacity, usage thresholds, and operational status.  
- Supports on-demand **formatting** operations while ensuring safe execution and no interference with ongoing sessions.  

---

**Backup Management**  
Implements an intelligent backup system that ensures no data loss even when devices go offline.  
- When a patient records sessions while the device is offline, data is temporarily stored on the SD card.  
- Once the device reconnects, the server requests metadata of recorded sessions so that users can selectively upload them.  
- Supports **partial uploads** (specific parts of sessions) depending on the session type and data relevance.  
- Handles errors during upload — like timeouts, mid-transfer interruptions, or device disconnections — and automatically resumes from where it stopped.  
- If a session repeatedly fails, the system skips it and continues with the next available one to ensure progress and avoid blocking the queue.
This mechanism ensures continuous data integrity and user control even under unstable connectivity conditions.

This component became a foundation for several other modules, improving coordination and system reliability overall.

---

**Network Management**  
- Developed ping & latency tracking and adaptive timeout logic.  
- Added fail-safe handling during severe network slowdowns.  

---

**Device State**  
Built a centralized device state system that keeps track of all connected ECG devices in real time.  
Each device’s state is maintained in a centralized in-memory structure representing its current status across multiple dimensions:  
**assign**, **session**, **streaming**, **battery**, **SD card**, **backup**, **OTA**, and **access point**.  

The server continuously updates these states using messages received through the **Pulse Exchange (PX)** binary protocol.  
This allows the backend to instantly reflect any change in device behavior — such as starting or ending a session, beginning an OTA update, or switching between Bluetooth and server connections.

The device state acts as the single source of truth for all modules in the system, enabling consistent decision-making and reliable orchestration of commands across the platform.

---

**System Improvements**  
- Refactored the WebSocket communication layer by introducing a new **UI Socket** between the server and frontend.  
  Previously, all messages — including non-alarm data — were sent through the **Alarm Socket**, which increased load and latency.  
  The new separation reduced traffic on the alarm channel and significantly improved the delivery speed and reliability of real-time alerts.
- Built a **Virtual ECG** simulator identical in behavior to physical devices, enabling stress testing and rapid feature validation without requiring real hardware.
- Diagnosed and fixed **memory leaks** in long-running services by profiling heap usage and tracing leaked objects that were periodically crashing the server.

These improvements enhanced real-time responsiveness, observability, and overall system stability.

---

**Professional Development**  
Continuously expanding technical expertise through advanced backend, architecture, and DevOps learning paths.

- **Risk Management**
- **Docker & Kubernetes: The Practical Guide [2025 Edition]** by **Maximilian Schwarzmüller**
- **Design Microservices Architecture with Patterns & Principles** by **Mehmet Ozkaya**

---

**Tech Stack**  
Java · Jakarta EE · Docker · REST APIs · WebSockets · Linux · MySQL · Gradle · Git · (Clean Architecture & DDD) · UML · Microservices Concepts
Well-versed in designing resilient backend systems and integrating hardware–software communication through custom protocols.

<!-- 
* Designed a **new architecture for the communication protocol** between the server and the ECG device.

  * Applied **Single Responsibility Principle** and enforced **decoupling** by ensuring components rely on **contracts and abstractions**.
  * Achieved a design that is **open for extension, closed for modification**, supporting future scalability with minimal refactoring.
  * Promoted **reusability** and eliminated redundancy through clean modular structure.
  * Implemented an automatic **message parsing mechanism** by mapping message structures to POJOs and using **Java Reflection** to deserialize messages dynamically.

---
 -->

---

## Graduation Project  
**Task Together** – A+ Grade  
A project designed to **enhance group collaboration** by simplifying **project organization and communication** for academic, professional, and personal use.  
- **Role:** Android Developer  
- [GitHub](https://github.com/mostafa-tamer/Task-Together) | [Gallery](https://www.behance.net/gallery/204098119/Task-Together)

---

## Internships

### ITI Summer Internship ASP .Net MVC _(Jul 2023 - Aug 2023)_
- Built an **Online Market**.
- Implemented user, customer, cart, and stock features.
- Technologies: **MS SQL Server, C#, LINQ, Entity Framework, Razor Syntax, MVC, HTML, CSS, JavaScript**.
- [Certificate](https://drive.google.com/file/d/1MG5hhQEiVRih8ki4F5eFDiyRq0KxrXcA/view)

---

## Side Projects

### **Chat App** _(May 2024 - July 2024)_
- Android-Spring Boot **chat app** with User Management, Friendship, Chats, and Groups.
- Integrates **REST API** and **Web Sockets** for real-time interactions.
- Uses **FCM** for background push notifications.
- [Backend GitHub](https://github.com/mostafa-tamer/ChatWithMe-SpringBoot) | [Android GitHub](https://github.com/mostafa-tamer/ChatWithMe-Android) | [Gallery](https://www.behance.net/gallery/202302419/Chat-Applicatoin)

### **Vacation Tracking System Analysis** _(Oct 2024)_
- Extracted **functional and non-functional requirements**.
- Created **flow diagrams, state machine, sequence diagrams** and Designed **database tables**.
- [GitHub](https://github.com/mostafa-tamer/Vacation-Tracking-System)

### **Large-Scale E-Commerce Database Design** _(Nov 2024)_
- Designed and populated a **large-scale e-commerce database** using PostgreSQL.
- Created database functions to insert **millions of rows efficiently**.
- Wrote optimized SQL queries, improving performance by **74.7%**.
- [GitHub](https://github.com/mostafa-tamer/Large-Scale-E-Commerce-Database)

---

## Technical Proficiencies

### **Foundational Expertise**
- OOP, Data Structures & Algorithms, UML, SOLID Principles, Design Patterns, Operating Systems, Concurrency & Multithreading
- Relational Databases, Problem Solving, Git & GitHub, Linux, Docker, Jenkins
- Comfortable with **C/C++, Java, Kotlin, C#**

### **Backend**
- **Java, Spring Boot, Jakarta EE, Maven & Gradle**
- REST API, Web Socket
- Dependency Injection, Software Architecture (e.g., MVC, DDD)
- ORM, JDBC, JPA, Hibernate, HQL, Jooq, Liquibase
- Testing, Exception Handling, Security (e.g., Basic, JWT, OAuth2)

### **Database**
- Integrity, Security, Triggers, Indexes (hash, b-tree, covering, composite, clustered, non-clustered)
- Normalization & Denormalization, Materialized Views, Views, CTEs, Stored Procedures, Functions
- Explain Analyzer, Query Optimization, Concurrency, Database Maintenance, Database Internals
- **MySQL, PostgreSQL, SQL Server**

### **Docker & Kubernetes**
- Images, Containers, Volumes, Networking, Docker Compose
- Kubectl, Kubernetes Objects (Cluster, Master & Worker Nodes, Deployments, Services, Pods), Volumes (emptyDir, hostPath, persistent volumes), Networking

### **Problem Solving**
- Sorting, Greedy, Binary Search, Two Pointers, Sliding Window
- Recursion, Backtracking, Graphs, Trees

### **Miscellaneous**
- Data Analytics, Computer Graphics, Parallel Processing, Machine Learning, Genetic Programming, Natural Language Processing (NLP), Compilers, Data Compression
- Used **Cursor** efficiently for development and debugging, which significantly accelerated implementation and issue resolution. Focused on deep understanding over copy-paste to maintain strong technical reasoning and clean code.

---

## Android Development Experience
- **egFWD Scholarship – Advanced Android Kotlin Development (Sep 2022 – Nov 2022) from Udacity**. [Certificate](https://github.com/mostafa-tamer/resume/blob/main/android-udacity-certificate.jpg)
- **1 year** of experience in Android development (XML & Jetpack Compose).
- Built **large-scale applications** (**assets manager, inventory manager, CMMS**) at [Manzoma Technology Solutions](https://www.manzoma.com/) (2023).
- Worked on **freelancing projects** as well as teaching Kotlin to CS Students (2023/2024).

---

## Soft Skills
Leadership, Time Management, Adaptability, Organization, Problem Solving, and Communication Skills

<!-- Styling -->

<head>
  <style>
    /* h2 {
      color: #2f5496;
    } */]
  </style>
</head>


<!-- TODO -->
<!-- server device cache -->
<!-- soft skills ->  -->
<!-- ai usage in code, writing documents, extract vulnerabilities -->
