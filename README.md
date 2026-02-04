# JollyLab Infrastructure Platform

> Production-grade homelab infrastructure demonstrating DevOps and Infrastructure-as-Code practices

[![Status](https://img.shields.io/badge/status-in%20development-yellow)](https://github.com/thejollydev/jolly-lab-infrastructure)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## 🎯 Project Overview

A comprehensive homelab infrastructure project showcasing modern DevOps practices, infrastructure automation, and cloud-native technologies. This project serves as both a learning environment and a demonstration of production-ready infrastructure management.

**🚧 Currently in active development - check back soon!**

## 🏗️ Architecture

**Hardware:**
- Proxmox VE virtualization platform
- AMD Ryzen 7 5800X (8c/16t)
- 32GB RAM
- ZFS storage with redundancy
- GPU passthrough for LLM hosting (AMD RX 7900 XT 20GB)

**Core Services:**
- Reverse Proxy (Traefik)
- Monitoring (Prometheus + Grafana)
- Version Control (Gitea)
- Documentation (Wiki.js)
- Container Registry (Harbor)
- LLM Inference Server (Ollama)

## 🛠️ Tech Stack

- **Infrastructure as Code:** Terraform, Ansible
- **Containerization:** Docker, Docker Compose, Kubernetes (K3s)
- **Monitoring:** Prometheus, Grafana, Alertmanager
- **CI/CD:** GitHub Actions
- **Cloud:** Google Cloud Platform (backup & disaster recovery)
- **Operating Systems:** Proxmox VE, Ubuntu Server, Arch Linux

## 📋 Features

- [x] Hardware procurement and setup
- [ ] Proxmox installation and configuration
- [ ] Infrastructure-as-Code with Terraform
- [ ] Configuration management with Ansible
- [ ] Docker Compose service deployment
- [ ] Monitoring and alerting stack
- [ ] Automated backups to GCP
- [ ] CI/CD pipeline
- [ ] Comprehensive documentation

## 📚 Documentation

Full documentation will be available in the `docs/` directory, including:
- Architecture decisions
- Deployment guides
- Troubleshooting procedures
- Network topology
- Disaster recovery plans

## 🎓 Learning Objectives

- Infrastructure-as-Code practices
- Container orchestration
- Monitoring and observability
- GitOps workflows
- Cloud integration
- Production deployment patterns

## 📝 Blog Series

Follow along with the build process on my blog:
- Part 1: Architecture & Planning *(coming soon)*
- Part 2: Infrastructure as Code *(coming soon)*
- Part 3: CI/CD Pipeline *(coming soon)*
- Part 4: Monitoring & Observability *(coming soon)*

## 🔗 Related Projects

- [Career Catalyst](https://github.com/thejollydev/career-catalyst) - Job search automation platform
- [Homelab Pulse](https://github.com/thejollydev/homelab-pulse) - Real-time monitoring dashboard

## 📫 Contact

- Portfolio: [soper.dev](https://soper.dev)
- LinkedIn: [joseph-soper-dev](https://www.linkedin.com/in/joseph-soper-dev/)
- Email: joseph@soper.dev

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
