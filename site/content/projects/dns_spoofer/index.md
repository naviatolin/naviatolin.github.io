+++
image = "dns_spoofer.png"
date = "2022-04-08"
title = "Minimal DNS Spoofer"
type = "gallery"
tags = "Python, Networking"
+++
I implemented a minimal DNS spoofer daemon in Python using standard POSIX functions that listens on the DNS port for A record requests and returns a hard-coded IP address of 6.6.6.6. This project includes a Makefile in order to start the daemon and the daemon working on your laptop can be seen using the dig tool on Unix systems.

[(Project Code)](https://github.com/naviatolin/minimal_dns_spoofer)