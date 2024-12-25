# Netty Messenger

**Netty Messenger** is a Java-based messaging application that uses TCP sockets for communication and RSA encryption to ensure secure message exchange. The project leverages the **Netty** library for efficient networking and includes features like encrypted key routing for enhanced security.

## Features
- **TCP Socket Communication**: Real-time communication between a Windows host and a Linux virtual machine.
- **RSA Encryption**: Ensures secure message exchange through public-key encryption.
- **Netty Library**: Provides an efficient, scalable, and non-blocking I/O framework for networking.
- **Encrypted Key Routing**: Routes encryption keys securely for added protection.

## Requirements
- JDK 11 or higher
- Maven
- Netty library

## Setup Instructions

### 1. Clone the repository:
```bash
git clone git@github.com:sonofsparda24/netty-messenger.git
cd netty-messenger
```

### 2. Build the project:

You can build the project using Maven:

```bash
mvn clean install
```

### 3. Run the application:

To run the application, use:

```bash
mvn exec:java
```


## How it works
- **Server**: A TCP server listens for incoming connections from clients.
- **Client**: A client connects to the server and sends/receives encrypted messages.
- **RSA Encryption**: Messages are encrypted using RSA before being sent and decrypted by the receiver.

## Contributing
Feel free to fork the repository, open issues, and submit pull requests. Contributions are welcome!

## License
This project is licensed under the MIT License - see the LICENSE file for details.
