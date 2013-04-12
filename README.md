check_dnsbl
===========

a simple Nagios plugin to check whether your server is included in a DNSBL

It is quite common for outgoing SMTP servers to get listed in DNS black lists
like bl.spamcop.net. In order to know when this happens I wrote this simple
Nagios plugin, check_dnsbl.

Edit the file in order to include the blacklists you wish to monitor against.

http://blog.postmaster.gr/2006/10/16/check_dnsbl-a-simple-nagios-plugin/
