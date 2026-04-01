# Simple-VPN
Here's a simple VPN application in Python. This is a point-to-point tunnel (not a full-featured production VPN like OpenVPN or WireGuard). It works on Linux only (requires root privileges for TUN interface). It creates a virtual network interface (tun0), encrypts traffic with a simple XOR (for demo purposes), and tunnels packets over UDP
Important Warnings
This is for educational purposes only.
XOR encryption is not secure — use it only for learning.
Run with sudo (needed for TUN device).
Test in a safe environment (two machines or VMs).


Improvements You Can Add

Use proper encryption (e.g., cryptography Fernet or AES).
Dynamic peer discovery (store client address on first packet).
Handle multiple clients.
Add authentication.
Use scapy for packet inspection.
Add SSL/TLS over the UDP socket for better security.

For a more complete example with better structure, check open-source projects like the "CrapVPN" demo or simple TUN/UDP tunnels on GitHub.
Would you like a version with better encryption, TCP transport, or for a different language (Node.js, Go, etc.)? Let me know your platform (Linux/Windows) and requirements!
