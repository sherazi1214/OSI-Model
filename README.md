# OSI-Model

The OSI Model is a 7-layer conceptual framework used to understand and standardize how different networking protocols and systems communicate over a network.

![OSI-Model](https://infosys.beckhoff.com/content/1033/tf6310_tc3_tcpip/Images/png/84433547__en-US__Web.png)


## 🔍 Detailed Layer-by-Layer Breakdown
### 🔹 Layer 7: Application Layer
Role: Closest to the end user. Interfaces directly with software applications.

#### Functions:

Email, file transfer, web browsing

Provides network services to applications

#### Examples:

HTTP, FTP, SMTP, DNS, POP3, Telnet

### 🔹 Layer 6: Presentation Layer
Role: Translates data from application layer into format understandable by network.

#### Functions:

Data encryption/decryption

Compression and decompression

Syntax and format translation

#### Examples:

SSL/TLS, JPEG, MPEG, ASCII, EBCDIC

### 🔹 Layer 5: Session Layer
Role: Establishes, manages, and terminates connections between applications.

#### Functions:

Dialog control

Session checkpoints and recovery

#### Examples:

NetBIOS, RPC (Remote Procedure Call), PPTP

### 🔹 Layer 4: Transport Layer
Role: Ensures complete and reliable data transfer.

#### Functions:

Flow control

Error recovery

Segmentation and reassembly

#### Key Protocols:

TCP (Transmission Control Protocol) – reliable

UDP (User Datagram Protocol) – faster, unreliable

### 🔹 Layer 3: Network Layer
Role: Handles logical addressing and path determination.

##### Functions:

Routing and forwarding

IP addressing

Packet switching

#### Key Protocols:

IP (IPv4, IPv6), ICMP, RIP, OSPF

### 🔹 Layer 2: Data Link Layer
Role: Ensures reliable data transfer across the physical link.

#### Functions:

MAC addressing

Error detection (not correction)

Frame synchronization

#### Sub-layers:

LLC (Logical Link Control)

MAC (Media Access Control)

Key Protocols/Technologies:

Ethernet, PPP, Switches, VLANs

### 🔹 Layer 1: Physical Layer
Role: Transmits raw bits (0s and 1s) over the physical medium.

#### Functions:

Defines cables, cards, voltage levels

Data rate and signal type

#### Examples:

Ethernet cables, fiber optics, hubs, radio waves

# 🎓 Mnemonic to Remember the OSI Layers (Top to Bottom):
## "All People Seem To Need Data Processing"

A – Application

P – Presentation

S – Session

T – Transport

N – Network

D – Data Link

P – Physical

Or from bottom to top:
## "Please Do Not Throw Sausage Pizza Away"
