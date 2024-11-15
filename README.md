# Hello World MassTransit

📚 A repository to explore and learn **[MassTransit](https://masstransit-project.com/)**, a popular .NET library for building message-based distributed systems.

---

## Overview

This repository provides a beginner-friendly introduction to **MassTransit**, focusing on its core features and practical use cases, including:

- Implementing message-based communication in .NET applications.
- Exploring the use of brokers like RabbitMQ and Azure Service Bus.
- Understanding patterns such as in-memory messaging and the outbox pattern.

MassTransit simplifies integration with message brokers and promotes a clean architecture for distributed systems.

---

## Features

- **Beginner-Friendly Examples**:
  - Includes an easy-to-follow **Hello World** implementation.
  - Demonstrates the use of MassTransit with various transports (e.g., In-Memory, RabbitMQ, Azure Service Bus).

- **Practical Patterns**:
  - Shows how to implement essential patterns like the **Outbox Pattern**.
  - Utilizes popular data stores like **Entity Framework Core** and **MongoDB**.

- **Extensible Setup**:
  - Provides a foundation to build and expand MassTransit-based projects.

---

## Getting Started

Follow these steps to set up and run the project locally.

### Prerequisites

- Install the [.NET SDK](https://dotnet.microsoft.com/download) (version 6.0 or higher recommended).
- Ensure RabbitMQ or Azure Service Bus is available if testing those configurations.

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/GuilhermeStracini/hello-world-masstransit.git
   cd hello-world-masstransit
   ```

2. **Restore Dependencies**:
   ```bash
   dotnet restore
   ```

3. **Run the Application**:
   ```bash
   dotnet run
   ```

4. **Explore the Code**:
   - Check the implementation of message producers, consumers, and broker configurations.
   - Modify the transport configuration (e.g., switch from In-Memory to RabbitMQ) as needed.

---

## Useful Links

Expand your learning with these resources:

- [MassTransit with In-Memory in .NET Core](https://blog.devops.dev/masstransit-with-in-memory-in-net-core-52988ae1e987)
- [MassTransit with RabbitMQ and Azure Service Bus](https://blog.devops.dev/masstransit-with-rabbitmq-and-azure-service-bus-in-net-1b38a28e84f1)
- [.NET Core with RabbitMQ and MassTransit](https://medium.com/@david.bytyqi/net-core-8-with-rabbitmq-and-masstransit-77899c27fd79)
- [Use MassTransit to Implement Outbox Pattern with EF Core and MongoDB](https://medium.com/codex/use-masstransit-to-implement-outbox-pattern-with-ef-core-and-mongodb-f0ce3b4cf0b1)
- [Official MassTransit Documentation](https://masstransit-project.com/documentation/)

---

## Contribution

Contributions are welcome!  
Feel free to fork this repository, open issues, or submit pull requests to add examples, fix bugs, or improve documentation.

---

## License

This project is licensed under the [MIT License](LICENSE).
