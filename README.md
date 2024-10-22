# Lab3_SDA

# Lab 3: Observer Pattern and Event Management System

## Overview
This project demonstrates the implementation of the Observer design pattern and an event management system in Java. It includes functionalities for file operations with various listeners that respond to events like opening and saving files.

## Features
- **Observer Pattern**: 
  - Implemented a basic Observer pattern allowing multiple observers to react to changes in a subject.
  - Observers include:
    - `BinaryObserver`: Displays file state in binary.
    - `OctalObserver`: Displays file state in octal.
    - `HexaObserver`: Displays file state in hexadecimal.
    - `LogOpenListener`: Logs open file operations to a specified log file.
    - `EmailNotificationListener`: Sends email notifications for file operations.
    - `SMSSupportListener`: Sends SMS notifications with a length check for messages.

- **Event Management System**:
  - Built an event manager that facilitates subscribing and notifying listeners of file events (`open` and `save`).
  - Listeners can be attached or detached dynamically.

## Structure
