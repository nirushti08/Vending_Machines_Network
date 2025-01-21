# Vending Machines’ Network

This repository contains the project details for the **Vending Machines’ Network**, completed as part of the Semester 6 EN3251 - Internet of Things module. The project focuses on creating a connected network of vending machines to improve inventory management, customer convenience, and operational efficiency using IoT technologies.

---

## Project Overview

The Vending Machines’ Network connects vending machines in a **star topology** to a central server. The system enables:
- **Real-time monitoring** of product availability and machine status.
- **Customer convenience** with features like:
  - Viewing nearby vending machines.
  - Checking product availability.
  - Adding products to a cart and purchasing.
- **Company benefits** such as:
  - Notifications for low inventory.
  - Resupply scheduling.
  - Analysis of sales trends for informed decision-making.

---

## Project Architecture

- **Communication Protocol**: MQTT (Message Queuing Telemetry Transport) is used for publisher-subscriber communication between vending machines and the central server.
- **Data Format**: Messages are transmitted as JSON strings.
- **Hardware Implementation**: A prototype vending machine is built using:
  - ESP32 development board.
  - OLED display (128×64).
  - Push buttons for user interaction.

---

## Implemented Functionalities

### Customer Features:
1. **Main Menu**: Provides options to:
   - Buy products.
   - View nearby vending machines.
   - Check product availability across locations.
2. **Buy Products**:
   - View updated product details (price and quantity).
   - Add products to the cart after setting the desired quantity.
3. **Cart View**:
   - Review selected products, subtotal, and total before purchase.
   - Proceed with purchase or clear the cart.
4. **Nearby Locations**:
   - View vending machines ordered by proximity.
   - Check product availability in selected machines.
5. **Product Availability**:
   - View availability of specific products across all vending machines.

### Administrative Features:
1. **Central Server Interface**:
   - Monitor product inventory and machine status.
   - Schedule resupply routines based on alerts for low inventory.
   - Update product prices and synchronize changes across all vending machines.
2. **Hidden Interface for Operators**:
   - Update product quantities during resupply, synchronized with the central server.

---

## Functionality

### Vending Machine’s User Interface:
- Allows customers to browse products, add items to the cart, and make purchases.
- Displays product availability and location details for nearby vending machines.

### Server User Interface:
- Provides administrators with real-time data on inventory and sales.
- Includes features for resupply scheduling, price updates, and notifications for low inventory.

### Communication:
- **MQTT Broker**: Handles communication between vending machines and the server.
- JSON objects are used for efficient data transmission and processing.

---

## Development Tools
- **Hardware**: ESP32, OLED display, push buttons.
- **Software**:
  - MQTT for communication.
  - Node-RED for server-side automation.
  - Python for backend processing.

---

## Links
- [Video Link](https://uniofmora-my.sharepoint.com/:f:/g/personal/kurrshanthv_20_uom_lk/EpO2s3Vqid1CmBEF5DsZCtUB-zmbeyEU9zS9G8x6z_9DNQ?e=aLq2EW)

---

This project demonstrates how IoT can enhance operational efficiency and user experience for vending machine networks, paving the way for smarter retail solutions.
