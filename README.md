# **resolv.conf for Android**
## Description
Have you ever run Go applications in your Android terminal, only to find there is no DNS available for the app? The issue turns out that the Go app will check /etc/resolv.conf for DNS querie. Unfortunatly on most devices /etc/resolv.conf is missing.

This module simple puts resolv.conf to your /system/etc and does nothing more.

Here is what the resolv.conf contains:
```
nameserver 1.0.0.1
nameserver 80.80.80.80
nameserver 223.5.5.5
```
## Changelog
v1 Initial release
## Requirements
No requirements known yet
## Instructions
1. Clone this repo and zip it. Make sure the META-INF directory is at the root of your zipped archive.
2. Flash it via Magisk Manager.
## Links
[Latest stable Magisk](http://www.tiny.cc/latestmagisk)
