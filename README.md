# Send-DNSQuery
Performs an A record DNS query, using **System.Net.Sockets.Socket** and building a UDP packet.

*Why?*
In PowerShell 2 there was no way to direct your DNS query to a custom server. In PowerShell 3 and higher this was resolved when [Resolve-DNSName](https://technet.microsoft.com/en-us/library/jj590781%28v=wps.630%29.aspx) was introduced.

**NOTE**
This currently only sends the packet to the DNS server and does not retrieve a result. Will add in the support for retriving the result later.
