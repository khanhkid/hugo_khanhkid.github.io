---
title: "Install Nginx, Mysql"
date: 2019-10-21T9:46:58+07:00
draft: true
tags: [ service, nginx, mysql]
---

## OVERVIEW

Quick note about Install Nginx + Mysql

## INSTALL NGINX

Step 1: ssh to the server and run

        sudo apt update
        sudo apt install nginx

Step 2: Check nginx installed & running

        sudo nginx -v 
        sudo systemctl status nginx

You can see this 

![image alt text](/posts/images/20191021_nginx/nginx_image_status.png)

Congratuation!!!

Step 3: Check service is available

        http://server_domain_or_IP

## INSTALL MYSQL 

