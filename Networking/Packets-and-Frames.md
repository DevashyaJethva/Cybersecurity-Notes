# 📦 Packets and Frames

Packets and frames are small units of data used for communication.

They are related but operate at different OSI layers.

---

# 📌 Packet (Layer 3 - Network Layer)

A packet exists at Layer 3.

It contains:

- IP header
- payload (actual data)

Packets use IP addresses for delivery across networks.

Whenever we talk about routing or IP addressing, we are referring to packets.

---

# 📌 Frame (Layer 2 - Data Link Layer)

A frame exists at Layer 2.

A frame:

- encapsulates the packet
- adds MAC addresses
- delivers data inside a local network

Frames handle physical delivery within a LAN.

---

# 🔁 Encapsulation Analogy

Think of sending a letter:

- Letter = Packet
- Envelope = Frame

The envelope helps deliver the letter.

Removing the envelope at destination is called **de-encapsulation**.

---

# ⭐ Why Packets are Used

Packets allow data to be transmitted in small pieces instead of one large block.

Benefits:
- reduces congestion
- avoids bottlenecks
- easier recovery
- efficient transmission

Example:
A website image loads using multiple packets that get reassembled.

---

# 🧾 IP Packet Header Fields

Important IP header fields include:

### Time To Live (TTL)
- prevents packets looping forever
- decreases at every router
- packet discarded at TTL = 0

### Checksum
- verifies integrity
- detects corruption

### Source Address
- IP of sender

### Destination Address
- IP of receiver

---

# 🔑 Key Difference

- Packet = Logical delivery using IP (Layer 3)
- Frame = Physical delivery using MAC (Layer 2)

Together, they enable reliable communication.
