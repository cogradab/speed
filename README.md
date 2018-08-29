# speed
Enable the DS3231 RTC (RealTime Time Clock):
1. Append the modules file to /etc/modules using the command 'sudo cat modules >> /etc/modules'
2. Copy config.txt to /boot/config.txt. This will overwrite the existing config.txt. If this is a problem, you will nee$
3. Open the terminal and run the following commands:
        sudo apt-get -y remove fake-hwclock
        sudo update-rc.d -f fake-hwclock remove
4. Copy hwclock-set to /lib/udev/hwclock-set
Update .node-red folder:
5. Copy node red files to .node-red folder:
        mv /node-red/.node-red <home directory>/.node-red
Copy cripts to Desktop:
6. Copy the contents of the scripts directory to the Desktop.
  
