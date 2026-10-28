# Hi there, I'm Angelo 👋

🎓 **M.Sc. Student in Computer Science & Engineering (Cybersecurity)** @ *Politecnico di Milano*  
🌍 **Exchange Student (ITEE Faculty)** @ *University of Oulu, Finland*  
🎓 **B.Sc. in Computer Engineering** @ *Politecnico di Milano*

---

## 🛠️ Technical Projects

### 🛡️ [SDMO — Legacy System Modernization for Post-Quantum Cryptography](https://github.com/AloRno/SDMO)
*Course Project for Software Development, Maintenance & Operations — **University of Oulu** (2026)*

Modernization of a legacy edge-cloud IoT telemetry system to withstand quantum computing threats through **AI-assisted software engineering** and critical evaluation of LLM-generated artifacts.

* **Architecture & PQC Integration:** Conceived the baseline edge-cloud system and migrated transport security from classical Diffie-Hellman to a **Hybrid DH + ML-KEM-768** key encapsulation mechanism with **AES-256-GCM**, preserving backward compatibility with legacy AES-CBC edge sensors.
* **AI Evaluation & Technical Documentation:** Treated LLM outputs as untrusted sources—critically reviewing, testing, and adapting generated code and operational configurations (`Docker Compose`, `Prometheus`, `GitHub Actions CI/CD`, `Pytest`). Authored comprehensive **Architectural & Technical Documentation** and a formal **Cryptography & Mathematics Report** detailing migration strategies, accepted/rejected AI artifacts, and residual security risks.
* **Tech:** `Python` `Post-Quantum Cryptography (ML-KEM-768)` `Docker` `Pytest` `CI/CD` `Technical Documentation`

---

### 🚲 [BBP — Best Bike Paths](https://github.com/ilevinci/RubinoUvinsiVinciguerra)
*Final Project for Software Engineering 2 — **Politecnico di Milano** (2026)*

Complete requirements engineering and architectural design project for a sustainable urban mobility platform supporting safe bike-route planning, obstacle reporting, and crowd-sourced road quality ratings (developed in a 3-person team with [Ilenia Vinciguerra](https://github.com/ilevinci) and [Eleonora Uvinsi](https://github.com/eleonorauvii)).

* **My Role:** Architect & Formal Modeler.
* **Contribution:** Co-authored the **Requirements Analysis & Specification Document (RASD)** and **Design Document (DD)**; led the formal verification and modeling phase in **Alloy 6** to prove system constraints and state invariants, co-designed the system deployment architecture and core design patterns (**UML**), and defined the implementation and integration testing strategy.
* **Tech:** `Alloy 6` `UML` `PlantUML` `Draw.io` `Software Architecture` `LaTeX` `Git`

---

### 🚀 Galaxy Trucker — Distributed Multiplayer Board Game Engine 🔒
*Final Project ("Prova Finale") for Software Engineering — **Politecnico di Milano** (2025)*  
*(🔒 Private repository — university policy restricts publishing the official assignment specification and bundled third-party rulebook; access available upon request).*

Full client/server implementation of the *Galaxy Trucker* board game featuring a TUI, JavaFX GUI, concurrent **Java RMI & TCP Socket** networking, and game-state persistence, developed in a 4-person team following strict **Model-View-Controller (MVC)** design patterns.

* **My Role:** Test Engineer & GUI Developer.
* **Contribution:** Authored a core section of the project's **JUnit** test suite covering the shipboard tile model, danger-penalty resolution, and controller state transitions—surfacing edge cases in the adventure-card engine prior to integration. Built major views of the **JavaFX** client (ship building, fixing, flight phase, and planet exploration).
* **Tech:** `Java` `JavaFX` `Java RMI` `TCP Sockets` `MVC` `JUnit` `UML` `Git`

---

### 🍰 [Industrial Bakery Simulation — API Project](https://github.com/AloRno/API_Project)
*Final Project ("Prova Finale") for Algorithms and Principles of Computer Science — **Politecnico di Milano** (2024)*

High-performance in-memory simulation built from scratch in **C11** with zero external dependencies, focused on strict time and space complexity optimization. It models an industrial production line handling recipe management, ingredient batch expiration dates, order queuing, and courier loading schedules.

* **⚡ Performance & Data Structures:** Implemented custom **Hash Maps** (with polynomial rolling hash and doubly linked lists) and expiration-ordered **Priority Queues** to achieve optimal **$O(n)$** time complexity across critical operations, paired with a custom byte-stream parser.
* **🧠 Memory Management:** Manual memory allocation (`malloc`/`free`) profiled with **Valgrind** to prevent memory fragmentation and ensure zero memory leaks.
* **Tech:** `C11` `Algorithms & Data Structures` `Manual Memory Management` `Valgrind` `GDB`

---

### 🔌 [Differential Filter — Memory-Mapped Hardware Module](https://github.com/AloRno/Differential-Filter-VHDL)
*Final Project ("Prova Finale") for Logic Networks (Reti Logiche) — **Politecnico di Milano** (2024)*

Synchronous memory-mapped **Finite-State Machine with Datapath (FSMD)** hardware component in **VHDL** that reads signed 8-bit sample streams from RAM, applies an order-3 or order-5 differential filter, and writes saturated results back to memory (developed in pairs with [Mirco Poma](https://github.com/MircoPoma)).

* **My Role:** Co-Designer & Co-Developer.
* **Contribution:** Designed the 11-state Moore FSM and datapath architecture, implemented divider-free fixed-point normalization ($1/12$ and $1/60$) using shift-add arithmetic with sign-aware rounding correction and saturation clamping, and validated the design in simulation against the course testbench.
* **Tech:** `VHDL` `Xilinx Vivado` `Digital Logic` `FSMD Design`
