# xrayr-reality
XRAYR + REALITY
Preferably on Debian/Ubuntu:

`bash <(curl -Ls https://raw.githubusercontent.com/therealaleph/xrayr-reality/main/install.sh)`

![image](https://github.com/therealaleph/xrayr-reality/assets/67456590/daab093c-d48e-462b-bf1b-8b754c21452f)

In V2Board: 
Add a V2Ray node, TCP connection with port 443

Link format:
vless://[**UUID**]@**[SNI DOMAIN]**:443?security=reality&sni=**[SNI DOMAIN]**&fp=chrome&pbk=[**PUBLIC KEY**]&sid=[**Short ID**]&type=tcp&flow=xtls-rprx-vision#**[Connection NAME] **

In case you want to build yourself (considering you have go > 1.20) from the [source](https://github.com/XrayR-project/XrayR):

`git clone https://github.com/XrayR-project/XrayR`\n
`cd XrayR/main`\n
`go mod tidy`\n
`go build -o XrayR -ldflags "-s -w"`\n
`./XrayR -config config.yml`\n
