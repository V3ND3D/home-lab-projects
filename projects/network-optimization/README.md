# Network Optimization & Segmentation Project

## 📌 Summary
Planned, configured, and optimized a segmented home network to improve both performance and security for gaming, personal devices, and lab systems.

- Built dual-band segmentation to isolate IoT and prioritize lab devices
- Integrated VPN and DNS customization to improve privacy and control
- Achieved consistent **Open NAT** and resolved all Xbox disconnection issues while maintaining strict security posture

## 🎯 Goals & Purpose
- Improve network reliability across all connected devices
- Isolate vulnerable/low-trust devices via segmentation
- Maintain secure connectivity without sacrificing performance (e.g. Open NAT for Xbox)

## 🧰 Tech Stack / Tools
- Home router & extender
- Custom DNS servers
- ProtonVPN
- Wireshark (traffic inspection)
- NAT, DMZ, and firewall configuration

## 🏗️ Network Architecture
- Dual-band Wi-Fi:
  - **2.4 GHz** → IoT & legacy devices
  - **5 GHz** → gaming, lab, productivity
- VPN routing for secure lab traffic
- Strict firewall rules applied to sensitive devices

## 🔧 Features & Milestones
- ✅ DNS customization and filtering
- ✅ Dual-band segmentation with performance prioritization
- ✅ Enabled DMZ + optimized NAT configuration for **Xbox Series X**
  - Achieved **Open NAT** for smooth multiplayer performance
  - Eliminated prior issues with lag, packet loss, and random disconnects
  - Balanced with strict firewall rules to avoid exposing other lab devices
- ✅ Resolved network instability via extender reconfiguration and router-level resets
- ✅ Conducted Wireshark traffic analysis:
  - Baseline behavior observed (TCP, ARP, TLS 1.2, ICMPv6)
  - No anomalous or malicious traffic identified

## 🔐 Security Considerations
- Firmware up-to-date on router and extender
- Blocked inbound traffic except VPN whitelisted ports
- Game console traffic isolated from lab infrastructure
- Xbox placed behind NAT with port forwarding only where required
- MAC filtering planned for sensitive hosts (not yet implemented)
- Verified no device exposure via external scans

## 🚧 Planned Enhancements
- VLAN setup to separate lab and entertainment traffic
- Integration of self-hosted Pi-hole for ad/tracking blocking
- Syslog logging for long-term analysis and intrusion detection
- MAC address filtering on key endpoints (lab PC, MacBook, VMs)
