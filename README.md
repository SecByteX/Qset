# Qset
Qset Terminal Shortcut
This application is for Debian-based Linux operating systems. It supports both 64-bit and 32-bit machines. The primary purpose of this project is to facilitate long-term work through the terminal.



**NOTE:** [Please read the disclaimer at the end of this document. If you do not agree with these terms, please do not use this software](#Disclaimer)



## A. Specifications:
1. DNS changer:  You can change your dns setting easily with Free DNS Providers


## B. Installation
```bash
git clone https://github.com/secbytex/qset
```
```bash
cd qset
sudo chmod 755 qset/DEBIAN/
sudo chmod 644 qset/DEBIAN/control
```

```bash
sudo dpkg-deb --build qset qset.deb
sudo dpkg -i qset.deb
```



## C. Usage
i. With Command and Parameter
```bash
$ qset --help
QSet Terminal Shortcut - v0.1-dev

Usage:
  qset
  qset [command] [parameter]

Available Commands:
  dns      Change your dns server what you want


```

1. DNS
```bash
$ qset dns --help
QSet Terminal Shortcut - v0.1-dev

Usage:
  qset dns [param]

Available Parameters (required) :
  -cf      Cloudflare Free DNS Server: 1.1.1.1, 1.0.0.1
  -g       Google Free DNS Server: 8.8.8.8, 8.8.4.4
  -cd      Control D Free DNS Server: 76.76.2.0, 76.76.10.0
  -q9      Quad9 Free DNS Server: 9.9.9.9, 149.112.112.112
  -oh      OpenDNS Home: 208.67.222.222, 208.67.220.220
  -cb      CleanBrowsing: 185.228.168.9, 185.228.169.9
  -ad      AdGuard DNS: 94.140.14.14, 94.140.15.15
  -al      Alternate DNS: 76.76.19.19, 76.223.122.150

```

**Example Usage**
```bash
qset dns -cf
```

ii. Way 2 : with MENU
```bash
$ qset
```

# Source
- [https://www.lifewire.com/free-and-public-dns-servers-2626062](https://www.lifewire.com/free-and-public-dns-servers-2626062)

# Disclaimer
This software is provided for educational and informational purposes only. By using this project, you acknowledge that you are solely responsible for any changes made to your DNS settings and any potential risks associated with it.

The developer assumes no liability for any damage, loss of data, security vulnerabilities, or any other consequences resulting from the use or misuse of this software.

Use this tool at your own risk. Changing DNS settings may affect your internet connectivity, privacy, and security. It is recommended that you research and use trusted DNS providers.

By using this software, you agree that the developer is not responsible for any direct, indirect, incidental, or consequential damages arising from its use.

**If you do not agree with these terms, please do not use this software**
















