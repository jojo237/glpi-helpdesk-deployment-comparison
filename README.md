# GLPI Helpdesk – IT Ticketing System Deployment (Docker & aaPanel)

## Project Overview
This project focuses on deploying and evaluating an IT ticketing system (GLPI) using two different approaches:

- Docker-based deployment (Primary)
- aaPanel-based deployment (Secondary – upcoming)

The objective is to simulate a real IT support environment and strengthen hands-on skills in ITSM, system administration, and containerized applications.

---

## Current Status
✅ Docker Deployment Completed  
🔄 aaPanel Deployment – In Progress  

---

## Technical Environment
- Ubuntu Server (Virtual Machine)
- Docker & Docker Compose
- GLPI (ITSM Tool)
- Git & GitHub

---

## Docker Deployment – Key Implementations
- Installation and configuration of Docker on Linux VM
- GLPI container deployment using Docker Compose
- Persistent volumes configuration (data durability)
- Restart policy configuration (service resilience)
- Removal of installation directory for security hardening
- Admin password change and access control setup
- User and role creation (User / Technician)
- Ticket lifecycle testing (creation, assignment, resolution)
- System reboot testing to validate container auto-restart

---

## Project Structure
├── docker-version/ # Docker deployment files
├── aapanel-version/ # aaPanel deployment (Part 2)
├── comparaison/ # Architecture & analysis
└── README.md

---

## Skills Demonstrated
- IT Service Management (ITSM)
- Docker Containerization
- Linux System Administration
- Technical Troubleshooting
- Role-Based Access Control (RBAC)
- Documentation & Project Structuring

---

## Next Phase
- Deployment of GLPI using aaPanel
- Comparative analysis: Docker vs Web Hosting Panel
- Documentation of architecture, security, and maintenance differences

---

## Hiw to run the project
1. Install Docker & Docker compose
2. Clone the repository
3. Run: 
    docker-compose up -d
4. Access GLPI browser

---

## Author
Hands-on IT lab project focused on real-world IT support and infrastructure practices.

