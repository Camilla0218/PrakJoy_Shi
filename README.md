🍺 Process Automation Project – Automated Beer Pouring Workflow
📌 Overview

This repository contains a process automation project developed in the context of Sustainable Process Automation at Technical University of Munich.

The project demonstrates how a digital workflow can orchestrate a physical task — automated beer pouring — using a robotic system (UR5) through an XML-based process model.

⚙️ Project Description

The core of this repository is an XML-based process model designed for execution in a workflow engine such as CPEE (Cloud Process Execution Engine).

The use case focuses on an automated beer pouring scenario, where the workflow coordinates interactions between software and a robotic arm.

The process includes:

Triggering a robotic program to pour beer
Waiting for task completion via synchronous endpoints
Managing process flow and execution order
Structuring the automation logic in a reproducible workflow

This project illustrates how digital process orchestration can control real-world physical actions.

🧩 Repository Structure
├── process_model.xml     # Main workflow definition (CPEE-compatible)
├── images/              # Supporting project visuals
│   ├── workflow.png
│   ├── system.png
│   └── demo.png
└── README.md
🖼️ Process Visualization

Below are some visual representations of the workflow and system setup:

🍺 Beer Pouring Workflow

🤖 System Architecture (CPEE + UR5 Integration)

🔍 Key Concepts

This project demonstrates several important concepts in modern automation systems:

Process Orchestration: Coordinating multi-step workflows
Cyber-Physical Systems: Linking software with robotic execution
Service Integration: Invoking UR5 robot programs via HTTP endpoints
Synchronous Execution Control: Ensuring correct task sequencing
🤖 System Integration

The workflow interacts with a UR5 robotic arm, which exposes execution endpoints for specific programs.

Example interaction:

HTTP request triggers a robot program (e.g., beer pouring)
/wait endpoint ensures the workflow proceeds only after completion

This setup enables:

Reliable execution control
Decoupling between workflow logic and physical actions
🚀 Technologies Used
XML (Process Modeling)
CPEE Workflow Engine
REST APIs (HTTP-based control)
UR5 Robotic System
🎯 Learning Outcomes

Through this project, the following skills were developed:

Designing executable workflows for real-world automation
Integrating software systems with robotic hardware
Understanding orchestration in distributed systems
Applying process automation concepts to physical use cases
📎 Notes

This repository serves as a conceptual and technical demonstration of integrating workflow engines with robotic systems for real-world automation tasks.

👤 Author

Tianyi Shi
M.Sc. Information Systems
Technical University of Munich
