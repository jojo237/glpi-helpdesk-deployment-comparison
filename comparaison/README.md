# GLPI Helpdesk Deployment – Docker vs aaPanel

## Objective
This project explores two different approaches to deploying an IT Helpdesk system using GLPI.

## Environments
- Ubuntu Server 24.04 (VM)
- Docker
- aaPanel (Nginx + PHP + MySQL)

---

## Docker Deployment 
- Successfully deployed GLPI using Docker
- Fast and reliable setup
- Minimal configuration required
- Fully functional environment

---

## aaPanel Deployment 
- Manual deployment using Nginx, PHP, and MySQL
- Faced multiple real-world challenges:
  - Nginx routing issues
  - PHP configuration constraints (open_basedir, extensions)
  - File permissions
  - Installation conflicts between /public and /install
- Installation completed via CLI
- Partial web functionality achieved

---

## Key Learnings
- Docker simplifies deployment and reduces configuration errors
- Traditional deployments require deeper system-level understanding
- Troubleshooting is a critical skill in real-world IT environments

---

## Skills Developed
- Linux Administration
- Docker & Containerization
- Nginx Configuration
- PHP Debugging
- MySQL Database Management
- IT Service Management (GLPI)

---

## Conclusion
While Docker provides a streamlined and efficient deployment method, traditional environments highlight the complexity and importance of system configuration and troubleshooting.

