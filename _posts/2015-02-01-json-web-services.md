---
layout: post
title:  "Tutorial: Creating a java JSON web service in 10 minutes"
date:       2015-01-16 16:21:29
summary:    This guide walks you through the process of creating a "hello world" web service with jsonsrv.
categories: tutorials
tags: jee json web rpc http
---
This guide walks you through the process of creating a "hello world" web service with jsonsrv.
**What you’ll build:**

You’ll build a service that will accept HTTP GET/POST requests at:
```
http://localhost:8080/jsonsrv-example/srv?id=hello
```

and respond with a JSON representation of a greeting:

{"value":{"greeting":"Hello!"}}
