# OS Page Replacement and Scheduling Algorithms

This repository contains C++ implementations of various Operating System page replacement and scheduling algorithms.

## Project Overview

This project demonstrates key OS concepts by simulating page replacement algorithms to manage memory frames effectively. It also includes CPU scheduling algorithms to illustrate process management.

The main file [`OS_Page_Replacement_Algo.cpp`](./OS_Page_Replacement_Algo.cpp) implements:

- Page Replacement Algorithms (e.g., FIFO, LRU, Optimal)
- Scheduling Algorithms (if included, specify here)

## Features

- Simulates how pages are replaced in memory frames using different algorithms.
- Calculates page faults and helps understand efficiency trade-offs.
- Provides a hands-on experience with classic OS algorithms in C++.

## Getting Started

### Prerequisites

- A C++ compiler (e.g., g++, clang)
- Basic knowledge of OS concepts (page replacement, CPU scheduling)

### How to Compile and Run

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
    ````

2. Compile the C++ program:

   ```bash
   g++ OS_Page_Replacement_Algo.cpp -o os_simulator
   ```

3. Run the executable:

   ```bash
   ./os_simulator
   ```

4. Follow the on-screen prompts to select algorithms and input page/reference strings or process details.

## Code Structure

* `OS_Page_Replacement_Algo.cpp` : Main program file implementing the algorithms.
