# Setup Client
## Windows and Linux.
* Install the installers downloaded 
## Linux
* Install **openvpn3** follow the instruction here: https://openvpn.net/cloud-docs/openvpn-3-client-for-linux/
* Require **.ovpn** file from client web interface
* `openvpn3 config-import --config client.ovpn`
* `openvpn3 session-start --config client.ovpn`
This will establish the connection to vpn
