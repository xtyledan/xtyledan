# Tyler Daniels

**Software Engineer | Python & Java | Mechatronics and Industrial Automation**

Computer science graduate pursuing an **M.S. in Computer Science (Software Engineering)** at Southern New Hampshire University. I develop practical software and bring hands-on experience with industrial equipment, sensors, motors, robotics, and troubleshooting.

My focus is on **building reliable tools, testing behavior, and documenting engineering decisions**.

[**Portfolio**](https://xtyledan.github.io/) · [**LinkedIn**](https://www.linkedin.com/in/tyler-daniels2000/) · [**Repositories**](https://github.com/xtyledan?tab=repositories)

---

## Selected engineering projects

### [TkForge — Visual Tkinter GUI Builder](https://github.com/xtyledan/TkForge-Visual-Tkinter-GUI-Builder)

A Python desktop editor for building Tkinter interfaces visually. Place and configure widgets, preview layouts, save validated JSON projects, and export runnable Python layout code.

![TkForge desktop editor screenshot](https://raw.githubusercontent.com/xtyledan/TkForge-Visual-Tkinter-GUI-Builder/main/docs/screenshot.png)

**Engineering highlights:** widget dragging and redraw behavior, validated serialization, safe source generation, headless regression tests, and a documented tradeoff between absolute positioning and responsive layouts.

**Stack:** Python · Tkinter · JSON · unittest · GitHub Actions  
[Source and setup](https://github.com/xtyledan/TkForge-Visual-Tkinter-GUI-Builder#quick-start) · [Architecture and limitations](https://github.com/xtyledan/TkForge-Visual-Tkinter-GUI-Builder#design) · [CI](https://github.com/xtyledan/TkForge-Visual-Tkinter-GUI-Builder/actions)

### [Animal Rescue Explorer — Interactive Data Dashboard](https://github.com/xtyledan/Animal-Rescue-Explorer-Local-Data-Dashboard)

A local dashboard with searchable animal records, browser-side summaries, and a read-only HTTP API. Includes a synthetic CSV dataset so the demo runs without database credentials; MongoDB integration is optional.

![Animal Rescue Explorer dashboard screenshot](https://raw.githubusercontent.com/xtyledan/Animal-Rescue-Explorer-Local-Data-Dashboard/main/docs/screenshot.png)

**Engineering highlights:** API filtering, data-source separation, regression tests, mocked database behavior, and explicit documentation of local-only security and deployment limits.

**Stack:** Python · HTTP/JSON · HTML/CSS/JavaScript · unittest  
[Source and setup](https://github.com/xtyledan/Animal-Rescue-Explorer-Local-Data-Dashboard#quick-start) · [Architecture and limitations](https://github.com/xtyledan/Animal-Rescue-Explorer-Local-Data-Dashboard#how-it-works) · [CI](https://github.com/xtyledan/Animal-Rescue-Explorer-Local-Data-Dashboard/actions)

### [Java Service Testing — Appointments, Contacts & Tasks](https://github.com/xtyledan/Java-Service-Testing-Appointment-Contact-Task-Management)

Three Java domain services exercising input validation, state changes, and unit-testable business rules. Includes JUnit 5 tests and a reproducible Maven build.

**Engineering highlights:** defensive copying of mutable appointment dates, positive and negative test cases, clear boundaries between models and services, and automated build verification.

**Stack:** Java · JUnit 5 · Maven · GitHub Actions  
[Source and test instructions](https://github.com/xtyledan/Java-Service-Testing-Appointment-Contact-Task-Management#run-the-tests) · [Architecture](https://github.com/xtyledan/Java-Service-Testing-Appointment-Contact-Task-Management#architecture-overview) · [CI](https://github.com/xtyledan/Java-Service-Testing-Appointment-Contact-Task-Management/actions)

---

## Technical background

| Area | Experience |
| --- | --- |
| Software development | Python, Java, object-oriented programming, API development, debugging |
| Quality and workflow | Automated tests, Git/GitHub, pull requests, CI with GitHub Actions |
| Interfaces and data | Tkinter, HTML, CSS, JavaScript, JSON, SQL concepts, data visualization |
| Industrial systems | Mechatronics, robotics, motors, sensors, electrical systems, equipment troubleshooting |

**Education:** B.S. in Computer Science; M.S. in Computer Science, Software Engineering concentration (in progress).

**Additional work:** [Live software portfolio](https://xtyledan.github.io/) · [Portfolio source](https://github.com/xtyledan/xtyledan.github.io) · [Graduate coursework](https://github.com/xtyledan/ms-computer-science-coursework)

## How I work

I aim for small, reviewable changes supported by meaningful tests and accurate documentation. My repositories explain how to run the code, what has been verified, and what remains out of scope. Selected bug-fix examples include [restoring TkForge drag interactions](https://github.com/xtyledan/TkForge-Visual-Tkinter-GUI-Builder/pull/2), [protecting Java appointment dates](https://github.com/xtyledan/Java-Service-Testing-Appointment-Contact-Task-Management/pull/2), and [handling missing dashboard coordinates](https://github.com/xtyledan/Animal-Rescue-Explorer-Local-Data-Dashboard/pull/2).

*Project screenshots are captured from running applications. TkForge and Animal Rescue Explorer are locally run projects, not claimed production deployments.*
