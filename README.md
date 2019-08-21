creates a network namespace with openvpn and attaches a single application
usage:
`# vpn <your executable> <your parameters>`
Based on https://schnouki.net/post/2014/openvpn-for-a-single-application-on-linux/
All credits goes to /dev/schnouki

before executing this script:

`
# sudo su -
# mkdir -p /etc/netns/vpn
# echo 'nameserver 8.8.8.8' > /etc/netns/vpn/resolv.conf
# mkdir /etc/openvpn/config/
# copy ovpn config and auth files here 
# Change parameters in the file
`
