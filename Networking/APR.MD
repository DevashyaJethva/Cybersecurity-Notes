# 🔁 ARP (Address Resolution Protocol)

Devices on a network have two main identifiers:

- **IP Address** (logical identifier)
- **MAC Address** (physical identifier)

The **Address Resolution Protocol (ARP)** is responsible for linking these two.

ARP allows a device to find the MAC address associated with a specific IP address on a local network.

Without ARP, devices would know the destination IP but would not know the MAC address required for local delivery.

---

# 🎯 Purpose of ARP

ARP enables communication inside a LAN by:

- matching an IP address to a MAC address
- allowing physical delivery of data
- maintaining mappings in memory

Each device stores mappings in an **ARP cache**.

---

# 🗂 What is an ARP Cache?

An ARP cache is a temporary table stored on a device.

It contains:

- IP addresses of other devices
- corresponding MAC addresses

This reduces repeated ARP requests and improves efficiency.

---

# ⚙️ How ARP Works

ARP uses two message types:

---

## 1️⃣ ARP Request

- Sent as a broadcast to all devices
- Message:
  **"Who has this IP? Send me your MAC."**

---

## 2️⃣ ARP Reply

- Only the device with that IP responds
- Sends its MAC address directly back

---

# 🧾 Step-by-Step ARP Process

1. Device A wants to send data to Device B.
2. Device A knows Device B’s IP but not its MAC.
3. Device A sends an ARP Request (broadcast).
4. Device B replies with its MAC address.
5. Device A stores it in ARP cache.
6. Communication continues using MAC address.

---

# ⭐ Importance of ARP

ARP is essential because:

- local network delivery requires MAC addresses
- IP addresses alone are not enough
- ensures accurate device-to-device communication
