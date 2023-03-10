
### INSTALL SCRIPT
<pre><code>apt-get update && apt-get upgrade -y && apt install -y wget screen && wget -q https://raw.githubusercontent.com/firdaus-rx/AutoScriptXray/main/setup && chmod +x setup && screen -S install ./setup</code></pre>

### TESTED ON OS 
- UBUNTU 20.04

### PORT INFO
```
- TROJAN WS 443
- TROJAN GRPC 443
- SHADOWSOCKS WS 443
- SHADOWSOCKS GRPC 443
- VLESS WS 443
- VLESS GRPC 443
- VLESS NONTLS 80
- VMESS WS 443
- VMESS GRPC 443
- VMESS NONTLS 80
- SLOWDNS 53, 5300
```

### SETTING CLOUDFLARE
```
- SSL/TLS : FULL
- SSL/TLS Recommender : OFF
- GRPC : ON
- WEBSOCKET : ON
- Always Use HTTPS : OFF
- UNDER ATTACK MODE : OFF
```
