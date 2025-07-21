# Banking System Simulation

A C++ console-based simulation of a banking system with file management and process scheduling.

## Features

- Account Management: Create, delete, view, and update accounts.
- Transactions: Deposit and withdrawal with balance updates.
- Token System: Simulates customer handling using scheduling algorithms (FCFS, Priority, SJF, RR).

## Technologies

- C++
- File System (C++17 `std::filesystem`)
- Multi-threading (`<thread>`, `<chrono>`)
- Standard Libraries: `<vector>`, `<queue>`, `<fstream>`, etc.

## Scheduling Algorithms

- **FCFS** (First Come First Serve)
- **Priority Scheduling**
- **SJF** (Shortest Job First)
- **RR** (Round Robin, Quantum = 20)

## Structure

- `Customer` struct holds transaction info.
- Modular functions handle UI, file I/O, and scheduling logic.

## Usage

Compile and run the code using any modern C++ compiler (C++17 or later).

