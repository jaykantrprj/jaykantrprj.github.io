---
title: HTML server using python | Hosting files using pyhton server
author: jaykantrprj
date: 2023-02-11 11:33:00 +0800
categories: [Blogging, Demo]
tags: [typography]
math: true
mermaid: true
---

## HTML server using python | Hosting files using pyhton server

> This tutorial will guide you to server your html content using python server.

## Why to use this?

The Python http.server module provides a simple way to serve HTML files over HTTP, making it possible to host a static website on your own computer. There are several reasons why you might want to host your HTML using the http.server module:

- Experimentation and development: If you are building a website and want to test it locally, you can use the http.server module to serve your HTML files and preview your site in a web browser. This allows you to iterate quickly on your design and functionality without having to upload your changes to a remote server each time.

- Personal or small-scale projects: If you have a small website or personal blog, the http.server module may be a good choice for hosting, especially if you do not need the full feature set of a more sophisticated hosting solution.

- Lack of access to a web server: If you do not have access to a web server or hosting account, or if you are not comfortable using a hosting platform, the http.server module provides a simple way to host a website from your own computer.

You can follow below steps to get it started
Install Python on your computer if it is not already installed. You can download the latest version of Python from the official website (https://www.python.org/downloads/).

Create a new directory on your computer to store the html files.

Start the Python http.server module by running the following command in the command prompt or terminal, while in the directory where your HTML file is located:

```bash
python -m http.server [port]
```
For Linux based system if above don't work
```bash
python3 -m http.server 
```
Example: To start server on port 8088
```bash
python -m http.server 8088
```
- Open a web browser and go to http://localhost:8088 to view your blog. By default, the http.server module listens on port 8000, so your blog will be accessible at that URL.

You can also customize the appearance of your blog by adding CSS and JavaScript files, and linking to them in your HTML files.
With these steps, you'll have a simple blog up and running using the Python http.server module. Keep in mind that this method is only suitable for personal or experimental blogs, as it is not a robust solution for large-scale or production use.