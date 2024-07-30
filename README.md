
## Network Packet Analyzer

### Overview

This tool captures and analyzes network packets, displaying key information such as source and destination IP addresses, protocols, and payload data. It uses the Scapy library in Python to accomplish this. 

### Installation

To use this tool, you need to install the Scapy library. Install it using pip by running the following command in your terminal (e.g., in VS Code's integrated terminal):

```bash
pip install scapy
```

### Ethical Considerations

- **Educational Purposes Only**: This tool is intended for educational and debugging purposes.
- **Authorization**: Unauthorized packet sniffing or network analysis can be illegal and unethical. Ensure you have proper permissions and authorizations before using this tool.

### Customization

- **Packet Filters**: By default, the tool captures all IPv4 packets. You can modify the packet filter to capture specific types of packets. For example, to capture only TCP packets, you can adjust the filter parameter in the sniff function.

  For more information on packet filters and customization, refer to the [Scapy documentation](https://scapy.readthedocs.io/en/latest/).

### Running the Script

- **Linux/Mac**:
  Run the script with elevated privileges in the terminal:
  ```bash
  sudo python3 your_script_name.py
  ```

- **Windows**:
  Run the script with administrative privileges using Command Prompt or PowerShell.

