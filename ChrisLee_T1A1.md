# Term 1 A1 Assignment: Christopher Lee 12189@CoderAcademy.edu.au

### **Assignment Brief: Demonstrate knowledge of fundamental programming concepts and the web. Provide a series of short answers to the specified questions.**

# **Question 1: Identify and explain common and important components and concepts of web development markup languages.**

Three popular markup languags that you are likely to encounter in your career in computer science are: HTML, XML and XHTML. These versions share similarites and differences; as the internet evolves and grows, so do markup languages. However, with an evolving web environment, continuity and compatability issues can arise. This issue was predicted and as such, versions of HTML represent standardized improvements to the foundational language for the World Wide Web.
As technology improves and develops, the methodology to achieve desired web page results evolves alongside it.  

Important components of web pages are things such as tables, forms, lists, headings and style. In order for a browser to be able to interpret and reproduce information in the way we want, we need to provide a uniform structure to the web pages we create. Structuring our web page to explain where to place certain content, how certain content should look and even conditions upon how we want content to behave allows use to produce reliable, intentional and reproducable outcomes.  

# **Question 2: Define the features of the following technologies that are essential in terms of the development of the internet**:
 - _packets_
 - _IP addresses (IPv4 and IPv6)_
 - _routers and routing_
 - _domains and DNS_  
# **Explain how each technology has contributed to the development of the internet.** 

**Packets**: Sending information across the internet is a mysterious capability that seemingly functions magically.However, the process of delivering data from one computer to another is actually a very logical process. To understand why data is broken down into packets, we first need to understand _how_ computers communicate. Computers communicate to one another using **binary**. Computers use transistors to act like electronic swithces, being that they are either _on_ or _off_. The simplest way to convey the desired command to another computer is through binary, being that the number 0 will represent **on** and the number 1 will represent **off**.<br>  
</br> Now imagine you want to send a reasonably large sized file across the internet. In order to do that, both computers -or however many computers are on the recieving network- will _talk_ to one another via binary and corresponding electrical signals. Sending the file in one complete "package" will not be the most efficent way for your data to travel. Because the data is sent via a physical connection of wires, the possibility of congestion increases exponentially the moment more than 2 computers are involved.  
This is where packets come in. <br>
</br> Data is broken into packets in order to decrease latency and increase overall efficiency of the journey from one computer to another. These packets are sent as incredibly small, deconstructed "packages" which can then be reconstructed on the recieving end.  
Packets are seperated into incredibly small pieces of data - **_64kb_**- each of these pieces of data carries information that i being sent from one computer to another. For example; some of these packets will contain information regarding the sender, such as their ip address, others will contain information that explains how many packets the reciever should expect to see. Other packets serve purposes such as informing the recieving computer when it has reached the end of the packet sequence.<br>  
</br>Because of the way this data is structure during sending, we are able to communicate with large networks and send information across the globe seemingly instantly. In terms of the development of the internet, i strongly believe that packets have contributed massively. Without packets, trasnfer efficiency of data  would be congested and slow, it would be a nightmare in todays world and would seriously hinder the progression and development of tech.
<br>

</br>

**IP Addressess**: In order for us to transfer data across the internet, we need to know _where_ to actually send said data. Comparable to your physical street address, an IP address is used as a means to identify hardware on networks. To simplify, if you wanted to send a letter to a friend, you would need to know what their address is. Their physical address identifies their house on a street with multiple other houses. The same principle applies to computers. Having IP addresses, allows both devices to connect and trasnfer data over the internet. IP addresses are unique  and consist of a string of numbers seperated by periods. For ipv4, the older IP framework, the string of numbers are seperated into 4 sections. Each section ranges between 0 and 255. This means that an ipv4 IP address would look something like this: **127.0.0.1**.
One of the shortcomings of ipv4 is the sheer amount of hardware that exsits in the world today. Computers, routers, websites etc all have unique IP addresses. Consequently, this means we will reach the maximum amount of unqiue identifiers under this framework. So how do we get around this shortcoming?<br>
</br> Introducing ipv6. In order for ipv6 to adapt to the increasing amount of techonological presence in the modern world, it implemetedan alphanumerical hexadecimal notation. Meaning, IP addresses now contain both letters **and** numbers. Ipv6 uses 128-bit addresses formatted into 8 groups of 4 hexadecimal numbers.  
An example of an ipv6 IP address is: **2002:0de6:0001:0042:0100:8c2e:0370:7234**   
One of the benefits of such a complex string of numbers and letters is that even in 2022, each device can have its own IP address, as opposed to needing to reuse addresses or mask them.<br> 
</br> In todays tech world, both ipv4 and ipv6 are in use. As tech continues to develop and old technology is retired, the use of ipv4 will slowly begin to decline until it is replaced entirely by ipv6.  
In terms of the development of the internet, ipv6 was an incredibly intelligent piece of technology implemented as a means to fix an originally unforseen problem. Its mere existence is nothing short of completely neccessary in todays world and its implementation is, in my opinion, an incredibly impressive feat of intelligence, perserverance and quick-thinking-problem-solving completed by engineers.
<br>

</br>

**Routers and Routing:**
Routers are used to connect devices such as computers or phones to the internet. Typically, a wireless router will connect directly with a modem. From there, information can be recieved or transmitted to the internet. Routers use built in attenas to communicate with devices on the home network. A wired router however, would connect directly from the modem to the device (computer).
Earlier, i wrote about packets. Thats how information is broken down for "shipment". I then spoke about IP addresses, thats how the "shipment" knows where to go and where it came from. All of that is great but without routers, it doesnt mean much. See, the purpose of a router is to provide the framework for the other two actions to take place. Meaning, without network connectivity, the rest is meaningless. Routing is the ability to send or forward packets from my network to someone elses network (or vice versa).The role of the router is to connect the 2 (or more) networks and then manage the traffic within. Using something called a routing table (list of all possible paths on the network) routers are able to recieve packets, crosscheck the routing table and then figure out the fastest path to send that data along.
Because of its capability to route traffic between devices and the internet, your home devices are able to connect to the internet.
In terms of the development of the internet, routers are responsible for security, connectivity, packet filtering etc. These tasks are incredibly fascinating and seem to occur seemlessly thanks to the technology involved.  