# Networking

## What is Networking

The process of connecting devices to exchange data and share resources. That is also called the Internet.

### Types of Networks

1. **WAN (Wide Area Network)** - Network in a wide area like a country.
2. **MAN (Metropolitan Area Network)** - Network in a city.
3. **LAN (Local Area Network)** - Network in a local area like a house.
4. **PAN (Personal Area Network)** - Small network that connects devices near a person.

## OSI & TCP/IP Model

### OSI Model (Open System Interconnection)

The OSI model is a conceptual framework for visualizing how data is transmitted across a network.

#### OSI Model Layers:

1. **Application Layer**
2. **Presentation Layer**
3. **Session Layer**
4. **Transport Layer**
5. **Network Layer**
6. **Data-Link Layer**
7. **Physical Layer**

### TCP/IP Model (Transmission Control Protocol/Internet Protocol)

The OSI model is never used in real life, but the TCP/IP model is used. It is a simpler version of the OSI model.

#### TCP/IP Model Layers:

##### 1. Application Layer
This is the first layer that combines the first three layers of the OSI model. From this layer, it is all planned how the data will be sent, whether it will be HTTP/HTTPS, SMTP, or FTP. All the transfer protocols are set in this layer.

##### 2. Transport Layer
This is the second layer that combines the fourth layer of the OSI model. It breaks the data into smaller parts and ensures that the data reaches the destination successfully.

###### Protocols in this layer:
- **TCP** - Ensures data is never lost and arrives correctly and in order.
- **UDP** - Sends data quickly but doesn’t check if everything arrived.

##### 3. Internet Layer
This layer decides the best route to deliver the data. It uses IP addresses to deliver the data.

##### 4. Network Layer
This is a hardware layer that includes two layers of the OSI model: Data-Link and Physical.