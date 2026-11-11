# Task-
* Explaining basic network types and concepts, observe network lookup and connectivity information, and describe what happens when a website opens.

## 7.1 Concepts of Network
|**Concept**|**Explaining what it does**|**Example**|
| :--- | :--- | :--- |
|**LAN**| A network covering a small area, such as a home, lab, or office.|WIFI-router of college,home router.|
|**MAN**|A network covering a city or large campus area.|My college networks connected across different buildings across the campus.|
|**WAN**|A network covering large geographical areas.|The global internet connecting the networks acroos the world.|
|**DNS**|Translates a domain name into an IP address.|Turning a domain-name like example.com to its numeric IP-Address|
|**Router**|Connects networks and forwards data between them.|the WIFI-router at home connecting my devices to the internet.|
|**Protocol**|A set of rules devices follow to communicate.|HTTP/HTTPS for loading a webpage.|
|**Packet switching**|Data is divided into packets that travel across a network|sending an email in small data pieces.|
|**Client-server**|A client requests a service and a server provides it.|My web browser (client) requesting a page from web server.|


## 7.2  Observing network information-

**what a connectivity test helps you check**:  (ping)

* It helps me to check whether my computer is able to reach other computer or networks and also helps in measuring how fast a data travels back and forth.

**what information a DNS lookup displays**:  (ns lookup website.com)

* It displays the name of the website ,The IP address of the website and also it displays the DNS server it used to search.

**=>**: 
        Server:     2401:4900:c960:8831::9d
        
        Address:	2401:4900:c960:8831::9d#53
        
        Name:	example.com
        
        Address: 104.20.23.154


**the role of DNS when you enter a website name in a browser**:

* So when i type website name in a browser,DNS is like a phonebok which searches for the website's IP address so that many computers know where to connect.


## 7.3  What happens when you open a website?

* I type the website address on my web browser which is the client.
* then the DNS will search for the required Numeric IP Address for that specific web address.
* Once the IP address is found,my local computer sends a request using my local "**Router**" into the internet.
* The request travels through standard communication Protocols (like,**HTTP,HTTPS**)
* The website server then receives the request and then it processes it and sends the output web pages in small packets of data.
* The browser collects these small packets of data then put them all together and displays the web page on my screen.


## Newtwork tools-

* **ping -c 4 example.com** -
-> It checked the connectivity to that website d response time.


* **nslookup example.com** - 
->  It showed me the Web server address,Name of the website and the IP address of tht website.


