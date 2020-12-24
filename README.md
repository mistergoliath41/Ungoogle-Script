# Ungoogle Script (No Root)
 Ungoogle your Android phone easily.
 
## Disclaimer
This script works even the phone is NOT rooted.

## Usage
To use this script you need to install ADB (Android Debug Bridge) on your PC.<br>
When ADB is installed, run this command:
```bash
adb shell "curl https://raw.githubusercontent.com/mistergoliath41/Ungoogle-Script/main/ungoogle.sh | sh"
```
If it does not works, download the script manually, launch a terminal where the script is located and try:
```bash
adb push ungoogle.sh /data/local/tmp
adb shell
cd /data/local/tmp
chmod 777 ungoogle.sh
sh ungoogle.sh
```