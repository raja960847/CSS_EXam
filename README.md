# CSS_EXam
Q1- What is ARP ? Explain in brief?

 Ans-   (ARP)-address resolution protocol
     Address Resolution Protocol (ARP) is a network-specific standard protocol. The Address Resolution Protocol is important for changing the higher-level protocol address (IP addresses) to physical network addresses. 
________________________________________________________________________________________________________________________________________________________________


Q2- What is NAT ? Explain in brief?

Ans-   Network Address Translation (NAT) 
      it is a way to map multiple private addresses inside alocal network to a public ip address 
      brfore transferring the information onto the internet organizations that want multiple device to emoly a single ip address use NAT as do most home router or       firewall
_____________________________________________________________________________________________________________________________________________________________________

Q3-  What is Private IP Address ? 

 Ans-  A private IP address is an IP address that is used on a local network and is not     
      directly accessible from the internet1234. A private IP address is assigned by a network device, such as a router, that uses network address translation to connect to the internet using a public IP address125. A private IP address has four sections of numerical digits and is reserved for internal use by the Internet Assigned Numbers Authorit
______________________________________________________________________________________________________________________________________________________________________

Q4-   Explain conditions for Deadlock/?

Ans-   A deadlock situation on a resource can arise only if all of the following conditions occur simultaneously in a system:
  
 Four important conditions for deadlock are:
 (A) MATUAL EXCLUSION

    Deadlock can happen only when resources are non-shareable If either R1 or R2 can be shared then both P1 and P2 can make progress because they both can get hold of it. Therefore mutual exclusion is required. 

 (B) HOLD AND WAIT

      A process must be handled at least one resource and waiting to require additional resources that are currently being held by the other processes.

 (C) NO RESOURCE PREEMPTION

The operating system assigns a resource to a process and cannot take it back if another process requests it because if it happens then deadlock will never occur. Resources cannot be preempted i.e. a resource can be released only voluntarily by the process holding it after that process has completed its task. 

 (D) CIRCULER WAIT 

In circular wait, processes are waiting in a circle for each other. All four conditions are necessary for a deadlock to happen. If a deadlock happens in the system then either the operating system has to do some work or we need to reboot the system.

We can understand deadlock by a real-world example. For example, consider a railway track where two trains are coming from opposite sides. Both trains are in front of each other and they are stopped because they both need the other side of the track. So this is a situation where no train can make progress because both trains are holding one side of the track waiting for the other side of the track. And both are waiting in a circular manner and we cannot do preemption. We cannot make the train go out of the track and free the track. This situation is a deadlock. 

_____________________________________________________________________________________________________________________________________________________________________


Q5- Explain Swap Memory?

Ans- If you run out of physical memory, you use virtual memory, which stores the data in memory on disk. Reading from disk is several orders of magnitude slower than reading from memory, so this slows everything way down. (Exchanging data between real memory and virtual memory is "swapping". The space on disk is "swap space".)
_____________________________________________________________________________________________________________________________________________________________________


Q6-  : For the given cache of size 3 and below inputs tell
the cache HIT rate .5 4 3 2 1 3 5 6 7 8 10 15 Explain each step briefly.?

Ans-  Cache hit rate is the percentage of requests for data that can be served by the cache, rather than having to be retrieved from the origin server. It is calculated by dividing the number of cache hits by the total number of cache hits and misses, and multiplying by 100 to get a percentage. A high cache hit ratio means that most requests are satisfied by the cache and not by the disk or the origin server, which can improve performance and reduce latency1.

For the given cache of size 3 and below inputs: 5 4 3 2 1 3 5 6 7 8 10 15, the cache HIT rate is 25%. Here’s how it works:

_______________________________________________________________________________________________________________________________________________________________________

Q7-  Explain Consistent Hashing in brief.?

Ans-  Consistent Hashing is a distributed hashing scheme that operates independently of the number of servers or objects in a distributed hash table. It powers many high-traffic dynamic websites and web applications.

In this tutorial, Toptal Freelance Software Engineer Juan Pablo Carzolio will walk us through what it is and how hashing, distributed hashing and consistent hashing work.
_______________________________________________________________________________________________________________________________________________________________________


Q8-   Explain what happens when you type www.attainu.com in the web browser.?

Ans-   When you type www.attainu.com in the web browser, the browser checks the cache for a DNS  record to find the corresponding IP address of www.attainu.com. DNS (Domain Name System) is a distributed database that maps domain names to IP addresses. If the browser does not find a DNS record in the cache, it will send a DNS request to the DNS server to resolve the domain name. The browser then initiates a TCP connection with the server at that IP address on port 80 (HTTP) or 443 (HTTPS). The browser sends an HTTP request message to the server, asking it to send a copy of the website to the client. If the server approves the request, it sends an HTTP response back to the browser with the requested content. The browser then renders the page as per HTML and CSS code received from the server 
_______________________________________________________________________________________________________________________________________________________________________


Q9-  What is Context Switching ? Explain in brief?

Ans-   The Context switching is a technique or method used by the operating system to switch a process from one state to another to execute its function using CPUs in the system. When switching perform in the system, it stores the old running process's status in the form of registers and assigns the CPU to a new process to execute its tasks. While a new process is running in the system, the previous process must wait in a ready queue. The execution of the old process starts at that point where another process stopped it. It defines the characteristics of a multitasking operating system in which multiple processes shared the same CPU to perform multiple tasks without the need for additional processors in the system.
_______________________________________________________________________________________________________________________________________________________________________


Q10 -  Explain all the layers TCP/IP model with example?

Ans- TCP/IP was designed and developed by the Department of Defense (DoD) in the 1960s and is based on standard protocols. It stands for Transmission Control Protocol/Internet Protocol. The TCP/IP model is a concise version of the OSI model. It contains four layers, unlike the seven layers in the OSI model,
The TCP/IP model is a set of protocols that enable communication over networks12345. The model has four or five layers, depending on the version245. The four layers are the application layer, the transport layer, the internet layer, and the network access layer134. The five layers are the application layer, the transport layer, the network layer, the data link layer, and the physical layer25. The application layer supports various protocols for different types of applications, such as HTTP, FTP, SMTP, and DNS34. The transport layer handles the flow of data and error control, using protocols such as TCP and UDP13. The internet layer or the network layer routes the data packets across the network, using protocols such as IP135. The network access layer or the data link layer and the physical layer define the physical standards and the network interface for the transmission of data145.
_______________________________________________________________________________________________________________________________________________________________________
