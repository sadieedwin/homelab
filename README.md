# 🏠 MONLAB

**My personal homelab for learning, experimenting, and building.**

MONLAB is my small home infrastructure environment where I practice Linux administration, networking, virtualization, automation, and observability.

It's a hands-on environment where I can **build → break → troubleshoot → document → improve**.

---

## 🖥️ Infrastructure

### Hardware

* **Dell OptiPlex 3040 Mini**

  * Proxmox VE
  * Virtualization host
 
* **Dell OptiPlex 3050 Mini**

  * Physical Operations node
  * Operations server: NGINX, AdGuard Home, Uptime Kuma
 
 * **Dell OptiPlex 7060 SFF**

   * General-purpose Ubuntu Server
   * File server, test, etc.

* **Custom Desktop**

  * Used for additional workloads and experiments

* **TP-Link Managed Switch**

  * Network connectivity
  * VLAN/networking experiments

* **Converge Router**

  * Internet gateway
---
 

  <img width="440" height="440" alt="monlab" src="https://github.com/user-attachments/assets/824293b0-26dd-4097-8587-214a17d64ff4" />
  
---

## ⚙️ Virtualization

**Proxmox VE** is currently used as the primary hypervisor.

Current workloads include:

* 🐧 Linux Virtual Machines
* 📦 LXC Containers
* 🔐 Bastion Host
* 📊 Observability Server
* 🎵 Navidrome
* 📁 Samba / File Storage
* 🌐 Web Applications

---

## 📊 Observability

One of the main purposes of MONLAB is learning observability and monitoring.

Current stack:

* **Prometheus**
* **Node Exporter**
* **Grafana**
* **Splunk** (Planned)


The goal is to monitor the infrastructure, visualize system metrics, and practice troubleshooting real-world operational scenarios.

---

## 🌐 Networking

The homelab currently uses a managed network switch and multiple network segments.

Areas I'm experimenting with:

* Linux networking
* Static IPs
* DHCP
* Firewalling
* Bastion hosts
* Service accessibility
* VLANs
* Network isolation

---

## 🚀 Applications & Projects

Some applications running in the lab:

* 🚨 **Incident Tracker** — personal incident repo
* 🔗 **URL Repository** — personal link repository
* 🎵 **Navidrome** — self-hosted music server
* 📁 **Samba** — network file sharing
* 🔐 **Vaultwarden** — planned/self-hosted password management experiment

More projects will be added as the lab evolves.

---

## 🎯 What I'm Learning

MONLAB is primarily a learning environment.

Current focus areas:

```text
Linux
Networking
Virtualization
Bash
Git
Docker
Ansible
Prometheus
Grafana
Splunk
DevOps
SRE
```

---


## 📌 Status

🟢 **Active**

MONLAB is continuously evolving as I learn new technologies and build new projects.

> **Build it. Break it. Fix it. Learn from it.**

---

*This repository provides an overview of my homelab. Detailed configuration and operational documentation is maintained separately.*
