# Network Footprinting
Network footprinting is the process of gathering information about a network to understand its structure, components, and security posture. This involves collecting details about network topology, IP addresses, routing information, and network devices such as routers, firewalls, and servers.
## Tools Used 
1. **nslookup**: Used to obtain various types of DNS-related information.
2. **traceroute**: Used to track the hops,path that packets take from your computer to a destination host.
3. **Shodan**: Used to gather information about servers, IoT devices, and other networked systems. It can be used for competitive intelligence to understand the technological landscape and security posture of competitors.
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

## 3. **Shodan.io**
### Steps to Use Shodan.io

1. **Visit the Website**:
   - Go to [Shodan](https://www.shodan.io/).

2. **Create an Account or Log In**:
   - If you don't have an account, sign up for a free account. If you already have an account, log in using your credentials.
3. **Enter Search Criteria**:
   - In the search bar, enter the IP address, domain name, or search term related to the network or devices you want to investigate.
   - *Example search:* `Ubuntu` 
   
   <p align="center">
     <img src="https://s4.aconvert.com/convert/p3r68-cdx67/a4r8u-whzuo.jpg" alt="Shodan Search" width="400">
   </p>

4. **Review the Results**:
   - Shodan will display a list of devices, their IP addresses, open ports, services running, and other relevant details.
   
   <p align="center">
     <img src="https://s4.aconvert.com/convert/p3r68-cdx67/ab1f0-tp0b1.jpg" alt="Shodan Results" width="400">
   </p>

