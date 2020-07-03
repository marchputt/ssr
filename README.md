# ssr
Quick note for setting up an SSR server

## Get started 
1. Get yourself a VPS. 
2. Make sure that ports you are going to use are opened. 
3. Install SSR. This note is based on a tutorial provided by [tipsforchina.com](https://www.tipsforchina.com/how-to-setup-a-fast-shadowsocks-server-on-vultr-vps-the-easy-way.html)

## SSR installation 
```
wget https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocksR.sh
chmod +x shadowsocksR.sh
./shadowsocksR.sh 2>&1 | tee shadowsocksR.log
```

## Recommended configuration 
- Password: testing
- Port: 443
- cipher: chacha20
- protocol: origin
- obfs: `http_simple_compatible` or (maybe better) `auth_sha1_v4_compatible`


