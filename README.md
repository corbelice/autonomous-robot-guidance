# Autonomous Robot Guidance — MicroPython

**Technische Universität Dresden | 2025–2026**  
**Academic Robotics Project | Team Project**

## 1. Project Overview

During my Erasmus year at Technische Universität Dresden, I participated in a robotics project involving the development of autonomous behavior for a **Pololu 3pi+ 2040 robot**, programmed in MicroPython.

The project explored how a mobile robot can execute autonomous missions by combining navigation, control and high-level decision-making.

One of the main applications was autonomous parking, requiring the robot to coordinate different operating phases while responding to information from its environment.

I was responsible for the **Guidance module**, which played a central role in organizing the robot's missions and coordinating its behavior.

This repository documents my contribution, the engineering challenges involved and the skills developed throughout the project.

---

## 2. Project Objectives

The project involved several technical objectives:

- Developing autonomous behavior for a mobile robot.
- Organizing robotic software into interacting modules.
- Coordinating mission execution through high-level logic.
- Managing transitions between different operating phases.
- Supporting autonomous parking and departure maneuvers.
- Integrating software components within an embedded environment.

These objectives required combining software engineering principles with concepts from robotics and control engineering.

---

## 3. System Architecture

The robotic software was organized around different functional responsibilities.

### Guidance

Responsible for high-level decision-making and mission coordination.

The Guidance module determines which operation the robot should perform according to its current mission and available information.

### Navigation

Responsible for navigation-related information used during autonomous operation.

### Control

Responsible for translating movement objectives into commands suitable for controlling the robot.

### Interaction Between Modules

A key aspect of the project was ensuring that the different modules could interact coherently.

The Guidance module acted as a coordination layer between mission objectives and lower-level robotic functions.

This modular approach helped separate high-level behavior from navigation and motion control.

---

## 4. My Contribution — Guidance Module

My main responsibility was the design and development of the robot's Guidance logic in MicroPython.

### 4.1 Finite State Machine

One of the central aspects of my work was the use of a **Finite State Machine (FSM)** to organize the robot's behavior.

This approach represents complex behavior as a set of operating states, with transitions depending on events, conditions or mission progress.

The state-machine architecture helped structure the robot's different activities and maintain coherent behavior throughout a mission.

This work involved:

- Identifying operational phases.
- Organizing the overall mission logic.
- Managing transitions between operating states.
- Coordinating the execution of different behaviors.
- Considering how the robot should react to changes in its operating conditions.

### 4.2 Mission Coordination

The Guidance module was responsible for coordinating the execution of autonomous missions.

My work involved defining how high-level decisions interacted with other software components.

Particular attention was given to maintaining consistency between the robot's current mission, its operating state and the actions requested from other modules.

### 4.3 Autonomous Parking

Autonomous parking was one of the main applications explored in the project.

From a guidance perspective, this required organizing a sequence of operations rather than treating the parking maneuver as a single action.

The work involved coordinating the different phases associated with approaching, entering and leaving a parking position.

### 4.4 Software Integration

The project required integrating independently developed software components into a common robotic architecture.

This involved working with interfaces between modules, discussing expected behavior and ensuring consistency across the different parts of the system.

It provided practical experience in collaborative embedded software development.

---

## 5. Engineering Challenges

### Managing Complex Behavior

Autonomous missions require several actions to be coordinated in the correct order.

Using a finite state machine provided a structured way to represent this behavior.

### Coordinating Software Modules

Separating Guidance, Navigation and Control introduced integration challenges.

Each module had its own responsibilities, but the overall system needed to behave consistently.

### Embedded Programming

Developing software for a physical robot requires considering the interaction between program logic and the behavior of the real system.

### Team Collaboration

Working on a shared robotics project required communication between team members, agreement on software interfaces and coordination during integration.

---

## 6. Technologies and Skills

### Hardware
- Pololu 3pi+ 2040 autonomous robot

### Programming
- MicroPython
- Modular software design
- Finite State Machines

### Engineering Concepts
- Autonomous robotics
- High-level guidance
- Mission planning and coordination
- Embedded software architecture
- Navigation and control interfaces
- System integration

### Professional Skills
- Collaborative software development
- Technical communication
- Problem decomposition
- Interface coordination
- Working in an international academic environment

---

## 7. Academic Context

| Information | Details |
|-------------|---------|
| University | Technische Universität Dresden |
| Academic year | 2025–2026 |
| Project | AMT Robotics Project |
| Project type | Academic team project |
| Programming language | MicroPython |
| Hardware | Pololu 3pi+ 2040 |
| My responsibility | Guidance module |

---

## 8. Source Code Availability

The original source code and detailed implementation are not publicly available.

This project was developed as part of university coursework, and the assignment is reused for educational purposes.

To preserve the academic integrity of the laboratory, this repository does not include:

- Source code implementing the assignment solutions.
- Detailed state-transition conditions.
- Parking algorithms or implementation parameters.
- Internal interfaces or other solution-specific material.

The purpose of this repository is to present the project context, my engineering responsibilities and the technical concepts explored during development.

---

## 9. What I Learned

This project strengthened my interest in **control engineering, robotics and embedded systems**.

It gave me practical experience in organizing autonomous behavior through finite state machines and understanding the importance of software architecture in robotic applications.

Working on the Guidance module also helped me develop a better understanding of the relationship between high-level decision-making, navigation and control.

Finally, working in an international engineering team allowed me to improve my technical communication and collaborative development skills.
