# OpenVPN Installation in AWS
1. [Refernce Video](https://www.youtube.com/watch?v=m-i2JBtG4FE&t=314s)
2. Now open admin gui. <ip>:943/admin
3. Configuration --> VPN Settings --> Routing 
    * Should VPN clients have access to private subnets (non-public networks on the server side)? **Yes, using Routing**
    * Specify the private subnets to which all clients should be given access (one per line):
        * Example: After connecting your device the IP address of the device is 172.27.224.2 then add 172.27.0.0/16 as a new line
    * Allow access from these private subnets to all VPN client IP addresses and subnets: **Yes**
4. Login to client web interface: <ip>:943
5. Download neccessary files
