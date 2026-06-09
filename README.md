# 🔐 Secure Remote Access

Secure remote access to home lab services using Cloudflare Tunnel and WireGuard VPN.
This repository documents the full setup and configuration of secure
external access to the home lab without exposing open ports to the internet.

## 🖥️ Infrastructure

| Role | Device | Specs |
|---|---|---|
| Server | ASUS ROG Strix | Intel i7 · 16GB RAM · 256GB SSD + 1TB HDD |
| Workstation | ASUS Professional | AMD Ryzen 9 · 32GB RAM |

## 🛠️ Stack

- **Tunnel:** Cloudflare Tunnel (cloudflared)
- **VPN:** WireGuard
- **DNS:** Cloudflare DNS
- **SSL:** Cloudflare managed certificates
- **Firewall:** UFW

## ✅ Roadmap

- [ ] Cloudflare account setup and domain configuration
- [ ] Cloudflared installation on server
- [ ] First tunnel — expose Grafana dashboard securely
- [ ] Custom domain with HTTPS for home lab services
- [ ] WireGuard VPN installation and configuration
- [ ] Peer configuration — access from anywhere
- [ ] Split tunneling setup
- [ ] Access policies and authentication rules

## 💡 Goal

Access any home lab service securely from anywhere in the world
without opening a single port on the router.
No exposed attack surface. No dynamic DNS hacks.

## 📐 Architecture

*Diagram coming soon*

## 📚 Documentation

Each step is documented as it is completed.
All configuration files are included in this repository.
