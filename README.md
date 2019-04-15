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
 
 * Internet routing is done by a router, a router connects devices within a network by forwarding data packets between them. This data can be sent between devices, or from devices to the internet. The router does this by assigning a local IP address to each of the devices on the network.
 
 * HTTP and HTTPS as well as port 80 and port 443 
 
 HTTP sends data over port 80 and HTTPS uses port 443. No encryption in HTTP, with HTTPS the data is encrypted before sending. HTTP works at the application layer, while HTTPS operates at the transport layer. HTTP URL in your browser's address bar is HTTP:// and the HTTPS URL is HTTPS://.
 
 * REST (Representational state transfer) is a software architectural style that defines a set of constraints to be used for creating Web services. Web services that conform to the REST architectural style, termed RESTful Web services, provide interoperability between computer systems on the Internet.
 
 * Roy Fielding's dissertation elaborates the Representational State Transfer (REST) architectural style for distributed hypermedia systems, describing the software engineering principles guiding REST and the interaction constraints chosen to retain those principles, while contrasting them to the constraints of other architectural styles. REST is a hybrid style derived from several of the network-based architectural stylesand combined with additional constraints that define a uniform connector interface.
 
 # Linux commands
 
 * Cd is used to change directory to the current working directory so if I am if I open my program on my home computer i will most likely be on my home directory if I use cd and type cd images as long as that is a directory in my pc I will no longer be in home but in images.
 
 * Ls is used to see any files in a current directory so if you cd images and ls after you should see the img in your computer
  
  * How to edit a file in VI,To open a file in the vi editor to start editing, simply type in 'vi <filename>' in the command prompt. To quit vi, type one of the following commands in the command mode and press 'Enter' to exit and save type  press Esc and then : (the colon). The cursor will go to the bottom of the screen at a colon prompt. Write your file by entering :w and quit by entering :q . You can combine these to save and exit by entering :wq .
   
   * ownwership and giving permissions on files. If you wanted to add or remove permissions to the user, use the command “chmod” with a “+” or “–“, along with the r (read), w (write), x (execute) attribute followed by the name of the directory or file.
   
   # UNIX 
   * In 1969-1970, Kenneth Thompson, Dennis Ritchie, and others at AT&T Bell Labs began developing a small operating system on a little-used PDP-7. The operating system was soon christened Unix, a pun on an earlier operating system project called MULTICS. In 1972-1973 the system was rewritten in the programming language C, an unusual step that was visionary: due to this decision, Unix was the first widely-used operating system that could switch from and outlive its original hardware. Other innovations were added to Unix as well, in part due to synergies between Bell Labs and the academic community. In 1979, the “seventh edition” (V7) version of Unix was released, the grandfather of all extant Unix systems.
     
     After this point, the history of Unix becomes somewhat convoluted. The academic community, led by Berkeley, developed a variant called the Berkeley Software Distribution (BSD), while AT&T continued developing Unix under the names “System III” and later “System V”. In the late 1980’s through early 1990’s the “wars” between these two major strains raged. After many years each variant adopted many of the key features of the other. Commercially, System V won the “standards wars” (getting most of its interfaces into the formal standards), and most hardware vendors switched to AT&T’s System V. However, System V ended up incorporating many BSD innovations, so the resulting system was more a merger of the two branches. The BSD branch did not die, but instead became widely used for research, for PC hardware, and for single-purpose servers (e.g., many web sites use a BSD derivative).
     
   # Linux
     
    * In 1991 Linus Torvalds began developing an operating system kernel, which he named “Linux” [Torvalds 1999]. This kernel could be combined with the FSF material and other components (in particular some of the BSD components and MIT’s X-windows software) to produce a freely-modifiable and very useful operating system. This book will term the kernel itself the “Linux kernel” and an entire combination as “Linux”. Note that many use the term “GNU/Linux” instead for this combination.
      
      In the Linux community, different organizations have combined the available components differently. Each combination is called a “distribution”, and the organizations that develop distributions are called “distributors”. Common distributions include Red Hat, Mandrake, SuSE, Caldera, Corel, and Debian. There are differences between the various distributions, but all distributions are based on the same foundation: the Linux kernel and the GNU glibc libraries. Since both are covered by “copyleft” style licenses, changes to these foundations generally must be made available to all, a unifying force between the Linux distributions at their foundation that does not exist between the BSD and AT&T-derived Unix systems. This book is not specific to any Linux distribution; when it discusses Linux it presumes Linux kernel version 2.2 or greater and the C library glibc 2.1 or greater, valid assumptions for essentially all current major Linux distributions.
      
    # Link to Ubuntu
      
    * https://www.ubuntu.com/download/desktop