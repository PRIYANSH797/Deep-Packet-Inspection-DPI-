# Multithreaded Deep Packet Inspection (DPI) Engine

A high-performance Deep Packet Inspection (DPI) engine developed in C++ for analyzing network traffic from PCAP files using a multithreaded Producer-Consumer architecture.

## Features
- Multithreaded packet processing
- Producer-Consumer architecture
- Thread-safe queues
- Ethernet packet parsing
- IPv4 parsing
- TCP parsing
- UDP parsing
- HTTP Host extraction
- TLS Server Name Indication (SNI) extraction
- Five Tuple flow tracking
- Configurable packet filtering

 ## Tech Stack
- C++
- STL
- Multithreading
- Mutex
- Condition Variable
- Computer Networks
- PCAP
  
## Architecture

PCAP File
     │
     ▼
Producer Thread
     │
Thread Safe Queue
     │
     ▼
Worker Threads
     │
Packet Parsing
     │
Five Tuple Tracking
     │
HTTP / TLS Extraction
     │
Packet Filtering

## Folder Structure
include/
src/
CMakeLists.txt
README.md

## Skills Demonstrated
- Concurrent Programming
- Thread Synchronization
- Producer Consumer Pattern
- Computer Networks
- Packet Parsing
- TCP/IP
- HTTP
- TLS

 ## Future Improvements
- IPv6 Support
- DNS Parsing
- Performance Benchmarking
- Live Packet Capture
