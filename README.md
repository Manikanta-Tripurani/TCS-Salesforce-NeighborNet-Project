
<p align="center">
<img src="https://user-images.githubusercontent.com/1528574/210984841-209a6331-52fe-45a8-9ffd-51c6258f7009.png" width="120" />
</p>
<h1 align="center">NeighborNet: Barter & Skill-Share Network</h1>
<p align="center">
A Salesforce-powered platform designed to build stronger communities through a hyper-local, non-monetary exchange of skills and goods.
</p>
<p align="center">
<img src="https://img.shields.io/badge/status-in%20progress-blue?style=for-the-badge" alt="Status">
<img src="https://img.shields.io/badge/platform-Salesforce-00A1E0?style=for-the-badge" alt="Platform">
<img src="https://img.shields.io/badge/program-TCS%20Last%20Mile-orange?style=for-the-badge" alt="Program">
</p>
📖 Table of Contents
The Problem
The Solution
🚀 Core Features
🛠️ Technology Stack
🗂️ Data Model Overview
📈 Project Status
📂 Repository Structure
👨‍💻 Author
🎯 The Problem
In many local communities, residents are eager to help each other, but their efforts are often hindered by disorganized communication channels like chaotic social media groups. This leads to several critical issues:
Missed Connections: Valuable opportunities for collaboration are lost in the noise.
Inefficient Matching: There is no systematic way to connect members with specific needs to those with the right skills.
Lack of Recognition: There is no system to track successful exchanges or recognize the contributions of active community members.
✨ The Solution
NeighborNet is a centralized platform built on Salesforce that transforms this chaos into a structured, efficient, and engaging network. It provides a dedicated digital space for community members to list their skills, offer assistance, and request help within a trust-based, non-monetary framework, fostering a true sense of community.
🚀 Core Features
👤 Member & Skills Hub: A central directory of all community members and a catalog of their unique skills.
📢 Offer & Request Board: An intuitive interface for posting, browsing, and managing service Offers and Requests.
🤝 Exchange Lifecycle Management: End-to-end tracking of barter transactions—from initial proposal and acceptance to final completion.
🤖 Automated Notifications: Smart, real-time alerts notifying members of potential matches and status updates on their exchanges.
📊 Community Analytics: Rich dashboards and reports providing insights into the most in-demand skills, active members, and overall community engagement.
🛠️ Technology Stack
Category	Technology
Platform	Salesforce (Developer Edition)
Backend	Apex (Triggers, Classes), SOQL
Automation	Salesforce Flow
Frontend	Lightning Web Components (LWC), App Builder
Deployment	Change Sets, Salesforce CLI (SFDX)
🗂️ Data Model Overview
The application is architected around a custom data model designed to represent the core entities of the barter network.
code
Mermaid
erDiagram
    CONTACT ||--o{ MEMBER_SKILL : "has"
    SKILL ||--o{ MEMBER_SKILL : "is"
    CONTACT ||--o{ OFFER : "creates"
    CONTACT ||--o{ REQUEST : "creates"
    OFFER ||--o{ EXCHANGE : "fulfills"
    REQUEST ||--o{ EXCHANGE : "is fulfilled by"
📈 Project Status
This project is being developed in 10 distinct phases. The table below tracks the current progress.
Phase #	Phase Name	Status
01	Problem Understanding & Industry Analysis	✅ Complete
02	Org Setup & Configuration	✅ Complete
03	Data Modeling & Relationships	👉 In Progress
04	Process Automation (Admin)	⏳ Pending
05	Apex Programming (Developer)	⏳ Pending
06	User Interface Development	⏳ Pending
07	Integration & External Access	⏳ Pending
08	Data Management & Deployment	⏳ Pending
09	Reporting, Dashboards & Security Review	⏳ Pending
10	Final Presentation & Demo Day	⏳ Pending
📂 Repository Structure
code
Code
.
├── 📄 README.md
└── 📁 reports
    ├── 📄 Phase_1_Report.pdf
    └── 📄 Phase_2_Report.pdf
(The /force-app directory containing the Salesforce source code will be added in subsequent phases.)
👨‍💻 Author
Name: Manikanta.Tripurani
Program: TCS Last Mile SmartBridge
Batch: 4
