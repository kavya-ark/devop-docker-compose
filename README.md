# devop-docker-compose
# Docker Jenkins CI/CD Pipeline (GitHub SSH Integration)

 Overview
This project demonstrates a real-world CI/CD pipeline using Jenkins inside a Docker container with GitHub SSH integration.  
It focuses on solving practical DevOps issues like container isolation, SSH authentication, and pipeline automation.

---

Tech Stack
- Jenkins
- Docker & Docker Compose
- GitHub (SSH Authentication)
- Linux (Ubuntu)
- Bash Shell

---
 Architecture
Developer → GitHub → Jenkins (Docker Container) → Build → Success

---

 Features
- Jenkins running inside Docker container
- GitHub integration using SSH keys
- Automated CI/CD pipeline
- Multi-environment SSH setup (Host vs Container)
- Real-world debugging of Docker and Jenkins issues

---

 Setup Process
1. Start Jenkins using Docker Compose
2. Configure Jenkins container
3. Generate SSH keys
4. Add GitHub public keys
5. Configure Jenkins pipeline
6. Trigger build from GitHub

---

Problems Solved (Real DevOps Issues)

- Fixed `Permission denied (publickey)` SSH error
- Resolved Docker container isolation issues
- Handled `chmod` and `chown` permission errors
- Debugged SSH using `ssh -vT git@github.com`
- Fixed Jenkins-GitHub authentication mismatch
- Managed multiple SSH keys for host and container
- Corrected Docker Compose volume misconfiguration
- Solved Jenkins pipeline checkout failures

---
Key Learnings
- Docker container isolation vs host system
- SSH authentication flow in CI/CD pipelines
- Jenkins credential management
- Linux permissions and user management
- Debugging real production-like issues

---

 Final Result
- Jenkins successfully connects to GitHub
- CI/CD pipeline runs successfully
- End-to-end automation achieved
