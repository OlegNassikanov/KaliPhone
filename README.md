# 📱 KaliPhone

**KaliPhone** is a concept for a minimalist phone system built on Linux and ESP32, designed to prioritize privacy, simplicity, and user control.

No ads.  
No tracking.  
No bloat.  
Only tools for freedom, hacking, and learning.

---

## 🎯 Goals

- Build a phone OS based on Linux with CLI-first interface
- Use ESP32 as core controller or modem link
- Full transparency and auditability
- Educational value for cybersecurity and electronics

---

## 🧩 Components

- 🐧 Minimal Linux distro (e.g. Alpine, Kali NetHunter, TinyCore)
- 📶 ESP32 (WiFi/BLE + MCU + serial interface)
- 🔋 Power management (Li-ion + charging board)
- 🖥️ Display module (e-paper / LCD optional)
- 🧠 CLI apps only, no GUI bloat

See [`components.md`](./components.md)

---

## 🛠 Setup

Setup and build guide in [`kali_setup.md`](./kali_setup.md)

---

## 🔧 Tools

Essential tools and command-line utilities are listed in [`tools.md`](./tools.md)

---

## 🌌 Vision

See the broader vision and purpose behind the project in [`vision.md`](./vision.md)

---

## 📄 License

MIT — do whatever you want, but share improvements if you can.

---

## 👤 Author

**Oleg Nassikanov**  
Inspired by freedom, minimalism, and the old-school hacker spirit.
# 📱 KaliPhone: Minimalist Linux Device Inspired by Kali

**KaliPhone** is a privacy-focused, Linux-based pocket device for calls, communication, and network testing — fully under your control. Built from real, available parts and free of corporate telemetry.

---

## 🧱 Hardware (Modular & Accessible)

| Component                           | Description                                           |
|------------------------------------|-------------------------------------------------------|
| 📦 Pi Zero 2 W / Radxa Zero / Odroid Go Ultra | Compact ARM SBCs, Linux-compatible          |
| 📶 SIM7600 / EC25 / Quectel Modem  | GSM/3G/4G voice, SMS, and data                       |
| 📺 1.8" TFT or OLED Display        | Ultra-low-power screen                               |
| 🎙️ I2S Microphone + Speaker       | Audio interface                                       |
| 🔋 Li-Ion Battery + TP4056        | Power management & charging                          |
| 🔌 ESP32 (UART/I2C)                | Power-saving coprocessor, BLE, sensors               |
| ⌨️ Button matrix or touchscreen    | User input                                            |

---

## 💻 Software Environment

| Component                     | Purpose                                                |
|------------------------------|--------------------------------------------------------|
| 🐧 Kali ARM Mini / Debian Minimal | Lightweight Linux base                           |
| 🛡️ iptables + AppArmor        | Traffic filtering and process isolation              |
| 🕵️ Wireshark / tcpdump / aircrack-ng | Network sniffing and auditing tools         |
| 📶 ModemManager + NetworkManager | Mobile connectivity management                   |
| 📞 Linphone CLI / SIP tools  | Secure VoIP calls via SIP                           |
| 📩 Signal CLI / Matrix / NeoMutt | Encrypted messaging from terminal               |
| 🔍 nmap / hydra / metasploit  | Penetration testing & reconnaissance                |

---

## 🧠 Key Features

- 🔐 Full **root access**, complete system control
- 🚫 **No Google, no telemetry, no app store**
- 📴 Works **offline** in air-gapped environments
- 📡 Use as **WiFi sniffer**, BLE scanner, or GPS tracker
- 🔒 Includes **VPN**, **TOR**, and **Onion routing**
- ⚙️ Launch only whitelisted binaries, filter all traffic
- 🔍 Auto-detect **BLE beacons**, rogue WiFi, and signal leaks

---

## 🔗 Repository

[👉 GitHub – KaliPhone](https://github.com/OlegNassikanov/KaliPhone)