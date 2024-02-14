# Private proxy setup tutorial - Kali Linux
Some institutions block certain websites, making it difficult to execute certain commands. (`apt update` I'm looking at you)<br>
A solution to this is to set up a private proxy and use that to reroute everything through a different service provider.<br>
This could also be done with a public proxy, but that's not advisable because people can see your original ip (proxies are not encrypted).
# Prerequisites 
- Kali Linux computer that will connect to the proxy *(this one is connected to the restricting institution wifi)*<br>
- Windows 10 computer that will be the private proxy server *(maybe your desktop at home - make sure your home ISP provider doesn't block websites you want to access.)*<br>
