<br />
CMPN OpenVPN Installation and Manager script by Cong Minh Vuong
<br />
### OS Support
*(Ubuntu 20.04 LTS recommend)*
- Ubuntu 18.04 LTS | Ubuntu 20.04 LTS
- Debian 10 | Debian 11
- CentOS 7 | (With SELinux Disabled)
- CentOS 8 or Almalinux Rocky Linux | (With SELinux Disabled)

### I. Automated install V1 (For Ubuntu and Debian Server with Public IP)

*Warning: Please update and upgrade your OS to latest before install*

**a) Install with command:**

*Need Root Permissions, not Sudo*

```bash
bash <(curl https://raw.githubusercontent.com/minhvip20956/cmpn-as/main/vpn.sh || wget -O - https://raw.githubusercontent.com/minhvip20956/cmpn-as/main/vpn.sh)
```
You will need to provide information during installation. Please follow the instructions.

**b) Manager Script**

Just with the following simple command. Every component you need is built-in.

```bash
cmvpn
```

## Good Luck!!!
