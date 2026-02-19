#  OSI Layers Explanation

---

#  Layer 1: Physical Layer

The Physical Layer is the lowest OSI layer.

It deals with physical hardware used for transmitting raw bits (1s and 0s).

### Responsibilities
- transmitting raw bits
- defining voltage and signal timing
- defining cable types and connectors

### Examples
- Ethernet cables
- Fiber optic cables
- Hubs
- NIC
- Wireless signals

---

#  Layer 2: Data Link Layer

The Data Link Layer handles:

- MAC addressing
- framing
- error detection within local networks

### NIC (Network Interface Card)
- each NIC has a unique MAC address
- permanently assigned by manufacturer
- can be spoofed

### Responsibilities
- adding source/destination MAC address
- formatting data into frames
- error detection

---

#  Layer 3: Network Layer

Responsible for:

- routing packets between networks
- logical addressing (IP)

### Routing
Routing selects the best path for packets.

Common protocols:
- OSPF
- RIP

### Factors
- shortest path
- reliability
- speed

Layer 3 devices:
- Router

---

# Layer 4: Transport Layer

Handles data delivery between devices using:

- TCP
- UDP

TCP = reliable  
UDP = fast

---

#  Layer 5: Session Layer

Responsible for:

- establishing sessions
- managing sessions
- terminating sessions

Uses checkpoints to recover lost data efficiently.

---

#  Layer 6: Presentation Layer

Responsible for:

- translation
- formatting
- compression
- encryption/decryption

Ensures compatibility between different systems.

---

#  Layer 7: Application Layer

Top layer used by users.

Provides services and protocols like:

- DNS
- HTTP/HTTPS
- FTP
- SMTP

Examples:
- web browsers
- email clients
- FileZilla
