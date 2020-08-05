 sudo vi /boot/config.txt
 
+enable_uart=1

$ sudo reboot

$ sudo pip install redis
$ sudo pip install getrpimodel

$ sudo mkdir -p /home/pi/LOG/
$ sudo python ./mh_z19.py
co2 = 453

co2    ||  board pin (Not GPIO)
vcc   =   4
gnd   =   6
tx    =  RXD0
rx    =  TXD0


-------------------------------------------------------------

https://qiita.com/revsystem/items/5a362e749ef80358e801

 sudo vi /boot/config.txt


diff --git 1/tmp/confifg.old 2/tmp/confifg.new
index 671312c..8cfe831 100644
--- 1/tmp/confifg.old
+++ 2/tmp/confifg.new
@@ -10,3 +10,4 @@ disable_overscan=0
 core_freq=250
 sdram_freq=400
 over_voltage=0
+enable_uart=1

$ sudo reboot


$ cd /tmp
$ sudo curl "https://bootstrap.pypa.io/get-pip.py" -o "get-pip.py"
$ sudo python get-pip.py
$ sudo pip install pyserial
$ sudo pip install redis

$ sudo pip install getrpimodel

$ git clone https://github.com/UedaTakeyuki/slider.git

$ cd slider
$ sudo mkdir -p /home/pi/LOG/
$ sudo python ./mh_z19.py
co2 = 453


co2    ||  board pin (Not GPIO)
vcc   =   4
gnd   =   6
tx    =  RXD0
rx    =  TXD0


 git init
 git add .
 git commit -m "first"
 git config user.email 
 git config user.name
 git remote add origin https://github.com/sotoedu/mh_z19Co2.git
 git push -u origin master

