#  Port Forwarding

Port forwarding is a networking technique that allows devices outside a private network (Internet) to access services inside a private network.

Without port forwarding, services inside a LAN cannot be accessed from outside.

Examples:
- web servers
- game servers
- remote desktop
- CCTV systems

---

#  How It Works (Without Port Forwarding)

Example:

- Server IP: `192.168.1.10`
- Web server runs on port 80

Only local devices can access it.

Internet users cannot because private IPs are not reachable externally.

---

#  How It Works (With Port Forwarding)

Example:

Public IP:
82.62.51.70


Router forwards:

- Public IP `82.62.51.70` port `80`
to
- Private IP `192.168.1.10` port `80`

Now internet users can access the server.

---

#  Port Forwarding vs Firewall

Many people confuse these.

### Port Forwarding
- forwards traffic to a specific internal device

### Firewall
- decides if traffic is allowed or blocked

---

#  Where Port Forwarding is Configured?

Port forwarding is configured on the router.

The router:
- receives internet traffic
- checks forwarding rules
- sends traffic to correct internal IP

---

#  Short Definition

Port forwarding is a router configuration that allows external devices to access services on an internal private IP by forwarding traffic from a public IP and port to a private IP and port.
