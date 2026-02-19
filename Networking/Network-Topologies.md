# 🕸 Network Topologies

In networking, **topology** refers to the physical or logical design of a network.  
It defines how devices are arranged and connected.

The most common LAN topologies include:

- Star Topology
- Bus Topology
- Ring Topology

Each topology has its own advantages and disadvantages.

---

# ⭐ Star Topology

In a **Star Topology**, all devices are connected to a central networking device such as a **switch** or **hub**.

All communication between devices passes through this central device.

---

## ⚙️ How It Works

When one device sends data:

1. Data goes to the central device (switch/hub)
2. The central device forwards it to the destination device

---

## ✅ Advantages

- Highly reliable compared to other topologies
- Easy to add/remove devices (scalable)
- Easier to detect faulty devices
- Good performance due to centralized control

---

## ❌ Disadvantages

- More expensive (requires more cabling + hardware)
- If the central device fails, the entire network stops
- Maintenance becomes harder as network grows

📌 Star topology is the most common topology used today in homes, schools, and companies.

---

# 🚌 Bus Topology

In a **Bus Topology**, all devices connect to a single main cable called the **backbone**.

Data travels along the same cable for all devices.

---

## ⚙️ How It Works

When data is sent, it travels across the backbone cable until it reaches the intended device.

---

## ✅ Advantages

- Simple and easy to set up
- Cost-effective (less cabling)
- No central device required

---

## ❌ Disadvantages

- Network slows down with many devices (bottleneck)
- Difficult to troubleshoot
- Backbone cable is a single point of failure
- Limited scalability

📌 Bus topology is rarely used today.

---

# 🔄 Ring Topology

In a **Ring Topology**, devices are connected in a circular loop.  
Each device is connected directly to two other devices.

---

## ⚙️ How It Works

Data travels in one direction around the ring until it reaches the target device.  
Each device forwards the data to the next device.

---

## ✅ Advantages

- Less chance of data collisions
- Easier to trace faults compared to bus topology
- No central device required

---

## ❌ Disadvantages

- If one device or cable fails, the whole network can fail
- Data may take longer to reach destination
- Not scalable for large networks

📌 Ring topology is less common today but was used in older networks.

