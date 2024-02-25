Simple Web stack is a collection of softwares that contain an OS, a programming language, database software, and a Web server. When the user  types a URL and clicks enter/return, the browser makes an HTTP request to the server. Then the webserver process the HTTP request by responding back with HTML Contents the web server contains static data such as static web pages and html documents. A server is a piece of computer hardware or software that provides functionality for other programs or devices. It shares data, resources and distributes work. It also helps in finding the correct IP address of the site requested by the user.
A domain name is an easy-to-remember name that’s associated with a physical IP address on the Internet. It’s the unique name that appears after the @sign-in email addresses, and after www. in web addresses.
The Domain Name System (DNS) is a system used to convert a computer’s hostname into an IP on the Internet.
www is a CNAME(Canonical Name) DNS record-type in www.foobar.com since it points to the same IP address as foobar.com and if the IP address changes we can only record changes in the DNS 
An application server is to acts as a host for the user’s business logic and dynamic content.
A database is a software used for storing data in our application, it allows the management, creation, updating, and retrieval of records. 

Issues That Can Affect A Simple Web Stack:
Single Point Of Failure (SPOF), is a part of the system that, if it fails the whole entire system stops from working.This web stack has no redundancy that can help in avoiding SPOFs, hence, any single failure in any part of the system will cause all the system to stop.
Downtime when maintenance needed (like deploying new code web server needs to be restarted); the downtime will occur because we only have one server and one database, which is used to make the deployment and maintenance which will leave the users with no access to the website during that period.
Cannot scale if it gets too much incoming traffic; this web stack cannot scale if there’s too much incoming traffic because no second server in the system to share loads and the system will be overloaded.
