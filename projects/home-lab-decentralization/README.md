# Home Lab & Digital Decentralization Project

## 📌 Summary
Designed and maintained a multi-device security lab focused on privacy, system hardening, and digital sovereignty.

## 🎯 Goals & Purpose
- Build a controlled, secure lab for experimentation with real-world security principles.
- Transition away from centralized tech ecosystems into local-first and privacy-preserving alternatives.

## 🖥️ Lab Architecture
- Dual-host setup: Windows 11 Pro PC and macOS (MacBook Air M3)
- Both systems run **Kali Linux VMs** for penetration testing and secure operations
- **File sharing** enabled across the local network between hosts and VMs for seamless transfers
- VMs configured to persist key tools and scripts across sessions to reduce redundancy

## 🧰 Tech Stack / Tools
- Windows 11 Pro (host OS)
- macOS (host OS)
- Kali Linux (VMs on both platforms)
- Proton (VPN, Drive, Mail)
- PowerShell, Wireshark, VirtualBox, UTM

## 🔧 Features & Milestones
- ✅ Multi-device hardening (Windows, macOS, Linux)
- ✅ Full migration to Proton ecosystem (VPN, Drive, Mail)
- ✅ VPN Secure Core routing (Iceland/Switzerland)
- ✅ Account minimization (from 130 → 51 essential services)
- ✅ OSINT data exposure analysis (zero confirmed leaks)

## 🔐 Security Considerations
- Hardened firewall & DNS
- All sensitive files stored offline or encrypted
- Proton Drive used only for essential cloud sync
- VMs used for isolated testing and network-level sandboxing

## 🚧 Planned Enhancements
- MAC address whitelisting
- Self-hosted VPN
- IDS/IPS deployment
- Wi-Fi auditing & analysis
