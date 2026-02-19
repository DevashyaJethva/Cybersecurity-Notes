#  Firewall

A firewall is a network security device that controls what traffic is allowed to enter or leave a network.

It acts like border security.

Firewalls decide based on:

- source
- destination
- port number
- protocol (TCP/UDP)

Firewalls use packet inspection to filter traffic.

---

#  Types of Firewalls

Firewalls can be:

- hardware-based (business use)
- router built-in firewalls
- software firewalls (example: Snort)

---

# 🔥 Stateful Firewall

### Description
Stateful firewalls track full connections instead of single packets.

### How It Works
- tracks sessions
- blocks suspicious behavior

### Characteristics
- high resource usage
- higher security
- detects abnormal behavior

---

#  Stateless Firewall

### Description
Stateless firewalls check each packet individually.

### How It Works
- compares packet with static rules

### Characteristics
- low resource usage
- faster but weaker
- depends on rule quality

---

#  Stateful vs Stateless Comparison

| Feature | Stateful | Stateless |
|--------|----------|----------|
| Tracks connection | Yes | No |
| Resource usage | High | Low |
| Security level | Higher | Lower |
| Speed | Slower | Faster |

---

#  Short Definition

A firewall is a network security device that monitors and controls incoming and outgoing traffic using predefined rules. It may operate in stateful or stateless mode.
