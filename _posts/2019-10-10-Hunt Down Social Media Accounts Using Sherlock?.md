---
title: 'How Do I Hunt Down Social Media Accounts Using Sherlock?'
date: 2019-10-10
permalink: /posts/2019/10/Hunt Down Social Media Accounts Using Sherlock!/
tags:

  - python
  - Social media
---
"**Social media is one of the easiest platform for hackers to find out information about any particular person or target. - Ankit Dobhal**"

Today! I wake up very late in the morning,& later at 9:30 I had a breakfast.
Then something happened one of my friend sent me a link about a tool **Sherlock** which could hunt down social media accounts with username.

Well as I usually do !!
I sat down in a cheer in front my computer with a cup of coffee,boot up my operating system.
Then I go through [github link](https://github.com/sherlock-project/sherlock) of **Sherlock** & started learning about that tool.

# **What is Sherlock?**

Sherlock is a python based tool which can reveal many user accounts created by the same person in the multiple social media platforms with their **screen_name** or **username**.
sherlock script is written on python. You can checkout the whole script from its [github](https://github.com/sherlock-project/sherlock) link.
![](https://thepracticaldev.s3.amazonaws.com/i/i5s59ny60iirfedqyno4.JPG)

 

## **How I Hunt Down Social media Accounts With Sherlock?**

> **Step 1 -: Installed Sherlock**
 In a terminal window I copied the link of sherlock from [github] 
 (https://github.com/ankitdobhal/sherlock) and run following commands.
 ![](https://thepracticaldev.s3.amazonaws.com/i/3ox2dolbvwaz1ko6cb2i.JPG)
 **Note : Python3 and python3-pip have to be installed.**
 To get help about Sherlock I tried **python sherlock -h** command from inside 
 the Sherlock folder.
 ![](https://thepracticaldev.s3.amazonaws.com/i/947hil9pokhs7zqkzf6k.JPG)

> **Step 2 -: Identify screen name**
Just after reading the help I was ready to start script.But wait how to find out screen name of my target? Then I found screen name of my target by running a Google search and "Twitter."
My target was Sir **[Robert Baptiste](https://twitter.com/fs0c131y) aka elliot_alderson**. He is french security researcher & I admire his work on security a lot. 
 ![](https://thepracticaldev.s3.amazonaws.com/i/mii62u4ur7lqkmjgp3bc.JPG)

> **Step 3 -: Scan for accounts**
Then finally I ran sherlock.py script with following commands in my terminal screen **python target_name -r --print-found** to find out all social media account of my target.
![](https://thepracticaldev.s3.amazonaws.com/i/ux8c4jwmmzjsza9ljsox.JPG)
**Note : '-r' argument in the above command will organize the list of found 
          accounts by which websites are most popular,& '--print-found' will 
          show all accounts in terminal screen.**
          
So as you can see above example that how I hunt down account all over internet using sherlock.py script.I also tried to contribute some file in this tool You can go through with this link to find out [sherlock](https://github.com/ankitdobhal/sherlock) tool.
-: https://github.com/sherlock-project

