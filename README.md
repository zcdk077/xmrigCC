# XMRIGCC
<a href=https://moneyblink.com/k6VT492G6xKR>Original Script</a>

# ANDROID SMARTPHONE

## Bahan-Bahan Mining
1. <a href=https://moneyblink.com/UhQzhTymk>Termux</a>
2. <a href=https://moneyblink.com/7kzerY1eXJx1>AutoStart Manager</a> <br><br>

# TUTORIAL TERMUX

## [ Install Update & Upgrade ]

```
yes | pkg update && pkg upgrade -y
```

## [ Install Builds ]

```
yes | pkg install wget nano
```

## [ Wget XMRigCC ]
```
wget https://github.com/zcdk077/xmrigCC/releases/download/3.4.3-dev/XMRigCC-3.4.2-Android-arm64.zip
unzip XMRigCC-3.4.2-Android-arm64.zip
rm -r XMRigCC-3.4.2-Android-arm64.zip
```

## [ Edit Wallet ]
```
nano config.json
```

## [ Start XMRigCC ]
```
./xmrigDaemon
```

## [ Autorun Mining ]

```
nano ../usr/etc/bash.bashrc
```

## [ Copy dan paste dibaris paling bawah ]

```
termux-wake-lock
clear
./xmrigDaemon
```

## Jika tidak mengerti tentang autorun bisa melewati langkah [ Autorun Mining ]
