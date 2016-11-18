PiPrintScan
===========

Use a raspberry pi as a printer and scanner server.

I’ve made one for a friend who is not a techie, so it needed to be easily
user-configurable.

I adapted a installer script which was initially uploaded by someone anonymous
called swe\_toast. I tend to test scripts first b4 uploading.

Took out some bugs, anadded upnp support and a configuration page for
cloudprint.

Setup your Pi with Raspbian Jessie Lite
<https://www.raspberrypi.org/downloads/raspbian/>

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
sudo su
apt-get update
apt-get upgrade
apt-get install git
git clone https://github.com/mikesmth/PiPrintScan.git
cd PiPrintScan
chmod 777 installer.sh
./installer.sh

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

###  
