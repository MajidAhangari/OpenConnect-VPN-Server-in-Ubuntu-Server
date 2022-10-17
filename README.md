# OpenConnect-VPN-Server-in-Ubuntu-Server
Anyconnect-VPN-Server in Ubuntu Server

Download and saving script on your server:

curl -O https://raw.githubusercontent.com/iw4p/OpenConnect-Cisco-AnyConnect-VPN-Server-OneKey-ocserv/master/ocserv-install.sh

Making script executable

chmod +x ocserv-install.sh

And then just run it:

./ocserv-install.sh

or

sudo bash ocserv-install.sh


in the nano /etc/ocserv/ocserv.conf  Set the number of devices a user is able to log in from at the same time. Default is 2. Set to zero for unlimited.

max-clients = 128

