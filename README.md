# Hey, I'm Robert 👋

DevOps & Cloud Engineer based in Salt Lake City with 20+ years in the industry. I build and automate infrastructure, manage Linux systems, and am actively expanding into Kubernetes, CI/CD pipelines, and cloud-native tooling.

Currently running a homelab with a multi-node Kubernetes cluster, Jenkins, Prometheus, Grafana, Alertmanager, and Ansible — all on Rocky Linux.

---

## 🛠️ Tech Stack

**Operating Systems**
- Rocky Linux / RHEL
- Ubuntu

**Infrastructure & Automation**
- Ansible
- Vagrant
- Jenkins (CI/CD)
- Docker
- Kubernetes

**Monitoring & Observability**
- Prometheus
- Grafana
- Alertmanager

**Cloud**
- AWS
- Azure (in progress)
- DigitalOcean

**Languages & Scripting**
- Python
- Bash
- PowerShell
- YAML / Jinja2

**Web**
- HTML / CSS
- JavaScript
- React
- Django

---

## 📜 Certifications

| Certification | Issuer |
|---|---|
| AWS Cloud Practitioner | Amazon Web Services |
| CompTIA Linux+ | CompTIA |
| CompTIA Cloud Essentials | CompTIA |
| CompTIA A+ | CompTIA |
| CompTIA Systems Support Specialist (CSSS) | CompTIA |
| LPI Linux Essentials | Linux Professional Institute |
| CIW Advanced HTML & CSS Specialist | CIW |

---

## 📂 Featured Projects

### [ansible-learnlinux](https://github.com/zemation/ansible-learnlinux)
Multi-distro infrastructure automation using Vagrant and Ansible — provisions and configures web, database, and file servers across Rocky Linux and Ubuntu. Demonstrates role-based playbook structure, Jinja2 templating, and cross-distribution configuration management.

### [ansible-kubernetes](https://github.com/zemation/ansible-kubernetes)
Ansible playbooks to provision a production-ready Kubernetes 1.32 cluster from scratch on Rocky Linux. Handles kernel modules, firewall configuration, containerd runtime, kubeadm init, Flannel CNI, and worker node joining — fully idempotent.

```bash
ansible-playbook site.yml  # full cluster bootstrap
```

**Stack:** Kubernetes 1.32 · containerd · Flannel · Rocky Linux 10

---

### [sysinfo](https://github.com/zemation/sysinfo)
A lightweight system information CLI tool written in Go. No external dependencies — reads directly from Linux virtual filesystems. Supports subcommands for disk, process, and network info with JSON output and cross-platform support planned.

```bash
sysinfo                      # system overview
sysinfo processes cpu -c 10  # top 10 processes by CPU
sysinfo network ports        # listening ports and owning processes
sysinfo disk --json          # disk usage as JSON
```

**Stack:** Go · Cobra · Linux


---

## 🌐 Find Me

- ☁️ [acloudengineer.com](http://www.acloudengineer.com)

---

*Always building. Always learning.*
