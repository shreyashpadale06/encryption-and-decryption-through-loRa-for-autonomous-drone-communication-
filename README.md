# encryption-and-decryption-through-loRa-for-autonomous-drone-communication-
A secure drone-to-drone communication system using LoRa technology &amp; encryption to transmit GPS coordinates. The 1st drone collects and encrypts location data before transmission, while the 2nd drone receives &amp; decrypts  it to recover the original coordinates. Designed for secure location sharing in search &amp; rescue &amp; disaster management operations.

# Secure Drone-to-Drone GPS Communication Using LoRa

## Project Description

This project focuses on secure communication between two drones using **LoRa (Long Range) technology and data encryption**. It is mainly designed for search-and-rescue operations, where sharing location information securely is important.

The first drone collects GPS coordinates (latitude and longitude), encrypts them, and transmits the encrypted data through a LoRa module. The second drone receives this data and decrypts it using the corresponding key to recover the original GPS coordinates.

This ensures that location information is protected during transmission while allowing drones to share coordinates over long distances with low power consumption.

## Key Features
- GPS coordinate collection (latitude and longitude).
- Encryption of location data before transmission.
- Long-range communication using LoRa modules.
- Decryption of received data to recover original coordinates.
- Secure location sharing for search-and-rescue operations.

## Working Process
1. Drone 1 collects GPS coordinates.
2. The coordinates are encrypted.
3. Encrypted data is transmitted using LoRa.
4. Drone 2 receives the encrypted data.
5. The data is decrypted to recover the original coordinates.
6. The recovered location can be used for rescue and navigation purposes.

## Technologies Used
- LoRa Communication
- GPS
- Data Encryption and Decryption
- Embedded Systems
- Drone-to-Drone Communication

## Applications
- Search-and-rescue missions
- Disaster management
- Emergency location sharing
- UAV communication
