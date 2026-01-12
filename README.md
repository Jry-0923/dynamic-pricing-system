# Intelligent Dynamic Pricing System (C++)

This project implements an intelligent dynamic pricing system in C++, 
designed to adjust prices based on demand-related signals and historical sales data.
The system focuses on modular pricing logic and empirical analysis of pricing strategies.

---

## Project Overview

Dynamic pricing is widely used in revenue management scenarios such as airline ticketing,
e-commerce, and online platforms.  
This project explores a rule-based pricing framework that reacts to demand signals
and evaluates system behavior under different pricing strategies.

The emphasis of this project is not only on implementation,
but also on **analyzing pricing behavior under varying assumptions**.

---

## Key Features

- Modular and extensible pricing logic
- Demand signal processing based on historical sales data
- Rule-based strategy design for price adjustment
- Empirical analysis of pricing outcomes under different strategies

---

## Project Structure
├── src/ # Core source code
├── include/ # Header files
├── sales_history.txt # Sample historical demand data
├── CMakeLists.txt # Build configuration
├── README.md

---

## Build and Run

### Build
```bash
mkdir build
cd build
cmake ..
make

## Run
./pricing_demo
