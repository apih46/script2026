```
AUTOSCRIPT XRAY

⚠️ System Requirements ⚠️
- Minimum 1GB RAM
- Debian10 above / Ubuntu20 above
- Recommended Debian for fast installation.
- Tested with VPS AWS, DigitalOcean, Vultr, GBcloud (Debian 11,12,13)

Setup:
```
apt update -y && apt upgrade -y && apt dist-upgrade -y && apt install -y screen wget curl && wget https://raw.githubusercontent.com/install/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
```

───────────────────────────────  
**SERVICES & PORTS**  
───────────────────────────────  

### XRAY SERVICES
- VMESS WS + TLS   : 443  
- VLESS WS + TLS   : 443  
- VMESS WS + NTLS   : 80 , 2052
- VLESS WS + NTLS   : 80 , 8080
- VLESS XHTTP + NTLS   : 80
- VLESS HTTPUpgrade + TLS   : 443  
- VLESS HTTPUpgrade + NTLS   : 80  

───────────────────────────────  
**SERVER INFORMATION & FEATURES**  
───────────────────────────────  

- Timezone   : Asia/Kuala_Lumpur (GMT +8)  
- Fail2Ban   : [ENABLED]  
- Dflate   : [ENABLED]  
- IPTables  : [ENABLED]  
- Auto-Reboot   : [ENABLED]  
- Daily Reboot Time  : 05:00 (GMT +8)  
- Auto Backup Data  : Yes  
- Restore Data   : Yes  
- Auto Delete Expired   : Yes  
- Full Orders Support   : Yes  

───────────────────────────────  
