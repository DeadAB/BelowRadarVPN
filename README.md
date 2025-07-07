# 🎯 BelowRadar - Complete VPN Solution

#### 📦 What's Included:

1.   **Main Application** (src/belowradar.py) - 752 lines of production-ready Python code
2.   **Installation Scripts** - Automated setup and advanced configuration
3.   **Comprehensive Documentation** - README, project overview, and inline docs
4.   **Testing Suite** - Unit tests and interactive demo
5.   **Security Features** - Kill switch, DNS protection, leak detection

# 🚀 Key Features:

#### Core Functionality:
  1.  ✅ OpenVPN Integration - Full OpenVPN support with auto-configuration
  2.  ✅ Free VPN Servers - Built-in database of 5 free VPN providers
  3.  ✅ Auto Server Selection - Intelligent server selection based on ping/load
  4.  ✅ Command-Line Interface - Rich terminal interface with emojis and colors

#### Security & Privacy:
  1.  ✅ Kill Switch - Automatic traffic blocking if VPN drops
  2.  ✅ DNS Leak Protection - Custom DNS servers and leak prevention
  3.  ✅ IPv6 Support - Full IPv6 leak protection
  4.  ✅ WebRTC Leak Detection - Built-in leak testing
  5.  ✅ AES-256-GCM Encryption - Enterprise-grade encryption

#### Advanced Features:
  1.  ✅ Tor Integration - Optional Tor proxy for additional anonymity
  2.  ✅ Stealth Mode - Traffic obfuscation and evasion techniques
  3.  ✅ DNS over HTTPS - Encrypted DNS queries
  4.  ✅ Connection Monitoring - Automatic reconnection and health checks
  5.  ✅ Performance Optimization - Network tuning and optimizations

# 🎮 How to Use:


#### 1. Try the Demo (No root required):
```   
cd BelowRadar
python3 demo.py
```
#### 2. Install BelowRadar:
```
sudo ./install.sh
```
#### 3. Basic Usage:
```
1  sudo belowradar status          # Check status
2  sudo belowradar connect         # Connect to best server
3  sudo belowradar servers         # List servers
4  sudo belowradar test           # Test for leaks
5  sudo belowradar disconnect     # Disconnect
```
#### 4. Advanced Setup:
```
sudo ./scripts/setup_advanced.sh
```
# 🔧 Architecture:

#### The application is built with a modular architecture:
1.  **BelowRadarConfig** - Configuration management
2.  **NetworkManager** - Network operations and IP management
3.  **ServerManager** - VPN server database and selection
4.  **VPNConnection** - Connection management and OpenVPN integration
5.  **BelowRadar** - Main application class and CLI interface

# 🛡️ Security Features:

1.  ***Kill Switch:*** Automatic iptables rules to block traffic if VPN drops
2.  ***DNS Protection:*** Custom DNS servers (Cloudflare, Google) with leak prevention
3.  ***Leak Testing:*** Built-in tests for DNS, IPv6, and WebRTC leaks
4.  ***Tor Integration:*** Optional Tor proxy for enhanced anonymity
5.  ***Stealth Mode:*** Traffic obfuscation to bypass VPN blocking

# 📁 Project Files:
```
BelowRadar/
├── src/belowradar.py          # Main application (752 lines)
├── scripts/setup_advanced.sh  # Advanced security setup
├── install.sh                 # Main installation script
├── requirements.txt           # Python dependencies
├── README.md                  # Comprehensive documentation
├── LICENSE                    # MIT License
├── demo.py                    # Interactive demo
├── test_belowradar.py        # Unit tests
└── PROJECT_OVERVIEW.md       # Project summary
```

# 🎯 Built for Security Professionals:

#### This tool is particularly suited for:
1.    **Penetration Testers** - Secure connections during assessments
2.    **Security Researchers** - Anonymous research and data collection
3.    **Privacy Advocates** - Personal privacy and anti-surveillance
4.    **System Administrators** - Secure remote access
5.    **Anyone who values privacy and security**

#### BelowRadar is production-ready, feature-complete, and designed with security best practices. It includes everything you need for a professional VPN solution on Linux terminals.

#### Stay Below the Radar! 🕵️‍♂️
