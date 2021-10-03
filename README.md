# RemoveDebianBloatware

```
#Libre
sudo apt-get remove --purge libreoffice* transmission-gtk thunderbird* -y
```

```
sudo apt remove celluloid pix Hypnotix drawing xfce4-dict hexchat simple-scan rhythmbox webapp-manager firefox -y
```

```
sudo apt-get clean
sudo apt-get autoremove
```

To Make it Headless
```
sudo su
update-rc.d -f xdm remove
apt-get remove --purge x11-common && apt-get autoremove
```
