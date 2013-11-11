NDN Trace

This application is a browser based version of ndnx-trace.

Dependencies:

1. NDN-JS (Link: https://github.com/named-data/ndn-js)
2. The NDN daemon should be running ndn_traced in order for this utility to work.
(Link: https://github.com/named-data/ndnx-trace)

Description:

The NDN Trace is a browser based tool with traceroute like functionality for NDNx.
This tool is written using NDNJS library for troubleshooting problems in a network of ndnx
nodes. It can trace route to a certain NDN URI, e.g, ndn:/ndn/ucla.edu/apps/ping. 
The tool displays all routes to the namespace and problems in each route, if any. 
In this process, the tool bypasses the intermediate ndnx caches. 

Note: 

The browser must be able to connect to remote port 9696, which may not be enabled on 
some firewalls.




