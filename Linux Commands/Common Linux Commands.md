# Common Linux Commands
#linux #command_line

---

###### Network 
- `ip addr` - list all network interfaces and the associated IP address
- `ip route` - shows routing table of linux machine
- `ip route add <network_ip>/<cidr> via <gateway_ip>` - adds route to linux machine
- `ip route add <network_ip>/<cidr> via <gateway_ip> dev <network_card_name>` - adds route to linux machine with specific network card

###### File Operations Utilites
- `wget` - command allows us to download files from the web via HTTP
- `scp` - secure copy transfer files between hosts using ssh (format of SCP is just SOURCE and DESTINATION) eg. `scp important.txt ubuntu@192.168.1.30:/home/ubuntu/transferred.txt`

###### Serving files - WEB
- `python3 -m http.server` - to start a simple HTTP server

Another good lightweight HTTP server is [Updog](https://github.com/sc0tfree/updog)

###### Filesystem 
-`find` - command to find a specific file in the Linux filesystem eg. `find -name <filename>`

External sources:
- [IP commands in linux](https://phoenixnap.com/kb/linux-ip-command-examples)