# Network Footprinting
Network footprinting is the process of gathering information about a network to understand its structure, components, and security posture. This involves collecting details about network topology, IP addresses, routing information, and network devices such as routers, firewalls, and servers.
## Tools Used 
1. **nslookup**: Used to obtain various types of DNS-related information.
2. **traceroute**: Used to track the hops,path that packets take from your computer to a destination host. 
## 1. **nslookup** 
### Steps to Use nslookup
1. **Open Command Prompt or Terminal**:
   - *On Windows:* Press Win + R, type cmd, and press Enter.
   - *On macOS or Linux:* Use the Terminal application.

2. **Type nslookup Command:**:
   - *Command:*
      - Website: nslookup website
      - Ip Address: nslookup ipaddress
   - *Example:*
     - nslookup www.snapchat.com
     - nslookup 93.184.216.34
       <div style="display: flex; justify-content: center;">
      <img src="https://s4.aconvert.com/convert/p3r68-cdx67/aa4v3-v11d9.jpg" alt="Image 1" style="width: 300px; height: auto; margin-right: 10px;">
      <img src="https://s4.aconvert.com/convert/p3r68-cdx67/aws7j-iu5yv.jpg" alt="Image 2" style="width: 400px; height: auto; margin-left: 10px;">
    </div>
  

3. **Review the Results**:
   - nslookup will display information such as the IP address of the queried domain, the DNS server used for the lookup, and other DNS-related details.

## 2. **traceroute** 
### Steps to Use traceroute
1. **Open Command Prompt or Terminal**:
   - *On Windows:* Press Win + R, type cmd, and press Enter.
   - *On macOS or Linux:* Use the Terminal application.
2. **Type Commands:**
   - *Windows Command:* tracert website
     - *Example:* tracert google.com
   - *Linux/macOs Command:* traceroute website
     - *Example:* traceroute google.com
   <div style="display: flex; justify-content: center;">
      <img src="https://s4.aconvert.com/convert/p3r68-cdx67/aul0h-zg4m4.jpg" alt="Image 1" style="width: 300px; height: auto; margin-right: 10px;">
      <img src="https://s4.aconvert.com/convert/p3r68-cdx67/acw26-pppy1.jpg" alt="Image 2" style="width: 400px; height: auto; margin-left: 10px;">
    </div>
3. **Review the Results**:
   - traceroute will display the hop count,response times,host name or ip address
