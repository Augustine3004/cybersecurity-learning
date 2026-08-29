# OSI Model

## What is the OSI Model?

OSI stands for **Open Systems Interconnection**.

The OSI model is a conceptual framework used to understand how devices communicate over a network. It divides network communication into **7 layers**, with each layer performing a specific function.

---

## The 7 Layers of the OSI Model

| Layer | Name | Main Function |
|---:|---|---|
| 7 | Application | Provides network services to applications |
| 6 | Presentation | Handles data formatting, encryption, and compression |
| 5 | Session | Establishes and manages communication sessions |
| 4 | Transport | Provides end-to-end communication and data delivery |
| 3 | Network | Handles logical addressing and routing |
| 2 | Data Link | Handles frames and MAC addresses |
| 1 | Physical | Transmits raw bits through physical media |

---

## Layer 7 — Application

The Application layer provides network services that applications can use to communicate over a network.

Examples:

- HTTP
- HTTPS
- DNS
- FTP
- SSH
- SMTP

**Example:** A web browser uses HTTP or HTTPS to communicate with a web server.

---

## Layer 6 — Presentation

The Presentation layer is responsible for how data is represented.

Its functions include:

- Data formatting
- Encryption and decryption
- Compression and decompression
- Character encoding

**Example:** Converting data into a format that another system can understand.

---

## Layer 5 — Session

The Session layer establishes, manages, and terminates communication sessions between applications.

Its responsibilities include:

- Establishing sessions
- Maintaining sessions
- Terminating sessions

---

## Layer 4 — Transport

The Transport layer provides end-to-end communication between devices.

Two major protocols are:

- **TCP (Transmission Control Protocol)**
- **UDP (User Datagram Protocol)**

TCP provides reliable and ordered delivery of data.

UDP provides faster communication with less overhead but does not guarantee delivery.

---

## Layer 3 — Network

The Network layer is responsible for logical addressing and routing packets between networks.

A major protocol at this layer is:

- **IP (Internet Protocol)**

Devices use IP addresses to identify network interfaces and determine where packets should be sent.

---

## Layer 2 — Data Link

The Data Link layer is responsible for communication between devices on the same local network.

It deals with:

- Frames
- MAC addresses
- Local network communication
- Error detection

Examples include:

- Ethernet
- Wi-Fi

---

## Layer 1 — Physical

The Physical layer deals with the physical transmission of data.

It transmits data as bits using physical or wireless signals.

Examples include:

- Ethernet cables
- Fiber-optic cables
- Radio signals
- Network connectors

## What I Learned
The OSI model has seven layers.
Each layer has a specific responsibility.
Data moves through the layers when devices communicate.
TCP and UDP operate at the Transport layer.
IP operates at the Network layer.
MAC addresses and Ethernet operate at the Data Link layer.
The Physical layer deals with the transmission of raw bits.
Understanding the OSI model helps with network troubleshooting and cybersecurity investigations.

---

## OSI Model from Layer 7 to Layer 1

```text
7. Application
6. Presentation
5. Session
4. Transport
3. Network
2. Data Link
1. Physical


