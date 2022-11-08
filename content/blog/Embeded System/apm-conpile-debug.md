---
title: "Apm Conpile Debug"
date: 2022-08-11T16:28:43+08:00
draft: true
---

Build APM from source code on MAC Book M1 Pro and explore the possible debug(embedded) methods.   

## Build 

waf is a special tool to organize the framework which means it is not quite common.   

the config script is written in python and seems can only generate .elf file for some specific boards like ESP32... 

Compile process become smoothly after I use a reliable but expensive proxy.



## Debug

GDB on m1 mac is not supported till now, but lldb is available. lldb can debug embedded system like STM32 though I have no board and JTAG with me yet.

