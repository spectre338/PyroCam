# PyroCam

Install node.js from Adafruit:
curl -sLS https://apt.adafruit.com/add | sudo bash

sudo apt-get install node

Verify:
pi@raspberrypi ~ $ node -v
v0.12.0

Clone Latest PyroCam
git clone https://github.com/spectre338/PyroCam.git

Step into PyroCam
$cd PyroCam

Install Express, Socket.io and nconf

$ sudo npm install express socket.io nconf --save 
$ Sudo npm install

To install temporarily and not add it to the dependencies list, omit the --save option

$ sudo node index.js
