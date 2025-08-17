# Internal Notes – Network Optimization Project

## 🔍 Key Lessons Learned
- DNS customization and dual-band segmentation greatly improved stability and speed.
- Xbox NAT issues were caused by poor port mapping + improper DMZ config — resolved after multiple resets and re-mapping.
- VPN passthrough on the router was disabled by default — enabling it fixed intermittent ProtonVPN drops.

## ⚠️ Obstacles & Fixes
- Repeated extender failures were due to mismatched DNS sync — had to factory reset both router and extender and reassign static DNS entries.
- Wireshark captures showed some excessive ICMPv6 traffic from old IoT devices — removed those from the main network.

## 💡 Future Notes
- VLAN and MAC filtering will require full router firmware access — consider custom firmware if unsupported (e.g., OpenWRT).
- Documented NAT type may fluctuate depending on Xbox traffic load and ProtonVPN activity — consider creating a secondary non-VPN SSID.
