# Multi-Node Relay Network Simulator with Onion Routing

A comprehensive Python-based simulator that demonstrates anonymous communication through onion routing principles similar to Tor networks. This educational tool implements multi-node relay communication with layered encryption for privacy protection.

## 🚀 Features

### Core Functionality
- **Multi-Node Network**: Configurable network with 4-6 interconnected nodes
- **Onion Routing**: Multi-layer encryption for anonymous communication
- **Packet Routing**: Direct and multi-hop message delivery
- **Real-time Monitoring**: Live statistics and network visualization
- **Dual Operation Modes**: Automated demonstrations and interactive control

### Technical Features
- **Asynchronous Operations**: Concurrent node communications using asyncio
- **Symmetric Encryption**: Fernet encryption for onion layers
- **Dynamic Topology**: Automatic neighbor discovery and routing
- **Comprehensive Logging**: Detailed packet tracking and statistics
- **Modular Architecture**: Extensible and maintainable codebase

## 📦 Installation

### Prerequisites
- Python 3.8 or higher
- pip package manager

### Installation Steps
1. Clone or download the project files
2. Install required dependencies:
```bash
pip install cryptography