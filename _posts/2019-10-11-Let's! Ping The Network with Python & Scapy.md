---
title: 'Bravo! Ping The network with 15 Line Of Code Using python & Scapy!'
date: 2019-10-11
permalink: /posts/2019/10/Ping The Network with Python & Scapy/
tags:

  - python
  - Scapy
---
![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/3jivpktvsvhavic0km8d.gif)

> Let's try to travel the time 1 year back when I started to learn about little bit about hacking and networking in windows and **Linux**. **Ping** was my first tool,it is a basic networking utility which helps to check connectivity and communication b/w two systems.So When first time I used this utility it helped me to understand the basic concept of **packets**,and I was very much happy. well I know its sound to much awkward now.
![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/4qgkyv4m36qp8botka49.jpg)
Well!! Then after spending my more time in pentesting, I started to automate more stuff using **python**. yesterday **ping** came back to me, when I was working and trying to understand how packets works, & found one of the module of the python [**scapy**](https://scapy.net) and tried to break the code & ping the network,lets try to understnd what I did with with **scapy**.

> ## Scapy and How it works:
So before discussing about **scapy** you need to be able that how to write code in python ,& if you don't know then this place is not for you!! Now What is **Scapy** and how it works?
Well [**scapy**](https://scapy.net) is a powerful **Python-based interactive packet manipulation program and library**.It is able to forge or decode packets of a wide number of protocols, send them on the wire, capture them, store or read them using pcap files, match requests and replies, and much more. It is designed to allow fast packet prototyping by using default values that work.

> To install this super amazing python based library & tool you need to write this following commands in your os terminal:
```python
pip install scapy (Windows)
pip3 install scapy (Linux)
```
> ## My ping script with scapy & python:
<script src="https://gist.github.com/ankitdobhal/158606d8c60827abbeca86880d2e020c.js"></script>

> ### what is this code doing? Let's break
python have its power to automate most of the stuffs which lets the pentester to ease their hacking task,In above code the basic first thing I did **imported scapy and sys module** to use them their functions,**ip** is the variable which stores the target ip address ,**icmp** variable which creates packet and **resp** variable which  contain **sr1** function that Send packets at layer 3 and return only the first answer.Then finally condional statement to check host is up or down.

> **Thankyou for visiting and understanding the power of python,You can also find above code in my [gist](https://gist.github.com/ankitdobhal/158606d8c60827abbeca86880d2e020c) and can ask me about anything.**
