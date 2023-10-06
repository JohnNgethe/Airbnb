# Concepts

## Table of Contents
- [Concepts](#concepts)
  - [Table of Contents](#table-of-contents)
  - [Load Balancer](#load-balancer)
  - [Web Stack Debugging](#web-stack-debugging)
  - [Background Context](#background-context)
  - [Resources](#resources)
  - [Requirements](#requirements)

---

## Load Balancer

For this project, we expect you to look at these concepts:

1. [Load balancing](https://www.thegeekstuff.com/2016/01/load-balancer-intro/)
2. [Load-balancing algorithms](https://community.f5.com/t5/technical-articles/intro-to-load-balancing-for-developers-the-algorithms/ta-p/273759)

## Web Stack Debugging

1. [Youtube video First 5 Commands When I Connect on a Linux Server](https://www.youtube.com/watch?v=1_gqlbADaAw&feature=youtu.be)
2. [5 commands](https://www.linux.com/training-tutorials/first-5-commands-when-i-connect-linux-server/)
3. [uptime and downtime](https://www.techtarget.com/whatis/definition/uptime-and-downtime)

## Background Context

You have been given 2 additional servers:

Let’s improve our web stack so that there is redundancy for our web servers. This will allow us to be able to accept more traffic by doubling the number of web servers, and to make our infrastructure more reliable. If one web server fails, we will still have a second one to handle requests.

For this project, you will need to write Bash scripts to automate your work. All scripts must be designed to configure a brand new Ubuntu server to match the task requirements.

## Resources

Read or watch:

- [Introduction to load-balancing and HAproxy](https://www.digitalocean.com/community/tutorials/an-introduction-to-haproxy-and-load-balancing-concepts)
- [HTTP header](https://www.techopedia.com/definition/27178/http-header)
- [Debian/Ubuntu HAProxy packages](https://haproxy.debian.net/)

## Requirements

General:

- Allowed editors: vi, vim, emacs
- All your files will be interpreted on Ubuntu 16.04 LTS
- All your files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- All your Bash script files must be executable
- Your Bash script must pass Shellcheck (version 0.3.7) without any error
- The first line of all your Bash scripts should be exactly #!/usr/bin/env bash
- The second line of all your Bash scripts should be a comment explaining what is the script doing
