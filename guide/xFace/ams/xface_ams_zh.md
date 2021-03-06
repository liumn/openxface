---
layout: default
title: xFace Application Management System
lang: zh
---

##What is AMS
xFace offers a running mode for multiple apps. Typically there is a supervisor app which's responsible for all other managed applications. Let's simply call this supervisor app as "Portal". Only Portal can be authorized AMS permission. 

Basically AMS offers a set of interfaces to manage apps as following,

![ams](img/ams.png "ams outline")

##AMS with App Market

With a back-end app market service, the Portal can ask for the market to get information, download, install or update apps with desire. The next figure outlines the entire circle, 

![ams with market](img/ams_with_market.png "market")

The whole solution of AMS with one dedicated market provides an ability to build your own app ecosystem. Here's a screenshot of our Portal app,

![portal demo](img/portal_demo.png "portal demo")
