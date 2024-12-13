## TCP Proxy
This TCP Proxy helps in understand protocols,modify traffic being sent to an application and create test cases for fuzzers.

### Libraries  Used
- socket
- sys 
- threading

### About 
TCP proxy has 4 different function .
 
 - hexdump - Display the communication between local and remote machines to console .
 - receive_from - Receive data from an incoming socket from either the local machine or remote machine .
 - proxy_handler - Manage the traffic direction between remote and local machine .
 - server_loop - Setting up a listening socket .

### Command Line 

./tcp_proxy [localhost] [localport] [remotehost] [remoteport] \[receive_first]

Example: ./tcp_proxy 127.0.0.1 9000 10.12.132.1 9000 True
