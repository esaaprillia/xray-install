# xray-install

Xray installation and configuraion script for **`Ubuntu`** and **`Debian`** servers.



## Features

- Automaticly install and configure [Xray-core](https://github.com/XTLS/Xray-core)
- Check exit code of every command that executed (No more nonsense errors).
- User Management with unique UUID/Password for each user
- VLess, VMess and Trojan Support
- XTLS for VLess and Trojan Support 
- VPS Basic settings for better experience
- Enable TCP BBR with [teddysun script](https://github.com/teddysun/across/blob/master/bbr.sh)
- Saving backups and bundle them in `.tar.gz` files for easy download.



## Usage

### Install Dependencies
```bash
apt update && apt install curl
```

### Run Script
```bash
bash -c "$(curl -L https://github.com/esaaprillia/xray-install/raw/main/xray.sh)"
```


## Supported protocols

1. [VLESS + WS + TLS](https://github.com/thehxdev/xray-examples/tree/main/VLESS-Websocket-TLS-s)
1. [VLESS + TCP + TLS](https://github.com/thehxdev/xray-examples/tree/main/VLESS-TCP-TLS-Minimal-s)
1. [VMESS + WS](https://github.com/thehxdev/xray-examples/tree/main/VMess-Websocket-s)
1. [VMESS + WS + TLS](https://github.com/thehxdev/xray-examples/tree/main/VMess-Websocket-TLS-s)
1. [VMESS + WS + Nginx](https://github.com/thehxdev/xray-examples/tree/main/VMess-Websocket-Nginx-s)
1. [VMESS + WS + Nginx + TLS](https://github.com/thehxdev/xray-examples/tree/main/VMess-Websocket-Nginx-TLS-s)
1. [VMESS + TCP](https://github.com/thehxdev/xray-examples/tree/main/VMess-TCP-s)
1. [VMESS + TCP + TLS](https://github.com/thehxdev/xray-examples/tree/main/VMess-TCP-TLS-s)
1. [Trojan + TCP + TLS](https://github.com/thehxdev/xray-examples/tree/main/Trojan-TCP-TLS-s)
1. [Trojan + WS + TLS](https://github.com/thehxdev/xray-examples/tree/main/Trojan-Websocket-TLS-s)

