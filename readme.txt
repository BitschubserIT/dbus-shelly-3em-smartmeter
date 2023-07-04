wget https://github.com/BitschubserIT/dbus-shelly-3em-smartmeter/archive/refs/heads/main.zip
unzip main.zip "dbus-shelly-3em-smartmeter-main/*" -d /data
mv /data/dbus-shelly-3em-smartmeter-main /data/dbus
chmod a+x /data/dbus/shelly-3em-grid40/install.sh
chmod a+x /data/dbus/shelly-3em-pvinverter41/install.sh
chmod a+x /data/dbus/shelly-3em-pvinverter42/install.sh


/data/dbus/shelly-3em-grid40/install.sh
/data/dbus/shelly-3em-pvinverter41/install.sh
/data/dbus/shelly-3em-pvinverter42/install.sh
