# Simple-VPN
Here's a simple VPN application in Python. This is a point-to-point tunnel (not a full-featured production VPN like OpenVPN or WireGuard). It works on Linux only (requires root privileges for TUN interface). It creates a virtual network interface (tun0), encrypts traffic with a simple XOR (for demo purposes), and tunnels packets over UDP
