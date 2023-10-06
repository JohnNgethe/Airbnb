
```markdown
# AirBnB Clone - Web Dynamic

## Table of Contents
- [AirBnB Clone - Web Dynamic](#airbnb-clone---web-dynamic)
  - [Table of Contents](#table-of-contents)
  - [Resources](#resources)
  - [Learning Objectives](#learning-objectives)
  - [Requirements](#requirements)
    - [General](#general)
  - [More Info](#more-info)
    - [Import JQuery](#import-jquery)
    - [Before starting the project…](#before-starting-the-project)

---

## Resources

Read or watch:

- [Code base to fork](https://github.com/jzamora5/AirBnB_clone_v3)
- [Selector](https://jquery-tutorial.net/selectors/using-elements-ids-and-classes/)
- [Get and set content](https://jquery-tutorial.net/dom-manipulation/getting-and-setting-content/)
- [Manipulate CSS classes](https://jquery-tutorial.net/dom-manipulation/getting-and-setting-css-classes/)
- [Manipulate DOM elements](https://jquery-tutorial.net/dom-manipulation/the-append-and-prepend-methods/)
- [Document ready](https://learn.jquery.com/using-jquery-core/document-ready/)
- [Introduction](https://jquery-tutorial.net/ajax/introduction/)
- [GET & POST request](https://jquery-tutorial.net/ajax/the-get-and-post-methods/)
- [HTTP access control (CORS)](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS)

## Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

### General

- How cool it is to request your own API
- How to modify an HTML element style
- How to get and update an HTML element content
- How to modify the DOM
- How to make a GET request with JQuery Ajax
- How to make a POST request with JQuery Ajax
- How to listen/bind to DOM events
- How to listen/bind to user events

## Requirements

### General

- Allowed editors: vi, vim, emacs
- All your files will be interpreted on Chrome (version 57.0)
- All your files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- Your code should be semistandard compliant with the flag --global $: semistandard *.js --global $
- All your JavaScript must be in the folder scripts
- You must use JQuery version 3.x
- You are not allowed to use var
- HTML should not reload for each action: DOM manipulation, update values, fetch data…

## More Info

### Import JQuery

```html
<head>
    <script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
</head>
```

### Before starting the project…

You will work on a codebase using Flasgger, you will need to install it locally first before starting the RestAPI:

```bash
$ sudo apt-get install -y python3-lxml
$ sudo pip3 install flask_cors # if it was not installed yet
$ sudo pip3 install flasgger
```

If the RestAPI is not starting, please read the error message. Based on the error message(s), you will have to troubleshoot potential dependencies issues.

Here are some solutions:

**jsonschema exception**
```bash
$ sudo pip3 uninstall -y jsonschema
$ sudo pip3 install jsonschema==3.0.1
```

**No module named 'pathlib2'**
```bash
$ sudo pip3 install pathlib2
```

**Expose ports from your Vagrant**

In your Vagrantfile, add this line for each port forwarded:

```ruby
# I expose the port 5001 of my vm to the port 5001 on my computer
config.vm.network :forwarded_port, guest: 5001, host: 5001
```

If you need to expose other ports, use the same line but replace the "guest port" (inside your Vagrant) and your "host port" (outside your Vagrant, used from your browser, for example).

It's important in your project to use the AirBnB API with the port 5001.
```
