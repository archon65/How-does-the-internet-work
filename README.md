# How-does-the-internet-work
I will be going over how the internet works starting with dns

* DNS stands for Domain Name System what it does is converts human readable domain names (like: www.google.com) into Internet Protocol (IP) addresses (like: 173.194.39.78).

* IP stands for Internt protocal, An Internet Protocol address is a numerical label assigned to each device connected to a computer network that uses the Internet Protocol for communication. An IP address serves two principal functions: host or network interface identification and location addressing 

* Domain names  is a label that identifies a network domain: a distinct group of computers under a central administration or authority. Within the Internet, domain names are formed by the rules and procedures of the Domain Name System. Any name registered in the DNS is a domain name.

* A top-level domain is one of the domains at the highest level in the hierarchical Domain Name System of the Internet. The top-level domain names are installed in the root zone of the name space.
 So reading a webssite by TLD using www.google.com as an example, www. is the subdomain google is the second level domain and the TLD is .com
 
 * So explaining how a web server can respond to requests through HTTP by sending a file or generating a page dynamically through a server-side language
 
 When you type an address such as www.njit.edu into your browser, you are commanding it to open a TCP (Transmission Control Protocol) channel to the server that responds to that URL (Uniform Resource Locator), A URL is like your home address or phone number because it describes how to reach you.
 
 In this situation, your computer, which is making the request, is called the client. The URL you are requesting is the address that belongs to the server.
 
 Once the TCP connection is established, the client sends a HTTP ( Hypertext Transfer Protocol) GET request to the server to retrieve the webpage it should display. After the server has sent the response, it closes the TCP connection. If you open the website in your browser again, or if your browser automatically requests something from the server, a new connection is opened which follows the same process described above.
 
 