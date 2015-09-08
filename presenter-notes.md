### Tools

Wireshark
* Packet Sniffer
* Powerful UI
* All OS's

tcpdump
* captures packets
* output can be read by wireshar
* sudo tcpdump -i eth0 -w capture

ngrep
* grep TCP, UDP and ICMP packets
* sudo ngrep -d eth1 -tq -W byline

--

### TCP and HTTP
 * OSI Layers: physical, data link, network, transport, session, presentation, application
 * TCP: Transport Later
 * HTTP: Application layer
 
 --
 
 ### Browsers
 * Use only GET and POST
 * e-tags
 * if-modified-since
 * cache-control
 
 ---
 
 ### Browser Samples
 
 * Get Request
 * Point out the TCP packet surrounding it
 * Hostname
 * Accepts
 * Accepts-encoding
 
 * Get Response
 * cache headers?
 * Content
 * Content-Type
 * Body
 
 * Post Request
 
 * Post Response
 * GZIP vs not gzipped
 
 * Post Image Request
 * enctype="multipart/form-data"

 
 