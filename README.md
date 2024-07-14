 Packet Sniffer

A Python-based packet sniffer using Scapy to capture, analyze, and save network packets. This tool is useful for network monitoring, debugging, and educational purposes.

 Features

- **Capture Packets**: Sniffs packets from a selected network interface.
- **Protocol Analysis**: Analyzes IP, TCP, UDP, and ICMP packets.
- **Packet Storage**: Saves captured packets to a .pcap file.
- **User Interface**: Command-line interface to select network interfaces and control the sniffer.

 Requirements

- Python 3.x
- Scapy
- Keyboard

 Installation

1. Clone the Repository
    ```sh
    git clone https://github.com/yourusername/packet-sniffer.git
    cd packet-sniffer
    ```

2. Install Dependencies
    ```sh
    pip install scapy keyboard
    ```

 Usage

1. Run the Packet Sniffer
    ```sh
    python packet_sniffer.py
    ```

2. Select a Network Interface
    - The script will list all available network interfaces.
    - Enter the index of the interface you want to sniff on.

3. Start Sniffing
    - The sniffer will start capturing packets on the selected interface.
    - Press `Esc` to stop sniffing.

4. Captured Packets
    - The captured packets will be saved to `captured_packets.pcap` in the current directory.
