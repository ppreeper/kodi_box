# kodi_box

## How to create a kodi box

Install a computer with the latest xubuntu LTS image (currently 16.04) and configure with default
* username: kodi
* password: kodikodi

Update computer and add requirements

```
sudo apt update
sudo apt full-upgrade
sudo apt install software-properties-common
sudo add-apt-repository ppa:team-xbmc/ppa
sudo apt update
sudo apt install kodi
```

Copy etc folder onto /etc

Copy home folder onto /home

Restart computer and enjoy

