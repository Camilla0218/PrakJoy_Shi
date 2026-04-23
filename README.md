<h1 align="center">🍺 Process Automation Project – Automated Beer Pouring Workflow</h1>

<h2>📌 Overview</h2>
<p>
This repository contains the full implementation of my project for the course <strong>Sustainable Process Automation</strong> at the Technical University of Munich.
</p>

<p>
The project demonstrates how a digital workflow can orchestrate a real-world physical task — <strong>automated beer pouring</strong> — by integrating a workflow engine (CPEE), a UR5 robotic system, and custom-built hardware components.
</p>

<p>
All relevant artifacts of the project are included in this repository, including process models, robot programs, and hardware designs.
</p>

<hr>

<h2>⚙️ Project Objective</h2>
<p>
The goal of this project was to design and implement a <strong>cyber-physical system</strong> where a workflow engine coordinates and controls physical actions performed by a robotic arm.
</p>

<p>
The system focuses on automating the beer pouring process while ensuring:
</p>

<ul>
  <li>Reliable orchestration of tasks</li>
  <li>Synchronization between software and hardware</li>
  <li>Clear separation between process logic and execution layer</li>
</ul>

<hr>

<h2>🏗️ System Architecture</h2>
<p>
The system consists of three main components:
</p>

<ul>
  <li><strong>CPEE Workflow Engine:</strong> Controls the process logic and execution flow</li>
  <li><strong>UR5 Robot:</strong> Executes physical actions such as pouring beer</li>
  <li><strong>Hardware Components:</strong> Custom-designed gripper and attachments</li>
</ul>

<p>
Communication is achieved via HTTP-based service calls, allowing the workflow engine to trigger robot programs and wait for their completion.
</p>

<hr>

<h2>🔄 Process Workflow</h2>
<p>
The workflow is defined in an XML-based process model executed by CPEE.
</p>

<p>The process includes:</p>
<ul>
  <li>Triggering robot programs for beer pouring</li>
  <li>Using synchronous endpoints (<code>/wait</code>) to ensure correct execution order</li>
  <li>Coordinating sequential and logical process steps</li>
</ul>

<p>
This demonstrates how workflow orchestration can be used to control real-world processes in a structured and reproducible way.
</p>

<hr>

<h2>🤖 Robot Integration</h2>
<p>
The UR5 robotic arm is integrated via HTTP endpoints that expose executable programs.
</p>

<ul>
  <li>Robot programs are stored as <code>.urp</code> files</li>
  <li>Each program represents a specific action (e.g., pouring, positioning)</li>
  <li>The workflow triggers these programs remotely</li>
  <li>The <code>/wait</code> endpoint ensures synchronous execution</li>
</ul>

<p>
This approach decouples the workflow logic from the physical execution layer.
</p>

<hr>

<h2>🧩 Hardware Design (3D Models)</h2>
<p>
As part of the project, custom hardware components were designed to support the robotic task.
</p>

<ul>
  <li>Gripper attachments for holding bottles</li>
  <li>Supporting components for stable manipulation</li>
  <li>Designed as 3D models for prototyping and fabrication</li>
</ul>

<p>
These components enable the robot to interact reliably with real-world objects.
</p>

<hr>

<h2>🧩 Repository Structure</h2>
<pre>
├── JoyPrak_Shi.xml              # CPEE process model
├── robot program/              # UR5 robot programs (.urp)
├── images and videos/          # Demonstration visuals
├── 3d models/                  # Custom hardware designs
└── README.md
</pre>

<hr>

<h2>🚀 Technologies Used</h2>
<ul>
  <li>XML (Process Modeling)</li>
  <li>CPEE Workflow Engine</li>
  <li>REST APIs (HTTP-based communication)</li>
  <li>UR5 Robotic System</li>
  <li>3D Modeling Tools (for hardware design)</li>
</ul>

<hr>

<h2>🎯 What I Implemented</h2>
<ul>
  <li>Designed and implemented the complete CPEE workflow model</li>
  <li>Integrated UR5 robot programs via HTTP endpoints</li>
  <li>Implemented synchronous execution using <code>/wait</code></li>
  <li>Structured the automation logic for reproducibility</li>
  <li>Designed custom 3D components for robotic interaction</li>
  <li>Organized all project artifacts into a unified repository</li>
</ul>

<hr>

<h2>📎 Notes</h2>
<p>
This project demonstrates the integration of software workflows and physical systems, highlighting the role of process automation in cyber-physical environments.
</p>

<p>
The repository serves as both a technical implementation and a project documentation.
</p>

<hr>

<h2>👤 Author</h2>
<p>
Tianyi Shi<br>
M.Sc. Information Systems<br>
Technical University of Munich
</p>
