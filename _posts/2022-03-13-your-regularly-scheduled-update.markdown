---
layout: post
title:  "Your Regularly Scheduled Update"
date:   2022-03-13 20:30:19 -0500
categories: development
---

Okay, so first update - and I can say it's been a busy couple of weeks. 

Firstly, I've started to make progress on what's tenatively being called TK + Scribe at the moment. For the immediate future this is intended to largely be performance focused changes to TavernKeeper's API. These changes will invovle deploying a new server with new code, that references TavernKeeper's existing database and mirrors the current TavernKeeper API exactly. This means that we'll be able to migrate TavernKeeper on an API-Call by API-Call basis. The end result will be a series of small but noticible impovements to the speed of the application. 

I'm currently hoping to replace the heaviest parts of TavernKeeper; such as the dashboard in March. Without getting into the underlying technology too much, TavernKeeper is written in Ruby - and Scribe was started in Elixir. There are plenty of benchmarks out there if you happen to be inclined to Google them. However, the performance jump is pretty staggering. 

Alot of the stuff being worked on is pretty foundational; such as testing, error handing, schema setup and authentication.
