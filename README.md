uniproxy
========

University Library Proxy Forwarder userscript

YOU NEED TO EDIT THE VARIABLE proxyname (SEE BELOW) WITH THE DOMAIN
FOR YOU INSTITUTIONS EZPROXY / LIBRARY PROXY IF YOU'RE NOT REGISTERED AT
Utrecht University in The Netherlands.

This script is intended to redirect websites of scientific journals through a
proxy website by appending the proxyserver address to the hostname. This will
only work if you have access to such a proxy with the correct credentials.
This work is very loosely based on the Library EZProxy forwarder by Andrew 
Perry, [http://userscripts.org/scripts/review/30220]. However this takes a 
radically different approach by modifying the current URL and leave the URL
rewriting to the proxyserver. If your proxyserver does not do that, add your 
proxyserver to the include-directives.
