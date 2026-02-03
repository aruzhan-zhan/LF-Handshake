# Lingua Franca Handshake (C++ Target)

This project implements a deterministic handshake protocol between two reactors using the [Lingua Franca](https://lf-lang.org/) coordination language.

## Overview
The project consists of two main components:
* **Source Reactor**: Sends a handshake string every 1 second based on logical time.
* **Sink Reactor**: Receives the string and prints a confirmation to the console.

## Environment & Tools
To build this project, the following environment was configured:
* **Target Language**: C++
* **Java**: OpenJDK 17 (Required for the `lfc` compiler)
* **Build System**: CMake 3.5+
* **Compiler**: MSVC (Visual Studio Build Tools 2026)

## How to Build and Run
1. Ensure the Lingua Franca CLI (`lfc`) is in your PATH.
2. Open a Developer Command Prompt (for MSVC access).
3. Navigate to the project root and run:
   ```bash
   lfc src/Handshake.lf
4. Run the executable:
   .\bin\Handshake.exe
