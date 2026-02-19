#  OSI Model (Open Systems Interconnection Model)

The OSI Model is a fundamental networking framework that defines how data is transmitted and received across a network.

It provides a standardized structure so different devices and technologies can communicate effectively.

---

#  Purpose of OSI Model

The OSI model provides:

- structured communication framework
- standard rules for data transfer
- compatibility between vendors
- easier troubleshooting by isolating problems

---

#  Structure of OSI Model

The OSI model has **7 layers**:

| Layer | Name | Function |
|------|------|----------|
| 7 | Application | Provides network services to applications |
| 6 | Presentation | Translates, encrypts, formats data |
| 5 | Session | Manages sessions and connections |
| 4 | Transport | Reliable delivery and flow control |
| 3 | Network | Routing and IP addressing |
| 2 | Data Link | MAC addressing and framing |
| 1 | Physical | Transmits raw bits via hardware |

---

#  Encapsulation Process

As data moves from Layer 7 down to Layer 1, each layer adds its own header information.  
This process is called **encapsulation**.

At the receiver side, each layer removes the headers.  
This is called **de-encapsulation**.

---

#  Importance of OSI Model

OSI is important because:

- standardizes device communication
- simplifies network design
- improves troubleshooting
- supports interoperability
