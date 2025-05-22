# Dell Inspiron Homelab / Cloud Server Project 🖥️☁️ 

## 🚀 Project Overview
This project transforms my old Dell Inspiron into a personal homelab/cloud server for cybersecurity, networking, and cloud computing practice. This is also to completely understand the trial and error process for making homelabs, and curating them to my personal needs.

## 🔧 Hardware Specs (if it has a check, it has been added to the desktop build, if not, its in progress)
- **Model**: Dell Inspiron 3646
- **CPU**: Intel
- **RAM**: 2x4GB DDR3 SO-DIMM, 1.35V
- **Storage**: 2.5" SATA SSD (120-500GB) (_thinking of getting an HDD_)
- **Network**: Ethernet

## 💿 Installed OS
- **OS**: Linux (Ubuntu Server)
- Installed via bootable USB using [Rufus/BalenaEtcher](https://www.balena.io/etcher/)

## 🧰 Services & Tools

| Category       | Tools/Services                             |
|----------------|--------------------------------------------|
| Cybersecurity  | Kali Linux, Suricata, Zeek, Security Onion |
| Networking     | pfSense, Pi-hole, OpenVPN/WireGuard        |
| Cloud/DevOps   | Docker, Portainer, k3s, Nextcloud          |
| Vulnerable Apps| DVWA, Metasploitable, Juice Shop           |

## 🔌 Remote Access
- **SSH** enabled on port `22`
- **Tailscale** for secure remote access
- **Cockpit** for monitoring

## 📘 Learning Goals
- Build and secure a self-hosted environment
- Practice detection with IDS/IPS tools
- Deploy containerized services with Docker
- Explore networking with DNS/VPN setups

## 📦 What You Can Do with This Homelab

- Pi-hole *(Ad-blocking DNS server)*: Lightweight; runs on even Raspberry Pi Zero
- Web hosting *(static or small dynamic sites)*: Apache, Nginx, Flask, or Node.js – perfect for practice
- Self-hosted services *(like Gitea, Portainer, or DuckDNS)*: Just keep resource limits in mind
- Linux-based pentesting labs *(e.g. Kali, Metasploit)*: Also lightweigh; best when using lightweight distros or CLI tools
- Basic containerization *(A docker)*: With caution	Limit container count due to RAM/CPU
- Basic file server or media server: Use Samba or Plex with low-res files
- Learning firewalls, DNS, port management: Ideal for this kind of practice

## 📚 Notes & Challenges
- Learned how to configure `iptables` firewall rules
- Faced an issue with USB boot (fixed by using legacy boot)

## ✅ Next Steps
- [ ] Deploy more VMs/containers
- [ ] Automate updates and backups
- [ ] Try Kubernetes workloads

## 🧠 Inspiration
- [Homelab Subreddit](https://www.reddit.com/r/homelab/)
- [Awesome-Selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted)
