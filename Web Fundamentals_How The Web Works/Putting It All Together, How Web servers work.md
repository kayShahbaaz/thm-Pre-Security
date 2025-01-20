**Load Balancers:**

- **When a website's traffic starts getting quite large or is running an application that needs to have high availability, one web server might no longer do the job.**
- **Load balancers provide two main features, ensuring high traffic websites can handle the load and providing a failover if a server becomes unresponsive.**
 
**CDN (Content Delivery Networks)**

- A CDN can be an excellent resource for cutting down traffic to a busy website
 
**WAF (Web Application** **Firewall****)**

- **A WAF sits between your web request and the web server; its primary purpose is to protect the webserver from hacking or denial of service attacks.** 
 
**Web Server:**

- **A Web server delivers files from what's called its root directory, which is defined in the software settings.**
- **For example, Nginx and** **Apache****share the same default location of /var/www/html in** **Linux** **operating systems, and IIS uses C:\inetpub\wwwroot for the Windows operating systems.**
- **So, for example, if you requested the file**  [http://www.example.com/picture.jpg](http://www.example.com/picture.jpg)**, it would send the file /var/www/html/picture.jpg from its local hard drive.**
 
**Virtual Hosts:**

- **A software used by Web Server**
- **The web server software checks the hostname being requested from the** **HTTP** **headers and matches that against its virtual hosts (virtual hosts are just text-based configuration files).**
- **If it finds a match, the correct website will be provided. If no match is found, the default website will be provided instead.**
- There's no limit to the number of different websites you can host on a web server.