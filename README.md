<h1>🍺 Process Automation Project – Automated Beer Pouring Workflow</h1>

<h2>📌 Overview</h2>
<p>
This repository contains a process automation project developed in the context of Sustainable Process Automation at Technical University of Munich.
</p>
<p>
The project demonstrates how a digital workflow can orchestrate a physical task — automated beer pouring — using a robotic system (UR5) through an XML-based process model.
</p>

<h2>⚙️ Project Description</h2>
<p>
The core of this repository is an XML-based process model designed for execution in a workflow engine such as CPEE (Cloud Process Execution Engine).
</p>
<p>
The use case focuses on an automated beer pouring scenario, where the workflow coordinates interactions between software and a robotic arm.
</p>

<p>The process includes:</p>
<ul>
  <li>Triggering a robotic program to pour beer</li>
  <li>Waiting for task completion via synchronous endpoints</li>
  <li>Managing process flow and execution order</li>
  <li>Structuring the automation logic in a reproducible workflow</li>
</ul>

<p>
This project illustrates how digital process orchestration can control real-world physical actions.
</p>

<h2>🧩 Repository Structure</h2>
<pre>
├── process_model.xml
├── images/
│   └── midtermSnapshot.jpeg
│   └── finalSnapshot.jpeg(tbd)
└── README.md
</pre>

<h2>🔍 Key Concepts</h2>
<ul>
  <li><strong>Process Orchestration:</strong> Coordinating multi-step workflows</li>
  <li><strong>Service Integration:</strong> Invoking UR5 robot programs via HTTP endpoints</li>
  <li><strong>Synchronous Execution Control:</strong> Ensuring correct task sequencing</li>
</ul>

<h3>🤖 System Integration</h3>
<p>
The workflow interacts with a UR5 robotic arm, which exposes execution endpoints for specific programs.
</p>

<p>Example interaction:</p>
<ul>
  <li>HTTP request triggers a robot program (e.g., beer pouring)</li>
  <li><code>/wait</code> endpoint ensures the workflow proceeds only after completion</li>
</ul>

<p>This setup enables:</p>
<ul>
  <li>Reliable execution control</li>
  <li>Decoupling between workflow logic and physical actions</li>
</ul>

<h2>🚀 Technologies Used</h2>
<ul>
  <li>XML (Process Modeling)</li>
  <li>CPEE Workflow Engine</li>
  <li>REST APIs (HTTP-based control)</li>
  <li>UR5 Robotic System</li>
</ul>

<h2>🎯 Learning Outcomes</h2>
<ul>
  <li>Designing executable workflows for real-world automation</li>
  <li>Integrating software systems with robotic hardware</li>
  <li>Understanding orchestration in distributed systems</li>
  <li>Applying process automation concepts to physical use cases</li>
</ul>

<h2>📎 Notes</h2>
<p>
This repository serves as a conceptual and technical demonstration of integrating workflow engines with robotic systems for real-world automation tasks.
</p>

<h2>👤 Author</h2>
<p>
Tianyi Shi<br>
M.Sc. Information Systems<br>
Technical University of Munich
</p>
