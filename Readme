# Warehouse Management System — CSCI 430

A console-based Java application developed as a Group 8 project for CSCI 430 at St. Cloud State University.

The application manages clients, product inventory, wishlists, orders, shipments, invoices, and payments using an object-oriented design.

## Features

- Add clients and products with automatically generated IDs.
- View product inventory and client account balances.
- Add products to client wishlists.
- Place orders and fulfill available quantities.
- Waitlist quantities that cannot be fulfilled immediately.
- Receive shipments and fulfill outstanding waitlist requests.
- Generate invoices and record client payments.
- Run a test walkthrough with checks for expected warehouse behavior.

## Repository Structure

| Location | Description |
|---|---|
| `Group8 Project Final/` | Group 8 warehouse application and test driver. |
| `LibraryFinal/` | Original library sample code included with the course repository. |

## Requirements

A Java Development Kit (JDK), with `java` and `javac` available in your terminal.

No third-party libraries are required for the warehouse application.

## Compile and Run

From the repository root, enter the warehouse application folder and compile its source files:

```bash
cd "Group8 Project Final"
javac *.java
```

Start the console interface:

```bash
java UserInterface
```

Follow the numbered menu. Enter `12` to display help or `0` to exit.

Compile the warehouse application separately from `LibraryFinal`, since the folders contain separate applications.

## Test Walkthrough

After compiling, run:

```bash
java WarehouseTest
```

The walkthrough creates sample clients and products, places orders, records payments, and receives a shipment. It checks wishlist clearing, waitlist fulfillment, inventory quantities, invoices, and account balances.

If all included checks pass, it prints:

```text
All warehouse behavior checks passed.
```

## Main Classes

- `Warehouse`: Coordinates warehouse operations.
- `Client` and `Product`: Represent clients and inventory.
- `ClientList` and `ProductList`: Manage collections and IDs.
- `WishListItem` and `WaitListItem`: Track requested and unfulfilled quantities.
- `Order` and `Transaction`: Record orders, charges, and payments.
- `UserInterface`: Provides the console menu.
- `WarehouseTest`: Runs the behavior-check walkthrough.

## Attribution

This repository is a fork of [KanishkaWijeratne/430Project1Final](https://github.com/KanishkaWijeratne/430Project1Final), which includes course sample code.

The warehouse application is located in `Group8 Project Final/`.
