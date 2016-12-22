# VPN_server
Configure a private VPN server on ubuntu 16.04


#Guide to follow 
https://www.digitalocean.com/community/tutorials/how-to-set-up-an-openvpn-server-on-ubuntu-16-04

#Folder structure
-VPN_server
  -openvpn_server: contains all the file of the folder /etc/opevpn/ located on the server
  -openvpn_client: contains all the file of the folder /etc/openvpn/ located on the client
  
#Issues during installation
-Issue N.1
    firewall rules not installed correctly on the server with ufw (Uncomplicated Firewall)
-Issue N.2
    enable TCP/UDP/ICMP traffic on aws with the security group associated to the instance
-Issue N.3
    DNS problem. the VPN connection worked while it was still using the client DNS. 
    -solution
      
