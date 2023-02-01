
## Install on Termux
### 1. Install debian 
Update and Upgrade repository
```bash
  pkg update && upgrade
```

Install proot-distro
```bash
  pkg install proot-distro
```
Install debian
```bash
  proot-distro install debian
```
Login debian
```bash
  proot-distro login debian
```
### 2. Install python 
```bash
  apt update && upgrade
```
```bash
  apt install python3.9 python3-pip dbus
```
### 3. Git clone
```bash
  apt install git
```
```bash
  git clone https://github.com/tenguproject/bot.git
```
```bash
  cd bot
```
```bash
  pip3 install -r requirements.txt
```
### 4. Running script
```bash
  python3 main.py
```
## Deeplink apk
Before installing you have to delete the original Gojek application
- [Click to download](http://tenguproject.com/assets/deeplink.apk)

## Screenshots

![App Screenshot](http://tenguproject.com/assets/gojek.png)

## Authors

- [@tenguproject](https://t.me/tenguproject)
