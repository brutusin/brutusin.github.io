---
layout: post
title:  "Instrumentation framework"
date:       2015-01-16 11:21:29
summary:    An extensible java agent framework that instruments (modifies the bytecode at class load time) programs running on the JVM, with the purpose of capturing method invocation events (start, finish, errors ...) and notifying custom listeners.
categories: java instrumentation brutusin bytecode
---

Some years ago I created, a simple java agent with the goal of tracing some method executions of third-party libraries in a non-intrusive way.

These past days, I have been improving and refactoring that piece of code and finally published it at GitHub, under the following description: 
> An extensible java agent framework that instruments (modifies the bytecode at class load time) programs running on the JVM, with the purpose of capturing method invocation events (start, finish, errors ...) and notifying custom listeners.*

You can find more information in the following links:

* [Brutusin instrumentation framework](https://github.com/brutusin/brutusin/tree/master/instrumentation) being an extensible framework to create custom agents. 
* [Brutusin logging implementation](https://github.com/brutusin/brutusin/tree/master/logging-instrumentation) a concrete implementation to log method executions.



Hope you enjoy it!