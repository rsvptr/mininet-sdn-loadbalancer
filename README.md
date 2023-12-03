# Overview

This repository provides a comprehensive suite for exploring load balancing in Software Defined Networks (SDN) using Mininet, a network emulator. The project includes simulations for both Star and Tree topologies, implementing a round-robin load balancer. It's an ideal resource for understanding the impacts of load balancing in SDNs.

## Features
- **Simulations of Star and Tree Topologies**: Detailed Mininet scripts for setting up both topologies.
- **Round-Robin Load Balancing**: Implementation of the round-robin algorithm for efficient load distribution.
- **Performance Analysis Tools**: Scripts to analyze and compare the performance under various scenarios.
- **Client-Server Interaction**: Custom client and server scripts for realistic network traffic simulation.

## Project Structure
- `client.py`: Client implementation sending HTTP GET requests to the load balancer.
- `loadBalanceNode.py`: Load balancer implementation with round-robin algorithm.
- `localClient.py`: Local client script for base test scenarios.
- `plot.py`: Visualization tool for performance results.
- `server.py`: Simple HTTP server setup.
- `starTopo.py`: Script for setting up a Star topology network.
- `treeTopo.py`: Script for setting up a Tree topology network.
- `miniedit.py`: GUI tool for creating network topologies in Mininet.
- `tests.py`: Functions for running various test scenarios.

## Scenarios
- **Base Test**: Measures base performance without load balancing.
- **Load Test**: Simulates high-load situations without load balancing.
- **Balance Test**: Evaluates performance with round-robin load balancing.

## Requirements
- Ubuntu 18.04
- Python 2
- Mininet
- MiniEdit

## Getting Started
To get started with the simulations:
1. Clone the repository.
2. Install Mininet and Python dependencies.
3. Run `miniedit.py` to set up the network topology.
4. Execute `starTopo.py` or `treeTopo.py` with the desired test arguments.
5. Use `plot.py` to visualize the performance results.

## Further Information
For a detailed overview and theoretical background of the project, refer to the presentation provided in the repository in PDF format. It offers insights into the design, methodology, and results of the simulations.
