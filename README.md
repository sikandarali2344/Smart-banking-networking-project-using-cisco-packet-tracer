

# MyBank Smart Banking Infrastructure

## 📌 Project Overview

MyBank Smart Banking Infrastructure is a secure enterprise banking network simulation developed using **Cisco Packet Tracer**. The project demonstrates a real-world banking environment with **7 interconnected branches**, featuring automated services, wireless connectivity, and robust security measures.

---

## 👨‍💻 Author

| Name | Sikandar |
|------|----------|
| **Roll No** | 23BSCS44 |
| **Program** | Computer Science |
| **University** | Quaid-e-Awam University of Engineering, Science and Technology, Nawabshah |
| **Supervisor** | Ms. Sana Arain |
| **Event** | CS department Networking Competition 2026 |

---

## 🎯 Project Objectives

- Secure communication between all bank branches
- Automatic IP allocation using DHCP
- Domain name resolution through DNS
- Email communication among branch managers
- Wireless connectivity for smart devices
- Network perimeter protection using Cisco ASA Firewall
- Enterprise-level banking infrastructure simulation

---

## 🏗️ Network Topology

```
                        [Internet]
                            |
                    [Cisco ASA 5505 Firewall]
                            |
                      [Core Router]
                            |
        +---------+---------+---------+---------+---------+---------+
        |         |         |         |         |         |         |
    [Branch1] [Branch2] [Branch3] [Branch4] [Branch5] [Branch6] [Branch7]
        |         |         |         |         |         |         |
    [Switches, Access Points, End Devices]
```

---

## 📊 Branch Addressing Scheme

| Branch | Network Address | Gateway |
|--------|-----------------|---------|
| Branch 1 | 172.20.16.0/21 | 172.20.16.1 |
| Branch 2 | 172.20.24.0/21 | 172.20.24.1 |
| Branch 3 | 172.20.40.0/21 | 172.20.40.1 |
| Branch 4 | 172.20.56.0/21 | 172.20.56.1 |
| Branch 5 | 172.20.80.0/21 | 172.20.80.1 |
| Branch 6 | 172.20.112.0/21 | 172.20.112.1 |
| Branch 7 | 172.20.144.0/21 | 172.20.144.1 |

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **Cisco Packet Tracer** | Network Simulation |
| **EIGRP (AS 100)** | Dynamic Routing |
| **Cisco ASA 5505** | Firewall Security |
| **DHCP** | Automatic IP Allocation |
| **DNS** | Domain Name Resolution |
| **Email Server** | Internal Communication |
| **WPA2-PSK** | Wireless Security |
| **Access Points** | Wireless Connectivity |

---

## 📋 Services Implemented

### 1. DHCP Services
- Automatic IP address assignment
- Subnet mask, gateway, and DNS distribution
- IP range: 172.20.x.100 to 172.20.x.254

### 2. DNS Server
- IP: 172.20.0.48
- Records: mybank.com, mail.mybank.com, admin.mybank.com

### 3. Email Infrastructure
- Domain: mybank.com
- Admin: admin@mybank.com, security@mybank.com
- Managers: manager1@mybank.com to manager7@mybank.com

### 4. Wireless Infrastructure
- SSID: MyBankSecure
- Authentication: WPA2-PSK
- Devices: Tablets, Smartphones, Laptops

### 5. Firewall Security
- Cisco ASA 5505
- Access Control Lists (ACLs)
- NAT and Traffic Filtering

### 6. Dynamic Routing
- Protocol: EIGRP
- Autonomous System: 100

---

## 📂 Project Structure

```
MyBank-Infrastructure/
├── README.md
├── MyBank_Smart_Banking.pkt
├── Documentation/
│   ├── Project_Report.pdf
│   └── Presentation_Slides.pptx
├── Configurations/
│   ├── Routers_Config.txt
│   ├── Switches_Config.txt
│   └── Firewall_Config.txt
└── Screenshots/
    ├── Topology.png
    ├── DHCP_Testing.png
    ├── Email_Testing.png
    └── Dashboard.png
```

---

## 🧪 Testing & Verification

| Test | Status |
|------|--------|
| End-to-End Connectivity | ✅ Passed |
| DHCP IP Assignment | ✅ Passed |
| DNS Resolution | ✅ Passed |
| Email Communication | ✅ Passed |
| Wireless Connectivity | ✅ Passed |
| Firewall Security | ✅ Passed |
| EIGRP Routing | ✅ Passed |

---

## 🚀 Future Enhancements

- Virtual Private Networks (VPNs)
- Cloud Integration
- AI-Based Monitoring
- Biometric Authentication
- Advanced Threat Detection

---

## 📝 Conclusion

MyBank Smart Banking Infrastructure successfully demonstrates how Cisco technologies can be integrated to build a **secure, scalable, and manageable** banking environment. The project reflects practical enterprise networking concepts and highlights the importance of security, automation, and centralized administration in modern banking systems.

---

## 📧 Contact

**Sikandar**  
Email: [sikandarali@quest.edu.pk]  
Roll No: 23BSCS44  
University: QUEST Nawabshah



---

Let me know if you want any modifications!
