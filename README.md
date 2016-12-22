# xzmdns
c++ linux dns client; use this to test your dns server.
#download and make
git clone https://github.com/xzmAPP/xzmdns.git
#
cd ./xzmdns
#
make
#how to use it
./dnstest 
#input dns server address
Enter dns server : 114.114.114.114
#input Hostname to search
Enter Hostname to Lookup : google.com
#enter to see the result
Resolving google.com
Sending Packet...Done
Receiving answer...Done
The response contains : 
 1 Answers.
 0 Authoritative Servers.
 0 Additional records.


Answer Records : 1 
Name : google.com IPv4 address : 216.58.200.238

Authoritive Records : 0 

Additional Records : 0 
Resolving google.com.
Sending Packet...Done
Receiving answer...Done
The response contains : 
 1 Answers.
 0 Authoritative Servers.
 0 Additional records.


Answer Records : 1 
Name : google.com IPv6 address : 2404:6800:4008:800::200e

Authoritive Records : 0 

Additional Records : 0 





