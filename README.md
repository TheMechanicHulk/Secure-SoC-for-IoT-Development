# Secure SoC for IoT Development

## Overview
The Secure System-on-Chip (SoC) for IoT Development project focuses on enhancing data security and communication efficiency for IoT applications. This project involves the design and implementation of a secure SoC utilizing AES encryption and communication protocols such as MQTT and CoAP. 

The SoC is developed for the Raspberry Pi 4, providing a robust platform for secure data transmission and management within IoT ecosystems.

## Features
- **AES-128 Encryption**: Implemented AES-128 encryption for secure data transmission, enhancing protection against unauthorized access.
- **Communication Protocols**: Integrated MQTT and CoAP protocols to facilitate efficient and secure communication between IoT devices.
- **Performance Evaluation**: Conducted comprehensive performance evaluations on memory consumption and cycle count for the AES encryption implementation.
- **Key Management**: Developed key schedule management strategies for secure key generation and distribution.
- **Galois/Counter Mode (GCM)**: Integrated GCM with AES-128 to ensure confidentiality and integrity of data during transmission.

## Workflow
1. **Design Phase**:
    - Designed the secure SoC architecture, including the integration of AES encryption and communication protocols.
    - Defined the requirements for data integrity and security in the SensorTag system.

2. **Implementation**:
    - Developed the AES-128 encryption module and implemented GCM for enhanced security features.
    - Integrated MQTT and CoAP protocols for effective communication among IoT devices.

3. **Performance Evaluation**:
    - Conducted tests to evaluate memory consumption and cycle count of the AES implementation.
    - Documented performance metrics to assess the feasibility of using the SoC in resource-constrained environments.

4. **Initialization Vector (IV) Generation**:
    - Devised methods for generating valid initialization vectors to maintain data integrity in the publisher/subscriber system.

## Hardware & Tools
- **Raspberry Pi 4**: The primary hardware platform for developing and testing the secure SoC.
- **Programming Language**: Developed the software components using C/C++ and Python.
- **Encryption Libraries**: Utilized cryptographic libraries for implementing AES encryption and GCM.
- **MQTT & CoAP Libraries**: Integrated libraries to facilitate communication between IoT devices.

## Installation and Setup
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/TheMechanicHulk/Secure-SoC-IoT-Development.git
    cd Secure-SoC-IoT-Development
    ```

2. **Hardware Setup**:
    - Assemble the components as per the design specifications on a Raspberry Pi 4.
    - Connect required peripherals for testing communication and encryption functionalities.

3. **Software Configuration**:
    - Install necessary libraries for encryption and communication:
    ```bash
    sudo apt update
    sudo apt install libssl-dev mosquitto mosquitto-clients
    ```

4. **Run the Application**:
    - Start the IoT application with secure communication:
    ```bash
    python3 main.py
    ```

## Results
- The developed SoC successfully implemented AES-128 encryption, ensuring secure data transmission.
- Performance evaluations indicated optimal memory usage and cycle count, making it suitable for resource-constrained IoT devices.
- The integration of GCM with AES-128 enhanced data integrity and confidentiality, providing a reliable solution for IoT applications.

## Future Improvements
- **Scalability**: Explore scalability options for handling multiple IoT devices simultaneously.
- **Enhanced Key Management**: Develop more robust key management protocols for improved security.
- **Integration with More Protocols**: Investigate the integration of additional communication protocols for broader compatibility.

## File Structure
```bash
├── src/               # Contains source code and implementation files
├── docs/              # Documentation and design specifications
├── tests/             # Test scripts and performance evaluation results
└── README.md          # Project documentation
