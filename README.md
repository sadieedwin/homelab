# 🏠 MONLAB

**My personal homelab for learning, experimenting, and building.**

MONLAB is my small home infrastructure environment where I practice Linux administration, networking, virtualization, DevOps, automation, and observability.

It's a hands-on environment where I can **build → break → troubleshoot → document → improve**.

---

## 🖥️ Infrastructure

### Hardware

* **Dell OptiPlex 3040 Mini**

  * Proxmox VE
  * Primary homelab server

* **Custom Desktop**

  * Ryzen 5 5600G
  * 16 GB RAM
  * Used for additional workloads and experiments

* **TP-Link Managed Switch**

  * Network connectivity
  * VLAN/networking experiments

* **Converge Router**

  * Internet gateway

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
* **Splunk**
* **Icinga**

The goal is to monitor the infrastructure, visualize system metrics, and practice troubleshooting real-world operational scenarios.

---

## 🌐 Networking

The homelab currently uses a managed network switch and multiple network segments.

Areas I'm experimenting with:

* VLANs
* Network isolation
* Static IPs
* DHCP
* Linux networking
* Firewalling
* Bastion hosts
* Service accessibility

---

## 🚀 Applications & Projects

Some applications running in the lab:

* 🚨 **Incident Tracker** — IT incident management application
* 🔗 **URL Repository** — personal technical link repository
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
Python
Bash
Git
Docker
Ansible
Prometheus
Grafana
Splunk
DevOps
SRE
Cloud
```

---

## 🗺️ Homelab Overview

```text
                         Internet
                            │
                     ┌──────▼──────┐
                     │   Router    │
                     │  / Gateway  │
                     └──────┬──────┘
                            │
                     ┌──────▼──────┐
                     │   Managed   │
                     │   Switch    │
                     └──────┬──────┘
                            │
                    ┌───────▼────────┐
                    │  Proxmox Host  │
                    │   Dell 3040    │
                    └───────┬────────┘
                            │
              ┌─────────────┼─────────────┐
              │             │             │
          ┌───▼───┐     ┌───▼────┐    ┌──▼─────┐
          │ Apps  │     │Observ-  │    │  LXC   │
          │  VM   │     │ ability │    │Containers│
          └───┬───┘     │   VM   │    └────────┘
              │         └───┬────┘
       ┌──────┴──────┐      │
       │             │      │
   Incident      URL Repo  Grafana
   Tracker                 Prometheus
                           Node Exporter
```

---

## 📌 Status

🟢 **Active**

MONLAB is continuously evolving as I learn new technologies and build new projects.

> **Build it. Break it. Fix it. Learn from it.**

---

*This repository provides a high-level overview of my homelab. Detailed configuration and operational documentation is maintained separately.*
