It's my fork from original RTL8192eu linux driver with support of Mercusys MW300UM.
Run these commands:

```
sudo apt-get install dkms build-essential git
git clone https://github.com/cyberkotov/mw300um-linux-driver.git
cd mw300um-linux-driver
sudo dkms add .
sudo dkms install rtl8192eu/1.0
sudo reboot
```




