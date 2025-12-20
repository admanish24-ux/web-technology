# web-technology
in term of the Internet, a protocol is a set of rules and standards that define how data is formatted, transmitted, received, and interpreted between devices connected to a network.
In simple terms, protocols ensure that computers and other devices can communicate with each other correctly, even if they use different hardware or software.
Example:
HTTP is a protocol used for transferring web pages.
TCP/IP is a protocol suite that enables reliable data transmission over the Internet.

# The primary difference between a Web Browser and a Search Engine is their function:
 A Web Browser is a software application used to access and view websites on the Internet.
 Examples: Google Chrome, Mozilla Firefox, Safari.
 A Search Engine is an online service used to find information or websites on the Internet by searching keywords.
 Examples: Google, Bing, DuckDuckGo.
 
 # The World Wide Web (WWW) is a system of interlinked web pages and resources that are accessed over the Internet using a web browser.
   It uses URLs to locate resources, HTTP/HTTPS to transfer data, and web browsers to view text, images, videos, and other content.

# The difference between a static web page and a dynamic web page is based on how content is created and displayed:
 Static Web Page:
  A static web page shows the same content to every user. It is written using basic HTML and does not change unless manually edited
  Example: A simple informational page.
# Dynamic Web Page:
   A dynamic web page displays different content based on user interaction, time, or data from a database. It uses technologies like JavaScript, PHP, or databases.
   Example: Social media pages or online shopping sites.
   
# Explain the client-server architecture of the web with a neat diagram.
   Client–Server Architecture of the Web
   The client–server architecture is the basic structure on which the World Wide Web operates. It divides the work of a network into two main parts: clients, which request services, and servers, which provide        those services.

   Client
A client is a device or software (usually a web browser like Chrome, Firefox, or Edge) used by the user to access the web.
Functions of the client:
1. Sends requests for web pages or data
2. Receives responses from the server
3. Displays web content (text, images, videos, etc.) to the user
# Server
A server is a powerful computer that stores websites, web pages, databases, and applications.

Functions of the server:
 1. Receives requests from clients
 2. Processes the requests
 3. Sends back the requested web pages or data

#How the Client–Server Model Works
  The user enters a website address (URL) in a web browser.
  The browser (client) sends an HTTP/HTTPS request to the web server.
  The server processes the request and finds the required web page or data.
  The server sends an HTTP/HTTPS response back to the client.
  The browser displays the received content to the user.
          Client (Web Browser)
        --------------------
        |  Chrome / Edge  |
        |  Firefox, etc.  |
        --------------------
                |
        HTTP / HTTPS Request
                |
                v
        --------------------
        |   Web Server     |
        | (Stores websites|
        |  & databases)   |
        --------------------
                |
        HTTP / HTTPS Response
                |
                v
        Client displays
        the web page
        
# Key Features of Client–Server Architecture
  Centralized data: Websites and data are stored on servers.
  Efficiency: Multiple clients can access the same server.
  Scalability: Servers can be upgraded to handle more users.
  Security: Servers manage access and protect data

Conclusion
 The client–server architecture enables efficient communication on the web by clearly separating the roles of requesting (client) and providing (server) information. This structure is the foundation of how  
 websites and web services work on the Internet.

# Describe the functions of the following Internet services: Email, FTP, and VoIP. long question
 1. Functions of Internet Services
   The Internet offers many services that help users communicate, share data, and interact in real time. Among the most important Internet services are Email, FTP, and VoIP. Each service has a specific function      and plays a vital role in modern communication.
Email (Electronic Mail)
Email is an Internet service used for sending and receiving digital messages between users anywhere in the world.

Functions of Email:
1.Allows users to send and receive text messages instantly.
2.Supports file attachments such as documents, images, audio, and video files.
3.Enables communication with one or multiple recipients at the same time.
4.Provides features like inbox, sent items, drafts, and spam filtering.
4.Stores messages for future reference.
6.Used for personal communication, official work, education, and business

# FTP (File Transfer Protocol)
  FTP (File Transfer Protocol) is an Internet service used to transfer files between computers over a network.

Functions of FTP:
1.Enables uploading files from a local computer to a remote server.
2.Allows downloading files from a server to a local computer.
3.Supports transferring large files efficiently.
4.Helps manage files on remote servers (copying, deleting, renaming).
5.Commonly used for website maintenance and software distribution.

# VoIP (Voice over Internet Protocol)
  VoIP (Voice over Internet Protocol) is a technology that allows voice communication over the Internet instead of traditional telephone systems.

Functions of VoIP:
 1.Enables voice calls using an Internet connection.
 2.Supports video calling and audio conferencing.
 3.Reduces communication costs, especially for long-distance calls.
 4.Allows real-time communication across different devices.
 5.Widely used in online meetings, remote learning, and customer support.
 6.VoIP provides fast and efficient voice communication worldwide.

 # The Internet is a network of networks.” Elaborate on this statement explaining how packet switching works.
 “The Internet is a Network of Networks” — Explanation with Packet Switching
  The statement “The Internet is a network of networks” means that the Internet is not a single, centralized network. Instead, it is a global system made up of many smaller networks (such as home networks,
  school networks, company networks, and Internet Service Provider (ISP) networks) that are interconnected using standard protocols. These independent networks communicate with each other to allow data to travel   worldwide.
# Why the Internet Is Called a Network of Networks
 1. Different organizations (schools, governments, companies, ISPs) own and manage their own networks.
 2. These networks are connected through routers and gateways.
 3. Common protocols like TCP/IP ensure that all networks can communicate, regardless of hardware or location.
 4. This interconnection allows users on one network to communicate with users on another network anywhere in the world.

How Packet Switching Works
Packet switching is the fundamental technique used by the Internet to transmit data efficiently.
Step-by-Step Working of Packet Switching

# Data Breakdown
 When a user sends data (such as an email or web page request), the data is broken into small units called packets.

# Packet Structure
1. Each packet contains:
2. Part of the original data
3. Source IP address
4. Destination IP address
5. Packet sequence number

#Routing Through Networks
 Packets travel independently through different routes across multiple networks.
 Routers decide the best path for each packet based on network traffic and availability.

#Packet Delivery
 Packets may arrive at the destination out of order.
 Some packets may take different paths across different networks.

# Reassembly
At the destination, the receiving system reassembles packets in the correct order.
Missing or corrupted packets are retransmitted (handled by TCP).

Advantages of Packet Switching
 Efficient use of network resources
 Reliable communication, even if part of the network fails
 Scalable, allowing millions of networks to connect
 Faster data transmission by using multiple routes

#  A startup company wants to host a website that displays the same information to all visitors and requires very low maintenance costs. However, they are being advised to usea dynamic website. As a consultant, would you agree? Justify your answer
 Case Study Analysis: Static vs. Dynamic Website for a Startup
 A startup company wants to host a website that: Displays the same information to all visitors Has very low maintenance cost

 # Static Website
Shows fixed content to all visitors.
Built with HTML/CSS; no database or server-side processing needed.
Low maintenance cost: content only changes if manually updated.
Fast loading and secure due to simplicity.

 #Dynamic Website
Displays content that can change based on user interaction or data from a database.
Built with technologies like PHP, JavaScript, or Python with a database backend.
Higher maintenance cost: requires server management, database upkeep, and programming expertise

# Analysis for the Startup
The company wants the same content for all visitors, so there is no need for dynamic features.
They also want very low maintenance costs, which aligns with static websites, not dynamic ones.
Using a dynamic website would increase complexity and cost unnecessarily.

# A user types www.google.com into their browser, but the browser displays a ”Server Not Found” error, even though the internet connection is active. However, accessing the site via 142.250.190.46 works. Diagnose the problem and explain the underlying technology that failed.
# Problem Diagnosis
Scenario:
User types www.google.com in the browser → “Server Not Found” error.
Internet connection is active.
Accessing the site via its IP address 142.250.190.46 works.

#Observation:
The site is accessible by IP but not by domain name.
This indicates a problem with domain name resolution, not with the Internet connection or the web server.

#Likely Problem
The problem is related to DNS (Domain Name System).
DNS is the system that translates human-readable domain names (like www.google.com) into IP addresses (like 142.250.190.46).

 # If DNS fails:
The browser cannot find the server by its domain name.
Directly using the IP address bypasses DNS, allowing access.

# Possible Causes:
Incorrect DNS settings on the computer or router.
ISP DNS server is down or unreachable.
Cached DNS records are corrupted.

Underlying Technology: DNS
# Domain Name System (DNS):
 Acts like the Internet’s phonebook, mapping domain names to IP addresses.

# When you type a URL:
The browser queries the DNS server to get the IP address.
The server responds with the correct IP.
The browser connects to the server using that IP. 
 
# Solution
Check DNS settings and ensure a valid DNS server is configured (e.g., Google DNS 8.8.8.8 or 8.8.4.4).
Clear DNS cache using commands like:
Windows: ipconfig /flushdns
Mac: sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder
