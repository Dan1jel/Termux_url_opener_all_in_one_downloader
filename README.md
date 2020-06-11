# All-in-one Download Script for Termux
All-in-one Download Script for Termux URL Opener
This script requires **ffmpeg, youtube-dl, python, wget** to function.

![screenshot.png](/screenshot.png)

# Using the script
Launch the "share" option and select Termux.

![share_icon.jpg](/share_icon.jpg)


# Installing the script
Launch Termux and run the follwing commands:
```
mkdir bin
#Installing dependencies
pkg update -y && pkg install wget -y && pkg install python -y && pkg install ffmpeg -y
yes | pip install youtube-dl

#Installing the script
wget -P "./bin/" --no-check-certificate "https://raw.githubusercontent.com/M3GABOY/Termux_url_opener_all_in_one_downloader/master/termux-url-opener" 
chmod +x "./bin/termux-url-opener"
termux-setup-storage
```
Or simply run this
```
wget --no-check-certificate "https://raw.githubusercontent.com/M3GABOY/Termux_url_opener_all_in_one_downloader/master/install.sh" && chmod +x install.sh && bash install.sh
```
# Adding cookies file for youtube-dl
Just put your cookies file at the home directory of Termux.

![cookies_screenshot.jpg](/cookies_screenshot.jpg)
