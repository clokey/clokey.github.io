---
layout: post
title: "MacOSXVirtualSerialPort"
date: 2014-03-08 23:05:16 +0000
comments: true
categories: OSX code
---
The first of the open source projects is now moved to the github repository. [MacOSXVirtualSerialPort](https://github.com/clokey/PublicCode/tree/master/MacOSXVirtualSerialPort) was a means of creating a virtual serial port pair on Mac OS X 10.7. Sadly it doesn't work anymore as the code relied on an interface builder plugin that no longer works and an authentication model no longer supported in Mac OS X.

The readme file in the repo does include instructions on how to use the underlying socat tool to achieve the same outcome.
