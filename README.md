# Networking Fundamentals

## Protocols
- **TCP (Transmission Control Protocol):** Ensures reliable and ordered delivery of data.
- **UDP (User Datagram Protocol):** Allows fast transmission without ensuring data reliability. Used for video streaming, gaming, etc.
- **HTTP (Hypertext Transfer Protocol):** Facilitates client-server communication for web requests.
- **SMTP (Simple Mail Transfer Protocol):** Used for sending emails.
- **POP3 & IMAP:** Protocols used for receiving emails.

## Networking Basics
- **Data Delivery:** Data is delivered in packets or chunks across networks.
- **IP Address:** Represented as x.x.x.x (0-255), used to identify devices on a network.
- **Port Number:** Identifies specific applications on devices. Ranges: Reserved ports (0-1023), application ports (1024-49152), and others.
- **Bandwidth:** Mbps, Kbps, Gbps represent data transmission rates.

## Network Types
- **LAN (Local Area Network):** Small-scale networks like homes or offices usually connected via Wi-Fi.
- **MAN (Metropolitan Area Network):** Covers a city or metropolitan area.
- **WAN (Wide Area Network):** Spans across countries using optical fiber cables, utilizing technologies like SONET and Frame Relay.

## Network Topologies
1. **Bus:** All devices connected to a single line.
2. **Ring:** Devices connected in a circular manner.
3. **Star:** Devices connected to a central hub or switch.
4. **Tree:** Combination of Bus and Star topologies.
5. **Mesh:** Every computer is interconnected.

## OSI Model Layers
1. **Application Layer:** Software that sends and receives messages.
2. **Presentation Layer:** Handles encryption, decryption, and data translation.
3. **Session Layer:** Manages connections, segments data with sequence numbers.
4. **Transport Layer:** Ensures error control, reliable data transport.
5. **Network Layer:** Communication between computers, routing, logical addressing.
6. **Data Link Layer:** Direct communication with sender and receiver, uses IP addresses.
7. **Physical Layer:** Transmits raw bit streams over physical media.

## TCP/IP Model Layers
1. **Application Layer:** Deals with user interactions and protocols like web browsers.
2. **Transport Layer:** Manages protocols for data transport.
3. **Network Layer:** Concerned with client communication.
4. **Data Layer:** Not explicitly defined.
5. **Physical Layer:** Handles physical data transmission.

## STATUS CODES
1. ** 1** -> informational
2. ** 2** -> success
3. ** 3** -> refirecting
4. ** 4** -> client side error
5. ** 5** -> internal server error
