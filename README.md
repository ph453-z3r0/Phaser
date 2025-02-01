# Phaser - A Stealthy LAN Access Tool (Prototype)

## Overview

**Phaser** is an advanced, stealthy tool designed for network access and control within a Local Area Network (LAN). Developed through the reverse engineering of various malware and virus samples, Phaser is a prototype that demonstrates the potential of fully undetectable (FUD) software. Its primary function is to provide seamless, covert access to systems within a LAN environment, bypassing traditional antivirus detection mechanisms.

Phaser operates in a client-server architecture, where the **Phaser.exe** (Client) is deployed on the target system, and the **Phaser_Controller.exe** (Controller) is used to manage and control the client remotely. This tool is designed for educational and research purposes, emphasizing the importance of understanding network security vulnerabilities.

---

## Key Features

- **Fully Undetectable (FUD):** Phaser is engineered to evade detection by all major antivirus software, making it a powerful tool for studying stealth techniques in cybersecurity.
  
- **LAN-Based Operation:** Phaser is currently optimized for Local Area Network environments, allowing for low-latency, high-speed access to connected systems.

- **Client-Server Architecture:** 
  - **Phaser.exe (Client):** Deployed on the target system, this component operates in stealth mode, ensuring minimal system footprint.
  - **Phaser_Controller.exe (Controller):** Used to remotely control and manage the client, providing a user-friendly interface for executing commands.

- **Covert Communication:** Phaser employs advanced encryption and obfuscation techniques to ensure that all communication between the client and controller remains undetected by network monitoring tools.

- **Prototype Status:** As a prototype, Phaser is a work in progress. It may contain bugs and issues, and user feedback is highly encouraged to improve its functionality.

---

## How It Works

Phaser leverages a combination of **polymorphic code**, **encrypted payloads**, and **network obfuscation** to remain undetected. The client component embeds itself into the target system's memory, avoiding traditional file-based detection. The controller communicates with the client using a custom protocol that mimics legitimate network traffic, ensuring that it blends seamlessly into the LAN environment.

### Key Technologies:
- **Polymorphic Engine:** Dynamically alters the client's code signature to avoid pattern-based detection.
- **AES-256 Encryption:** Secures all communication between the client and controller.
- **ARP Spoofing Detection Evasion:** Phaser avoids common LAN detection techniques like ARP spoofing by mimicking legitimate network behavior.

---

## Installation and Usage

### Prerequisites
- A Windows-based system (Client and Controller).
- Administrator privileges for installation.
- Both systems must be connected to the same LAN.

### Steps:
1. **Deploy Phaser.exe (Client):**
   - Run `Phaser.exe` on the target system. It will automatically embed itself into the system's memory and await commands from the controller.

2. **Run Phaser_Controller.exe (Controller):**
   - Launch `Phaser_Controller.exe` on your system. It will scan the LAN for active Phaser clients and display them in the interface.

3. **Control the Client:**
   - Select the target client from the list and execute commands remotely. The controller provides a range of options for system access and management.

---

## Disclaimer

**Phaser is intended for educational and research purposes only.** The developers do not condone or support the use of this tool for malicious activities. Unauthorized access to computer systems is illegal and unethical. Use Phaser responsibly and only in environments where you have explicit permission to do so.

---

## Known Issues and Bugs

As a prototype, Phaser may exhibit the following issues:
- Limited compatibility with non-Windows systems.
- Occasional instability in high-latency LAN environments.
- Potential false positives from advanced heuristic-based antivirus solutions.

If you encounter any bugs or have suggestions for improvement, please open an issue on the [GitHub repository](https://github.com/ph453-z3r0/Phaser) or contact me directly.

---

## Future Roadmap

- **WAN Support:** Expand Phaser's capabilities to operate over Wide Area Networks (WAN).
- **Cross-Platform Compatibility:** Develop versions for Linux and macOS.
- **Enhanced Stealth Features:** Integrate advanced techniques like rootkit functionality and kernel-level evasion.
- **User Interface Improvements:** Develop a more intuitive and feature-rich controller interface.

---

## License

Phaser is released under the **MIT License**.

---

## Contact

For inquiries, feedback, or collaboration opportunities, please reach out to:
- **Email:** ph453.z3r0@gmail.com
- **GitHub:** [ph453-z3r0](https://github.com/ph453-z3r0)

---

**Phaser - Redefining Stealth in Network Access.**  
*Use responsibly.*
