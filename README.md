Shelly Pro EM into Victron DBUS
based on: https://github.com/funkmaster86/dbus-shelly-pro-3em-smartmeter

THIS IS WORKING NOW, BUT I GIVE NO GUARANTEE THAT IT IS WORKING CORRECTLY(!)

Please create an issue if you experience any problems.
At the moment the script assumes that the pvinverter is attached to L1

Installation:
```
wget https://github.com/stenub/dbus-shelly-pro-em-smartmeter/archive/refs/heads/main.zip
unzip main.zip "dbus-shelly-pro-em-smartmeter-main/*" -d /data
mv /data/dbus-shelly-pro-em-smartmeter-main /data/dbus-shelly-pro-em-smartmeter
chmod a+x /data/dbus-shelly-pro-em-smartmeter/*.sh
/data/dbus-shelly-pro-em-smartmeter/install.sh
rm main.zip
```
