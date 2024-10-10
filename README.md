# Secure System-on-Chip (SoC) for IoT Development

## Overview
The Secure System-on-Chip (SoC) for IoT Development project focuses on designing a secure architecture tailored for Internet of Things (IoT) applications. This SoC integrates AES encryption and communication protocols like MQTT and CoAP to ensure data security and efficient communication across IoT devices.

## Features
- **AES Encryption**: Implemented AES-128 encryption to secure data transmission within IoT applications.
- **Protocol Support**: Incorporated MQTT and CoAP protocols to facilitate lightweight and efficient communication between devices.
- **Performance Evaluations**: Conducted evaluations on memory consumption and cycle count to optimize the encryption processes.
- **Galois/Counter Mode (GCM)**: Integrated GCM with AES-128 to enhance both encryption and decryption processes.
- **Initialization Vector Management**: Developed methods for generating valid initialization vectors (IVs) to maintain data integrity in the SensorTag publisher/subscriber system.

## Workflow
1. **SoC Design**:
    - Designed the architecture of the SoC, integrating AES encryption, MQTT, and CoAP protocols.
  
2. **AES Encryption Implementation**:
    - Implemented the AES-128 encryption algorithm and developed key schedule management strategies.
    - Conducted performance evaluations on memory usage and cycle count for various encryption tasks.

3. **GCM Integration**:
    - Integrated Galois/Counter Mode (GCM) with AES-128 for enhanced encryption capabilities, allowing for simultaneous encryption and integrity checking.

4. **Initialization Vector Generation**:
    - Devised methods for generating valid IVs to ensure data integrity and security within the SensorTag system.

## Hardware & Tools
- **System-on-Chip (SoC) Architecture**: Custom-designed architecture supporting IoT applications.
- **AES Encryption**: Used standard AES-128 algorithm for data security.
- **Communication Protocols**: Implemented MQTT and CoAP for efficient data transmission.
- **Development Environment**: Designed and tested using a hardware description language (HDL) for SoC implementations.

## Installation and Setup
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/TheMechanicHulk/Secure-SoC-for-IoT-Development.git
    cd Secure-SoC-for-IoT-Development
    ```

2. **Build the SoC Design**:
    - Follow the provided instructions in the `docs/` folder to set up the development environment and build the SoC design files.

3. **Testing the Implementation**:
    - Run the provided test scripts to evaluate the performance of AES encryption and communication protocols.

## Results
- The implementation demonstrated efficient data encryption and secure communication for IoT applications, successfully maintaining data integrity across the SensorTag system.
- Performance evaluations indicated optimal memory usage and cycle counts for AES encryption processes, confirming the viability of the design for real-world applications.

## Future Improvements
- **Enhanced Security Features**: Explore additional security features such as digital signatures and secure boot mechanisms.
- **Protocol Optimization**: Investigate optimizations for MQTT and CoAP protocols to further enhance communication efficiency.
- **Scalability Studies**: Conduct studies to evaluate the SoC's performance and scalability in large-scale IoT deployments.

## File Structure
```bash
├── docs/              # Documentation for SoC design and implementation details
├── scripts/           # Test scripts for evaluating AES encryption and communication protocols
└── README.md          # Project documentation
