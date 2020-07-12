---
layout: post
title: Wikipedia Scrape With 10 line of code
description : "As easy to srape anything."
date: 2019-10-05
tags: [Python, Scraping]
---

"**Hackers loves to use scraping to harvest data.~Ankit Dobhal**"

Welcome to My Blog
========
Hello my Computer Geek Friend!!This is a blog about scraping wikipedia content using python & bs4(python module),.
So what is exactly web scraping & from where this term comes from?Let's Try To Understand!!
![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/d0xz6qnhcpb7vztyq09y.jpeg)
**Web Scraping - :**
  Web scraping is data scraping process used for extracting data from websites.Web scraping can be done manually by a software user, the term typically refers to automated processes implemented using a bot or web crawler.It comes when world wide web born.Most of time search engine like google uses crawling process in their search result.
  
**Scraping With Python - :**
Web scraping & crawling can be done with the help of some softwares but in Nowadays Python is gaining its popularty in the field of web scraping & crawling ,& as we all know python is one of the most famous & powerful scripting languages generally for hackers & shell coders.
Python have some amazing & powerful modules & libraries which makes this scraping process so easy & useful,Their are two important modules in python one is **requests** & another is **BeautifulSoup**.

Let's Write Python Script to scrape wikipedia content or wikipedia searcher:
==
> I have a basic understanding how to do get request  to websites using python , so first of all I open up my **vscode** editor and create file name as **wikipy.py**.Then import **sys** library(**command line argument**), **requests** library(**for downloading & get method to wikipedia**), & my favorite library **BeautifulSoup** as **bs4** (**To extact content from wikipedia page**).
                      ![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/wflp6q7l9jvrdwt0yfbp.JPG)
Now its time to use get method to requests data from wikipedia server , but wait  I want to create a wikipedia searcher which will scrape the data according to my command line argument.So let's create a variable name as **res** to store get method to wikipedia search url & add it with my command line argument.
                      ![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/815z46vojx879xkbr51e.JPG)) 
**note: I uses raise_for_status() method if their is any error code and status code comes so this method will raise that & whole script will terminate.**
                      ![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/0lz57c8hrcqtn488yf7a.JPG)
 **res** download the whole page but it is complicating to extract data from the page bacuase it shows the html format data , so now this is time to use **BeautifulSoup** to extract data. So I am creating a variable name as **wiki** to extract data.
                      ![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/w1q8rhinaq6j5cpiczor.JPG)
**note: As you can in wiki varibale I uses BeautifulSoup function with two parameters ,So what they are exactly? let's understand. res.text is a text format of the page which is downloaded with the help of res variable  & html.parser is a parser which will          help me to sturcture the data into html format.**


> I want to scrape the <p> tag content according to command line argument because the whole text content of wikipedia page is inside the  <p> tag you can check this with the help of developer tools of chrome & firefox.
                      ![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/avqkw2464ox3ivqtsqyi.png)
Now I am using .select() function to select p tag & for loop to looping throgh it ,then finally printing the text elements inside p tag with.getText() function.
                      ![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/9w6lk4jrnl9zu7ts5qdx.png)

**Yeah we did it in just 10 line of code bravo!!!**
Its time to run the script with command line argument >>
                     ![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/9nw28k5v7plrk5qocnip.jpg)

**Thankyou all for visting my blog you can also check my gist for wikipy script the link is below!!
[wiki.py](https://gist.github.com/ankitdobhal/cc40a40cccd69bd646aaa06b7a05046e)
follow me on github & linkedlin for more exciting blogs and scripts!** 
