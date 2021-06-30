# Nginx
 NginX is a web server that can also be used as a reverse proxy, load balancer, mail proxy and HTTP cache.

 ## Custom Installation
Download [nginx](http://nginx.org/en/download.html) for your OS.

Unzip package 

>tar -xvf nginx-1.21.0.tar.gz

Configure module for your custom installation

> ./configure --sbin-path=/usr/sbin/nginx --http-log-path=/var/log/nginx/access.log --error-log-path=/var/log/nginx/error.log --conf-path=/etc/nginx/nginx.conf --with-pcre --pid-path=/var/run/nginx.pid --with-http_ssl_module --with-http_image_filter_module=dynamic --modules-path=/etc/nginx/modules

Build package

> make 

Install package 

> make install


## Basic Configuration

Nginx.conf = stores nginx properties            

Access.log = stores access logs     

error .log = stores error logs  

Index page = store index page to display into the  
browser  

Directives = nginx consists of modules which are 
controlled by directives specified in the configuration file.  

Context = block directive can have other directives inside braces.

This repository contains list of nginx configuration which you can use to play with basic nginx configuration.
