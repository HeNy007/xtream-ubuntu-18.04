<h1>xtreamui_HeNy007</h1>
This is an installation mirror for xtream ui software.

<h1>How do I install?</h1>
#update your ubuntu first, then install panel

```
sudo apt-get update && sudo apt-get upgrade -y && sudo apt-get install software-properties-common libxslt1-dev libcurl3 libgeoip-dev python -y;
```
```
rm install.py; 
```
```
wget https://github.com/HeNy007/xtream-ubuntu-18.04/raw/master/install.py;
```
```
sudo python install.py
```

#If you want to install main server with admin panel, choose MAIN.
#If you want to install load balance on additional servers, add a server to panel in manage servers page, then run script and proceed with LB option.



