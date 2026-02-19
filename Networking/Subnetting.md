#  Subnetting

Networks come in different shapes and sizes, from small home setups to large corporate infrastructures.

As networks grow, managing them efficiently becomes more complex.

**Subnetting** is the process of dividing a large network into smaller, manageable networks called **subnets**.

---

##  Simple Analogy

Subnetting is like dividing a cake among friends.

- There is limited cake
- It must be divided carefully

Similarly, there is a limited number of IP addresses, and subnetting helps allocate them logically.

---

#  Why Subnetting is Needed

In organizations, different departments exist such as:

- Accounting
- Finance
- Human Resources

Each department may require its own section of the network for organization and security.

Subnetting allows network administrators to logically separate departments within a larger network.

---

# ⚙️ How Subnetting Works

Subnetting is achieved using a value called a **Subnet Mask**.

An IP address consists of four octets (32 bits), for example:

192.168.1.100


A subnet mask also consists of four octets (32 bits) ranging from 0 to 255.

The subnet mask determines:

- how many subnets are created
- how many hosts are available in each subnet

---

#  Key Components of a Subnet

Each subnet uses IP addresses in three important ways:

---

## 1️ Network Address

- Identifies the start of the network
- Represents the subnet itself
- Cannot be assigned to a device

---

## 2️ Host Address

- Assigned to devices in the subnet
- Identifies a specific device

Example:192.168.1.100


---

## 3️ Default Gateway

A default gateway is:

- the router device that connects networks
- used when sending traffic outside the local subnet

Usually uses:
192.168.1.1
    or 
192.168.1.254



---

#  Subnetting in Small vs Large Networks

In home networks, subnetting is rarely noticeable because fewer than 254 devices exist.

However, in large organizations like offices or universities, subnetting is essential due to many devices such as:

- computers
- printers
- security cameras
- sensors
- servers

---

#  Benefits of Subnetting

Subnetting provides:

###  Efficiency
Reduces unnecessary network traffic.

###  Security
Separates sensitive systems from less secure networks.

###  Control
Allows better management and organization.

---

#  Real-World Example

A café may have:

- Employee network (payment systems, internal devices)
- Customer network (public Wi-Fi)

Subnetting keeps these networks separated, preventing public users from accessing sensitive systems.





