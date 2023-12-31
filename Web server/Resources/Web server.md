```markdown
# Web Server

## Table of Contents
- [Web Server](#web-server)
  - [Table of Contents](#table-of-contents)
  - [Concepts](#concepts)
  - [Background Context](#background-context)
  - [Resources](#resources)
  - [Learning Objectives](#learning-objectives)

---

## Concepts

For this project, we expect you to look at this concept:

- [What is a Child Process?](https://www.gnu.org/software/libc/manual/html_node/Processes.html#Processes)

## Background Context

In this project, some of the tasks will be graded on 2 aspects:

1. Is your web-01 server configured according to requirements?
2. Does your answer file contain a Bash script that automatically performs commands to configure an Ubuntu machine to fit requirements (meaning without any human intervention)?

For example, if I need to create a file /tmp/test containing the string hello world and modify the configuration of Nginx to listen on port 8080 instead of 80, I can use emacs on my server to create the file and to modify the Nginx configuration file /etc/nginx/sites-enabled/default.

But my answer file would contain:

```bash
sylvain@ubuntu cat 88-script_example
#!/usr/bin/env bash
# Configuring a server with specification XYZ
echo hello world > /tmp/test
sed -i 's/80/8080/g' /etc/nginx/sites-enabled/default
sylvain@ubuntu
```

As you can tell, I am not using emacs to perform the task in my answer file. This exercise is aiming at training you on automating your work. If you can automate tasks that you do manually, you can then automate yourself out of repetitive tasks and focus your energy on something more interesting. For an SRE, that comes in very handy when there are hundreds or thousands of servers to manage, and the work cannot be done only manually. Note that the checker will execute your script as the root user, so you do not need to use the sudo command.

A good Software Engineer is a lazy Software Engineer.

## Resources

Read or watch:

- [Video intro](https://www.youtube.com/watch?v=AZg4uJkEa-4&feature=youtu.be&hd=1)
- [How the web works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)
- [Nginx](https://en.wikipedia.org/wiki/Nginx)
- [How to Configure Nginx](https://www.digitalocean.com/community/tutorials/how-to-set-up-nginx-server-blocks-virtual-hosts-on-ubuntu-16-04)
- [Child process concept page](https://intranet.alxswe.com/concepts/110)
- [Root and subdomain](https://landingi.com/help/domains-vs-subdomains/)
- [HTTP requests](https://www.tutorialspoint.com/http/http_methods.htm)
- [HTTP redirection](https://moz.com/learn/seo/redirection)
- [Not found HTTP response code](https://en.wikipedia.org/wiki/HTTP_404)
- [Logs files on Linux](https://www.cyberciti.biz/faq/ubuntu-linux-gnome-system-log-viewer/)
- [-y on apt-get command](https://askubuntu.com/questions/672892/what-does-y-mean-in-apt-get-y-install-command)
- [Replace a line with multiple lines with sed](https://stackoverflow.com/questions/26041088/sed-replace-line-with-multiline-variable)

For reference:

- [RFC 7231 (HTTP/1.1)](https://datatracker.ietf.org/doc/html/rfc7231)
- [RFC 7540 (HTTP/2)](https://datatracker.ietf.org/doc/html/rfc7540)

man or help:

- [scp](https://linux.die.net/man/1/scp)
- [curl](https://linux.die.net/man/1/curl)

## Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

### General

- What is the main role of a web server
- What is a child process
- Why web servers usually have a parent process and child processes
- What are the main HTTP requests
- DNS
- What DNS stands for
- What is DNS's main role
- DNS Record Types
  - A
  - CNAME
  - TXT
  - MX
```
