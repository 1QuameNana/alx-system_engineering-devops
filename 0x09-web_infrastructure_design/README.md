This is a whiteboard of an infrastructural design of a simple website using 1 web server 1 Server: IP 8.8.8.8

Nginx (Web Server)

Gunicorn or similar (Application Server)

MySQL (Database)

Domain: foobar.com with www A record

Key Roles:
Web Server (Nginx): Handles HTTP, proxies to app server.

App Server: Executes code and returns dynamic content.

Database: Stores and manages application data.

DNS: Translates www.foobar.com to IP.
