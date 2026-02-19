# 🔒 VPN (Virtual Private Network)

A VPN is a technology that allows devices on different networks to communicate securely over the Internet.

It creates a secure encrypted tunnel between devices.

Devices connected through VPN form a private network, even though communication occurs over the public Internet.

---

# 🧾 Example Scenario

Imagine three networks:

- Network #1: Office #1
- Network #2: Office #2
- Network #3: VPN network

Without VPN, Office #1 and Office #2 cannot communicate securely.

With VPN:
- both offices connect through encrypted tunnel
- form a secure private network
- only VPN devices can communicate

---

# ⭐ Benefits of VPN

| Benefit | Description |
|--------|------------|
| Connect locations | Offices share data securely |
| Privacy | Data is encrypted, safer on public Wi-Fi |
| Anonymity | Hides activity from ISP/intermediaries |

⚠️ VPN anonymity depends on the provider. If provider logs traffic, privacy reduces.

---

# 🧪 VPN in Cybersecurity Labs

Platforms like TryHackMe use VPN so users can:

- access lab machines securely
- avoid exposing lab machines publicly
- prevent ISP misunderstanding lab activity

---

# 🧾 Common VPN Technologies

---

## 1️⃣ PPP (Point-to-Point Protocol)
- provides authentication and encryption
- uses private keys and certificates
- cannot leave network alone (non-routable)

---

## 2️⃣ PPTP (Point-to-Point Tunneling Protocol)
- carries PPP over networks
- easy setup
- weak encryption

---

## 3️⃣ IPSec (Internet Protocol Security)
- strong encryption
- widely supported
- more complex configuration

---

# 📊 Quick Comparison

| Technology | Security | Setup Difficulty |
|----------|----------|----------------|
| PPP | Moderate | Moderate |
| PPTP | Weak | Easy |
| IPSec | Strong | Complex |

---

# ✅ Short Definition

A VPN is a technology that creates an encrypted tunnel over the Internet, allowing devices to communicate as if they are on the same private network.
