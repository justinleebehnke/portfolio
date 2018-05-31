---
title: "Salesforce Integration"
description: "Challenges when building an app for Salesforce"
slug: "salesforce-integration"
image: salesforce-logo.png
keywords: ""
categories: 
    - "salesforce"
    - "canvas"
date: 2017-10-31T21:28:43-05:00
draft: false
---
#Get ready to researchi
So when you first start out trying to build an app on the Salesforce platform 
you will find yourself being pulled in a lot of different directions. One 
thing you need to determine right away is if you want to use the non-
programming language approach you will just have to learn their system. 

Since I am already familiar with a few web technologies I decided that I wanted
to do my own thing with a Node.js server that calls simple python applications.
I thought that would be the easy route since I had already built something that
just needed to be plugged into their API... or so I thought. 

Then came the good/bad news. The good news was that they have a tool that I can
use to have a locally synchronized database on a PaaS called Heroku, using a tool called Heroku Connect. The bad 
news was, I built my app to use an API interface with JSON. Dumb move on my 
part to build something without knowing exactly how the data was structured. 

Anyways now I have to learn how to query data dynamically from different users
and the more I look for information on how I might be able to figure all this 
out, the more tired I get from all the so called "examples" that show everything 
that I am not doing. 

I know it's going to be worth the trouble and hopefully soon I will be able to
make a blog post about how I slew this dragon. 

The basic outline I've got so far is as follows:
1.Use Canvas to display your app inside of Salesforce
2.Use Heroku Connect on the Heroku PaaS to get rapid data access and about a billion other sick features
3.Somehow figure out how to dynamically map the DB Schema of your client base to your standardized schema
4.Get super rich and retire

That's all I've got so far and that's after about 16 hours of research. We'll see how this develops
