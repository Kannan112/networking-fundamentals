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
1.** -> informational
2.** -> success
3.** -> refirecting
4.** -> client side error
5.** -> internal server error

# TCP/IP Model Overview

This repository provides a brief explanation of the TCP/IP model and related protocols. Understanding these concepts is crucial for network communication and data transmission.

## TCP/IP Model Layers

1. **Application Layer:** Responsible for end-user application access to the network using protocols like HTTP, SMTP, FTP, and DNS.
2. **Transport Layer:** Enables end-to-end communication between devices using protocols such as TCP and UDP.
3. **Network Layer:** Provides logical addressing for devices, packetizes data for transmission, and manages routing.
4. **Data Link Layer:** Offers physical addressing, ensures error-free transmission, and facilitates channel sharing among devices.
5. **Physical Layer:** Handles the physical transmission of data via cables, wireless signals, etc.

## Application Layer Protocols

- **SMTP (Simple Mail Transfer Protocol):** Used for sending emails.
- **POP3 (Post Office Protocol version 3):** Enables receiving emails from a remote server to a local email client.

## Email Process using SMTP

1. Establish a connection with the server.
2. Send the email message via SMTP.
3. Email is forwarded to the recipient's server for storage and retrieval by their email client.

## Transport and Network Layer

- **Transport Layer:** Sends data to the application layer.
- **Network Layer:** Sends packets to other devices on the network.

## Multiplexing

- **Multiplexing:** Transmitting multiple signals over a shared channel.
- **TCP:** Assigns unique port numbers to data streams for proper delivery.
- **Demultiplexing:** Identifies target applications using port numbers at the receiver's end.

## TCP and UDP Checksums

- Both TCP and UDP use checksums to verify data integrity during transmission.
- TCP verifies entire packet data, while UDP checks errors only in the header.
- TCP retransmits lost packets; UDP does not.

## Timer Usage in TCP

- TCP uses timers to monitor packet flow between devices.
- Detects lost packets for efficient retransmission and ensures data delivery.


