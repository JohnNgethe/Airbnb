# HTTPS SSL

## Table of Contents
- [Concepts](#concepts)
  - [DNS](#dns)
  - [Advanced](#advanced)
  - [Web Stack Debugging](#web-stack-debugging)
  - [Background Context](#background-context)
  - [Resources](#resources)
  - [Requirements](#requirements)
- [Learning Objectives](#learning-objectives)

---

## Concepts

For this project, we expect you to look at these concepts:

### DNS

1. [Learn everything about DNS in cartoon](https://howdns.works/)
2. Be sure to know the main DNS record types:
   - [A](https://support.dnsimple.com/articles/a-record/)
   - [CNAME](https://en.wikipedia.org/wiki/CNAME_record)
   - [MX](https://en.wikipedia.org/wiki/MX_record)
   - [TXT](https://en.wikipedia.org/wiki/TXT_record)

### Advanced

- [Use DNS to scale with round-robin DNS](https://www.dnsknowledge.com/whatis/round-robin-dns/)
- [What’s an NS Record?](https://support.dnsimple.com/articles/ns-record/)
- [What’s an SOA Record?](https://support.dnsimple.com/articles/soa-record/)
- [What’s the point in having www in a URL?](https://serverfault.com/questions/145777/what-s-the-point-in-having-www-in-a-url/)

## Web Stack Debugging

### Background Context

What happens when you don’t secure your website traffic?

## Resources

Read or watch:

- [What is HTTPS?](https://www.instantssl.com/http-vs-https)
- [What are the 2 main elements that SSL is providing](https://www.sslshopper.com/why-ssl-the-purpose-of-using-ssl-certificates.html)
- [HAProxy SSL termination on Ubuntu16.04](https://docs.ionos.com/cloud/)
- [SSL termination](https://en.wikipedia.org/wiki/TLS_termination_proxy)
- [Bash function](https://tldp.org/LDP/abs/html/complexfunct.html)

man or help:

- awk
- dig

## Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

General:

- What is HTTPS SSL 2 main roles
- What is the purpose of encrypting traffic

### Requirements

General:

- Allowed editors: vi, vim, emacs
- All your files will be interpreted on Ubuntu 16.04 LTS
- All your files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- All your Bash script files must be executable
- Your Bash script must pass Shellcheck (version 0.3.7) without any error
- The first line of all your Bash scripts should be exactly #!/usr/bin/env bash
- The second line of all your Bash scripts should be a comment explaining what is the script doing
