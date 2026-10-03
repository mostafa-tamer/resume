# Mostafa Tamer Mostafa Mohammed

📍 **Cairo, Egypt** | 📞 **+20 115 511 1844** | 📧 **m.tamer.fcai@gmail.com** 🔗 **[LinkedIn](https://www.linkedin.com/in/mostafa-tamer/)** | 🖥️ **[GitHub](https://github.com/mostafa-tamer)**

---

## Professional Summary

Owned the end-to-end architecture of the critical ECG device-to-server communication system at Pulse, driving production stability that directly secured enterprise contract renewals in the UK and new regional expansions across major healthcare networks in Egypt and Saudi Arabia. **Focused on solving complex concurrency, real-time data ingestion, and network protocol failures in production environments.**, with a strong foundation in modular Clean Architecture and Microservices concepts.

---

## Work Experience

### Java Software Engineer (Backend) – **Pulse for Integrated Solutions GmbH** *(Dec 2024 – Present)*

* **High-Availability Streaming Pipelines:** Engineered an atomic, multi-stage request pipeline for critical ECG live-streaming operations, ensuring zero stream drops in hospital environments via stage-level retries; eliminated catastrophic stream failures and protected system runtime by auto-aborting orphaned pipelines upon sudden device disconnections.
* **Device Manager Architecture:** Architected and developed a centralized module to manage and control ECG medical devices, refactoring legacy business logic out of a monolithic communication class into a scalable, modular design.
* **Connection Concurrency Control:** Resolved a critical race condition where network instability caused duplicate active connections for a single device, implementing an eviction strategy that forcibly terminates stale connections to prevent state corruption and database inconsistencies.
* **Data Integrity & Crash Recovery:** Engineered a thread-safe Backup Manager to synchronize device SD card data to the server; built a robust **server-boot recovery routine** that scans backup files to locate the last valid frame and isolate physical corruption.
* **Critical Incident Resolution (EgyptAir POC):** Partnered with the mobile engineering team to diagnose and resolve a high-priority Bluetooth streaming defect caused by frame serial inconsistencies and corrupted delay calculations; stabilized the system within a critical window, successfully securing a major enterprise contract with EgyptAir.
* **Protocol Integration & Ownership:** Acted as the primary backend point of contact for the embedded team to co-design and implement the communication protocol for core device features; integrated multi-master "busy detection" and adaptive network timeouts to stabilize session lifecycles, real-time streaming, and device backups.
* **Hardware Abstraction & Safety:** Developed an **Adapter layer** to isolate core business logic from **different hardware versions** via a unified interface; utilized Java switch expressions to enforce compile-time safety across all hardware iterations.
* **Memory Optimization & Profiling:** Diagnosed and eliminated memory leaks by analyzing heap dumps and using IntelliJ Profiler, resolving root causes linked to static map retention and thread race conditions within executor service lifecycles.
* **Self-Healing & Observability Infrastructure:** Developed a dual-layer device health monitor that automatically triggers silent recovery mechanisms for production failures, while exposing real-time diagnostic flags during testing to instantly pinpoint hardware-side failures.
* **Integration Testing & Architecture:** Introduced the first automated integration testing framework for the system using Arquillian, overcoming physical hardware integration challenges to validate core session and real-time streaming states under complex network and device failure scenarios.

---

## Prior Android Experience

**Android Developer | Manzoma Technology Solutions** *(2023 – 2024)*

Developed and optimized large-scale enterprise applications (Assets Manager, Inventory Manager, and CMMS) utilizing Kotlin, XML, and Jetpack Compose.

---

## Technical Skills

* **Languages & Core Foundations:** Java, Kotlin, C#, Python, C/C++, SQL, Concurrency & Multithreading, OOP, Data Structures & Algorithms, SOLID Principles, Design Patterns.
* **Backend & IoT Integration:** Spring Boot, Jakarta EE, MQTT Protocols, Real-Time Data Ingestion, WebSockets (Architecture & Channel Isolation), REST APIs, Stream Processing, Dependency Injection, Maven, Gradle.
* **Frontend & Web Development:** HTML5, CSS3, JavaScript (ES6+), Tailwind CSS, Bootstrap, Angular (Familiar).
* **Databases & Performance Tuning:** MySQL, PostgreSQL, Query Optimization, Indexing Strategies (B-Tree, Covering, Composite), Stored Procedures & Triggers, Concurrency Control.
* **Architecture & Systems Design:** Microservices Architecture, Clean Architecture, Domain-Driven Design (DDD), Resilience Patterns, Service Decomposition, Eventual Consistency.
* **DevOps & Cloud Infrastructure:** Docker, Docker Compose, Kubernetes Fundamentals, AWS (EC2), Linux.
* **Tools & Testing:** Git/GitHub, IntelliJ Profiler, Arquillian Integration Testing, Postman.

---

## Side Projects

### **Large-Scale E-Commerce Database Design**

* Designed and populated a massive PostgreSQL database, engineering custom functions to efficiently handle millions of rows. Optimized complex SQL queries and index strategies, resulting in a **74.7% performance improvement**.
* [GitHub](https://github.com/mostafa-tamer/Large-Scale-E-Commerce-Database)

### **Real-Time Chat Application**

* Engineered a full-stack Android and Spring Boot chat system supporting real-time interactions via WebSockets and REST APIs. Integrated Firebase Cloud Messaging (FCM) for background push notifications and managed data models for user relationships and group chats.
* [Backend GitHub](https://github.com/mostafa-tamer/ChatWithMe-SpringBoot) | [Android GitHub](https://github.com/mostafa-tamer/ChatWithMe-Android)

---

## Education & Certifications

* **B.Sc. in Computer Science** – Cairo University, FCAI *(2024)*
* **Cumulative Grade:** Very Good.
* **Graduation Project:** "Task Together" (A+ Grade).
* **Advanced Android Kotlin Development** – egFWD Scholarship (Udacity, 2022).

