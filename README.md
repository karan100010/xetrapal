# Readme.md for xetrapal

## first clone the repository to your system :
```
git clone https://github.com/anandabhairav/xetrapal
```

## install the dependencies:
```
cd xetrapal/
sudo apt install build-essential python python-dev
sudo -H pip install -r requirements.txt
sudo -H pip install configparser
sudo -H pip install oauth2client
sudo -H pip uninstall telegram
sudo -H pip install -U python-telegram-bot

```
[Had to uninstall teleram first, look like this is related to](https://github.com/Tkd-Alex/Telegram-InstaPy-Scheduling/issues/13)

## create the symbolic link of the file in /opt directory:
```
sudo ln -s /home/<username>/xetrapal /opt/xetrapal

```
## In ipython:
```
import sys
sys.path.append("/opt/xetrapal")
import xetrapal
```
