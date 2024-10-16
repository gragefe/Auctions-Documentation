# Auction Platform Documentation

This repository serves as the **official documentation** for the auction platform, providing a detailed view of the design and architecture of services and APIs. The goal of this project is to supply the necessary documentation for developing and understanding the platform, including diagrams, a **Design System**, and a **Docker Compose** setup for easily configuring the local environment.

---

## 🎨 Design System

This project includes a **Design System** created to show the components and usability across the auction platform. 

![AuctionDesignSystemPreview](https://github.com/user-attachments/assets/78222dfb-dad3-4cd1-b462-1bf2d836c580)

You can import the file "Auction Platform Design System.drawio" in the https://draw.io/ to check it.

---

## 🔄 Sequence Diagrams

To explain the internal workings of the platform's APIs and services, we have some  **sequence diagrams**. These diagrams provide a view of the flow flow each system follow, showing how requests flow between application layers, domain model, and services.

![AuctionSequenceDiagramsPreview](https://github.com/user-attachments/assets/5ed58798-1daa-44e5-83a3-40d9b234a5a9)

You can import the file "Platform APIs Sequence Diagrams.drawio" in the https://draw.io/ to check it.

---

## 📂 Project Structure
```plaintext
├── Auctions-Runtime-Api       # Responsible for handling data in the context of the public auction portal.

├── Auctions-Vehicles-Api      # Responsible for handling the vehicle context
├── Auctions-Bids-Api          # Responsible for handling the auction context
├── Auctions-Api               # Responsible for handling the bidding context

├── Auctions-Vehicles-Service  # Responsible for handling vehicle context events
├── Auctions-Bids-Service      # Responsible for handling auction context events
└── Auctions-Service           # Responsible for handling bid context events
