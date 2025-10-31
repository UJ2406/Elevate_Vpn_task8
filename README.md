# VPN Hands-On (Task 8)

## 📋 Task Overview

This project demonstrates setup and hands-on evaluation of ProtonVPN — using screenshots and real IP tests — to understand how VPNs protect privacy, mask your location, and provide secure internet communication.

---

## 🎯 Objectives

- Install, configure, and connect a free VPN service (ProtonVPN)
- Validate real IP masking and encrypted browsing
- Compare before/after VPN changes
- Summarize findings, best practices, and answer interview questions

---

## 🛠️ Tools Used

- ProtonVPN (Free)
- [whatismyipaddress.com](https://whatismyipaddress.com) for IP/geolocation check
- Wikipedia.org for safe browsing test
- Windows OS

---

## ⚙️ Detailed Steps and Observations

### 1. Download & Install ProtonVPN
- Downloaded official app from protonvpn.com.
- Installed and launched the app.

### 2. Account Creation & Sign-in
- Created a free ProtonVPN account (see screenshot below).
- Signed in securely.


---

### 3. Initial State: No VPN Connected
- Opened ProtonVPN client — “Unprotected” state displayed.
- Local IP: **49.36.214.26**, Country: **India**, ISP: **Jio**
- Connection before VPN activation.

     Verified on [whatismyipaddress.com]:  
      - City: Mumbai  
      - Region: Maharashtra  
      - ISP: Google LLC (Data Center/Transit)  
      - No VPN detected.

---

### 4. Connect to a VPN Server
- Clicked “Connect” in ProtonVPN (auto-selected “Fastest Free Server”).
- Connected successfully (status switched to **Connected**).
- Selected server in **United States/New York** (example for demo).

---

### 5. Verified IP and Location Change
- Refreshed [whatismyipaddress.com] after connection:
  - New IP: **181.214.131.54**
  - Location: **New York City, United States**
  - ISP: **Cyber Assets Fzco (VPN Server)**
  - Status: “Looks like you’re using a VPN!”
- My browsing traffic was now encrypted and routed through the US VPN server.

---

### 6. Browsed Wikipedia for Testing
- Accessed [Wikipedia.org] with VPN ON…  
  - Page loaded fine, no issues or restrictions observed.
  - Validates that encrypted tunnel works for normal browsing.

---

## 📝 Detailed Findings

- ProtonVPN setup is straightforward, with clean UI and instant connection.
- My real Indian IP and Jio ISP were hidden as soon as VPN connected.
- All websites saw only the New York VPN server and could not see my actual physical location.
- Wikipedia and other non-regional sites loaded without restriction on VPN.
- A slight drop in browsing speed was noticeable, but internet remained usable.
- Disconnecting the VPN immediately restored my real IP/location.

---

## 💡 Key Concepts Learned

- **What is a VPN?**  
  A VPN (Virtual Private Network) encrypts all internet traffic and routes it through a remote server, masking your real IP and enhancing privacy/security.

- **Privacy Protection:**  
  VPN prevents ISPs, government, local hackers, or public Wi-Fi snoopers from seeing your true online activity.

- **Encryption:**  
  Secures traffic between your device and the VPN server so outsiders can’t eavesdrop.

- **Limitations:**  
  You must trust the VPN provider. VPN may slow speeds and some services (like banking, streaming) can block known VPN IPs.

---

## 🗒️ Interview Questions & Answers

**1. What is a VPN?**  
A private, encrypted tunnel for your internet traffic routing via remote servers to hide your real IP—and protect against surveillance and eavesdropping.

**2. How does a VPN protect privacy?**  
It encrypts your traffic and masks your location, making sure websites and even your ISP can’t identify or track your true internet activity.

**3. VPN vs Proxy?**  
VPN encrypts all system traffic and spoofs your IP, while a proxy only routes specific app/browser data and doesn’t usually encrypt.

**4. Key VPN Benefits:**  
Privacy, secure browsing on public Wi-Fi, bypassing local restrictions, and protection from most ISP/third-party logs.

**5. Limitations:**  
Trust in provider, potential speed loss, and VPNs don’t prevent malware or phishing within the encrypted tunnel.

---

## 📂 Repository Structure Example

```
vpn-task8/
├── README.md          # This file 
├── screenshots/       # Demo images
└── findings.txt       # All the thinngs found 
```
