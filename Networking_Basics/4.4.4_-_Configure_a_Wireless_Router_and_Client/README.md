# Activity 4.4.4 - Configure a Wireless Router and Client

## 🎯Objectives
- Part 1: Connect the Devices
- Part 2: Configure the Wireless Router
- Part 3: Configure IP Addressing and Test Connectivity

## ⚙️ Router Configuration

| Setting | Value |
|---------|-------|
| **SSID (2.4GHz)** | `MyHome` |
| **Security Mode** | `WPA2-Personal` |
| **Passphrase** | `MyPassPhrase1!` |
| **DHCP Max Users** | `10` |
| **Admin Password** | `MyPassword1!` |
| **Router IP (Gateway)** | `192.168.0.1` |
| **DNS Server** | `209.165.200.230` |

## 💻 Device IP Addresses (via DHCP)

| Device | IP Address | Status |
|--------|------------|--------|
| Office PC | `192.168.0.2` | ✅ Connected |
| Laptop | `192.168.0.3` | ✅ Connected |
| Default Gateway | `192.168.0.1` | - |

## 📸 Execution Screenshots

| Step | Screenshot | Description |
|------|------------|-------------|
| 1 | ![Physical](prints/01_Network_Physical.jpg) | Physical topology view |
| 2 | ![Logical](prints/02_Network_Logical.jpg) | Logical topology with skillsforall.srv server |
| 3 | ![Office Config](prints/03_Desktop_Office_Configuration.jpg) | Office PC - DHCP enabled, IP received |
| 4 | ![Laptop Config](prints/04_Laptop_Configuration.jpg) | Laptop - IP configuration via DHCP |
| 5 | ![Router Wireless](prints/05_Router_Wirelles_Configuration.jpg) | Router - SSID "MyHome" configured |
| 6 | ![Laptop Connect](prints/06_Laptop_Wirelles_Connection_Successful.jpg) | Laptop - Successfully connected to access point |
| 7 | ![Laptop Status](prints/07_Laptop_Wirelles_Configuration.jpg) | Laptop - Wireless network status (IP: 192.168.0.3) |
| 8 | ![Office Test](prints/08_Desktop_Office_Test_Skillsforall_srv.jpg) | Office PC - Accessing skillsforall.srv ✅ |
| 9 | ![Laptop Test](prints/09_Laptop_Test_Skillsforall_srv.jpg) | Laptop - Accessing skillsforall.srv ✅ |
| 10 | ![TV](prints/10_TV_ON.jpg) | TV - Connected and working |

## ✅ Connectivity Tests

| Test | Result |
|------|--------|
| Office PC → skillsforall.srv | ✅ Successful |
| Laptop → skillsforall.srv | ✅ Successful |
| TV Service | ✅ Working |

## 🎯 Status

- [x] **Part 1:** Connect the Devices (coaxial + Ethernet cables)
- [x] **Part 2:** Configure the Wireless Router (SSID, Security, DHCP)
- [x] **Part 3:** Configure IP Addressing and Test Connectivity

## 📝 Notes

- DNS Server used: `209.165.200.230`
- All devices received IP addresses via DHCP from `192.168.0.1`
- Wireless security: WPA2-Personal with passphrase
- TV connected via coaxial splitter for video service

---
*Activity completed: April 2026*  
*Cisco Networking Basics Course*
