---
sidebar_position: 2
---


## What is NGINX

NGINX is a high-performance HTTP server and reverse proxy, as well as an IMAP/POP3 proxy server. NGINX is known for its high performance, stability, rich feature set, simple configuration, and low resource consumption. Website: nginx.org, nginx.com.

##### Install NGINX Web Server

```bash 
$ sudo dnf install nginx
# Start NGINX when system boots
$ sudo systemctl enable nginx
# Start NGINX
$ sudo systemctl start nginx
# Check NGINX Status
$ sudo systemctl status nginx
```

Now visit http://localhost/. You should see NGINX Test Page:



