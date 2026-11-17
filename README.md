<h1 align="center">TechAfresh VPN AIO Installer</h1>

<p align="center">
  Complete All-In-One VPN auto-installer and CLI management suite for Ubuntu (20.04 / 22.04 / 24.04 / 26.04+) and Debian (11 / 12 / 13+).
</p>
<p align="center">

<p align="center">
  <img src="https://img.shields.io/badge/DEBIAN_11-BULLSEYE-7952B3?style=for-the-badge&logo=debian&logoColor=white" alt="Debian 11" /><br>
  <img src="https://img.shields.io/badge/DEBIAN_12-BOOKWORM-7952B3?style=for-the-badge&logo=debian&logoColor=white" alt="Debian 12" /><br>
  <img src="https://img.shields.io/badge/DEBIAN_13+-TRIXIE-7952B3?style=for-the-badge&logo=debian&logoColor=white" alt="Debian 13+" /><br><br>
  <img src="https://img.shields.io/badge/UBUNTU_20.04-LTS-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" alt="Ubuntu 20.04" /><br>
  <img src="https://img.shields.io/badge/UBUNTU_22.04-LTS-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" alt="Ubuntu 22.04" /><br>
  <img src="https://img.shields.io/badge/UBUNTU_24.04-LTS-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" alt="Ubuntu 24.04" /><br>
  <img src="https://img.shields.io/badge/UBUNTU_26.04+-LTS-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" alt="Ubuntu 26.04+" />
</p>

---

<h2 align="center">Protocols</h2>

<p align="center">
  <img src="https://img.shields.io/badge/SSH-SLOWDNS-7952B3?style=for-the-badge&logo=cloudflare&logoColor=white" alt="SSH SlowDNS" /><br>
  <img src="https://img.shields.io/badge/SSH-WEBSOCKET-7952B3?style=for-the-badge&logo=cloudflare&logoColor=white" alt="SSH WebSocket" /><br>
  <img src="https://img.shields.io/badge/OPENVPN-TCP_/_UDP-2E8B57?style=for-the-badge&logo=openvpn&logoColor=white" alt="OpenVPN" />
  <img src="https://img.shields.io/badge/UDP-CUSTOM-2E8B57?style=for-the-badge&logo=linux&logoColor=white" alt="UDP Custom" /><br>
  <img src="https://img.shields.io/badge/XRAY-VMESS-E95420?style=for-the-badge&logo=cloudflare&logoColor=white" alt="XRAY Vmess" />
  <img src="https://img.shields.io/badge/XRAY-VLESS-E95420?style=for-the-badge&logo=cloudflare&logoColor=white" alt="XRAY Vless" /><br>
  <img src="https://img.shields.io/badge/XRAY-TROJAN-E95420?style=for-the-badge&logo=cloudflare&logoColor=white" alt="XRAY Trojan" />
</p>

---

<h2 align="center">Installation</h2>

### 1.

![Update & Upgrade Debian](https://img.shields.io/badge/Update_&_Upgrade_Debian_11,_12,_13+-7952B3?style=flat-square)

```bash
apt update -y && apt upgrade -y && update-grub && sleep 2 && reboot
```
or,

![Update & Upgrade Ubuntu](https://img.shields.io/badge/Update_&_Upgrade_Ubuntu_20.04_–_26.04+-7952B3?style=flat-square)

```bash
apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot
```

### 2.

![Install All Service VPN](https://img.shields.io/badge/Install_All_Service_VPN-7952B3?style=flat-square)

 **One Click Install Command**

```bash
bash <(curl -4sL https://vpn.techafresh.org.ng/install.sh)
```

---

## Service & Port

| Service | Port |
| :--- | :--- |
| **OpenSSH** | 22 |
| **Dropbear** | 109, 143 |
| **Stunnel4 SSL** | 443, 447, 777 |
| **SlowDNS** | 53 (UDP) |
| **SSH WS** | 80 (HTTP), 443 (TLS) |
| **OpenVPN TCP** | 443, 1194 |
| **OpenVPN UDP** | 53, 1195 |
| **UDP Custom** | 1-65535 |
| **BadVPN UDPGW** | 7100, 7200, 7300 |
| **XRAY Vmess TLS & Non** | 443, 80 |
| **XRAY Vless TLS & Non** | 443, 80 |
| **XRAY Trojan TLS & Non** | 443, 80 |
