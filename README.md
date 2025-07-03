# Mostafa Tamer Mostafa Mohammed  

📍 **Cairo, Egypt** 📞 **+20 115 511 1844** 📧 **m.tamer.fcai@gmail.com** 🔗 [**LinkedIn**](https://www.linkedin.com/in/mostafa-tamer/) 🖥️ [**GitHub**](https://github.com/mostafa-tamer)

---

## Profile Summary
Graduated with **“Very Good”** from the Faculty of Computers and Artificial Intelligence, Cairo University (2020 – 2024), earning an **A+ on my graduation project** with strong foundation in computer science and software engineering.

Currently working as a **Java Software Engineer (Backend)** at **Pulse for Integrated Solutions GmbH** (Dec 2024 – Present), a company pioneering **mHealth, medical devices, and remote patient monitoring**, where technology meets life-saving moments.

---

## Work Experience

### Java Software Engineer (Backend) @ **Pulse for Integrated Solutions GmbH** _(Dec 2024 – Present)_

#### Achievements
<!-- 
* Designed a **new architecture for the communication protocol** between the server and the ECG device.

  * Applied **Single Responsibility Principle** and enforced **decoupling** by ensuring components rely on **contracts and abstractions**.
  * Achieved a design that is **open for extension, closed for modification**, supporting future scalability with minimal refactoring.
  * Promoted **reusability** and eliminated redundancy through clean modular structure.
  * Implemented an automatic **message parsing mechanism** by mapping message structures to POJOs and using **Java Reflection** to deserialize messages dynamically.

---
 -->
Designed and implemented the ECG Device Manager as a core component in a modular monolith architecture.
- Session Manager: 
  - Manages patient session lifecycle.
  - Controls start and end of sessions on the ECG device.

- Streaming Manager: 
  - Tracks lifecycle of real-time patient data streaming.
  - Controls start, stop, and restart of ECG data streams.
  - Ensures consistency between the current session and the streaming state.
  - Implements streaming delay detection mechanisms.

- SD Card Manager: 
  - Monitors SD card status on the device.
  - Handles SD card formatting.

---

Developed the Network Management Module:
- Notifies the frontend of the ping status of each ECG device and server-client latency.
- Introduced a dynamic timeout mechanism using a sliding window to adjust based on RTT trends.
- Built a fail-safe mechanism that suspends commands during severe network slowdown.

---

Introduced Resilience
- Introduced a task pipeline that guarantees proper execution and recovery at any failure point.
- Developed a message failure detection mechanism that identifies device error codes and applies corrective handling.

---

Bug Resolution
- Fixed a critical bug in patient session handling and streaming with a mechanism ensuring consistency and recovery on failure.

---

Built a virtual ECG that helps for running the server without a need of a physical device

Documented components with UML and technical diagrams — widely used and praised across the team.

Handled production issues by SSH-ing into Linux servers, checking Docker logs, and exporting logs for debugging.

Deployed the **RIMPulse System** into **Docker Containers**
<!-- 
- Built a **logger** for the system, in which each directory is a hub contains logger files each hub is controlled by logger manager, logger files can be (enabled, disabled, deleted)
- Developed **unit & integration tests** for the features I implemented.
 -->
---

#### Training
- **Risk Management**
- **Docker & Kubernetes: The Practical Guide [2025 Edition]** by **Maximilian Schwarzmüller**
- **Design Microservices Architecture with Patterns & Principles** by **Mehmet Ozkaya**

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

---

## Android Development Experience
- **egFWD Scholarship – Advanced Android Kotlin Development (Sep 2022 – Nov 2022) from Udacity**. [Certificate](https://github.com/mostafa-tamer/resume/blob/main/android-udacity-certificate.jpg)
- **1 year** of experience in Android development (XML & Jetpack Compose).
- Built **large-scale applications** (**assets manager, inventory manager, CMMS**) at [Manzoma Technology Solutions](https://www.manzoma.com/) (2023).
- Worked on **freelancing projects** as well as teaching Kotlin to CS Students (2023/2024).

---

## Soft Skills
- **Leadership, Time Management, Adaptability, Organizational, Problem Solving, Good Speaker**

<!-- Styling -->

<head>
  <style>
    /* h2 {
      color: #2f5496;
    } */]
  </style>
</head>
