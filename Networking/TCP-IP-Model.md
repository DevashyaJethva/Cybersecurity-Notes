#  TCP/IP Model

The TCP/IP model is a simplified networking model compared to OSI.

OSI has 7 layers, TCP/IP has 4 layers:

- Application
- Transport
- Internet
- Network Interface

Like OSI, it also uses encapsulation and decapsulation.

---

#  TCP (Transmission Control Protocol)

TCP works at the Transport layer.

TCP is connection-based, meaning a connection must be established before communication.

TCP guarantees:

- reliable delivery
- correct order
- error detection
- flow control

---

#  Advantages of TCP
- guarantees integrity
- synchronizes order
- reliability checks

# Disadvantages of TCP
- slower than UDP
- requires stable connection
- retransmission causes delay

---

#  Important TCP Header Fields

- Source Port
- Destination Port
- Source IP
- Destination IP
- Sequence Number
- Acknowledgement Number
- Checksum
- Flags
- Data (payload)

---

#  TCP Three-Way Handshake

TCP connection setup process:

1. SYN
2. SYN/ACK
3. ACK

After this, the connection is established.

---

#  Sequence Numbers

Used to track packet order and detect missing segments.

Example:
- ISN = 0
- next segment = 1
- next = 2

---

#  Closing TCP Connection

TCP connection termination:

1. FIN
2. ACK
3. FIN
4. ACK

---

#  RST (Reset)

RST is used to terminate connection immediately when error occurs.

---

#  Key Point

TCP is reliable and connection-oriented.  
Used for web browsing, emails, file transfers.
