# Awesome Network Programmability [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of resources and packages for networking programmability and automation


## Table of Contents

- [Utilities](#utilities)
  - [Automation](#automation)
  - [Monitoring](#monitoring)
    - [Dashboard](#dashboard)
    - [Utility](#utility)
- [Libraries](#libraries)
  - [General Programmability](#general-programmability)
  - [Python](#python)
  - [Examples](#examples)
- [Resources](#resources)
  - [Books](#books)

## Utilities

### Automation
- [Ansible](https://docs.ansible.com)  
An agentless automation tooling that can perform a variety of automation functions against a wide variety of devices and operating systems.

- [Puppet](https://docs.puppet.com)  
An agent-based automation tooling that can perform a variety of automation functions against a wide variety of devices and operating systems.

- [Chef](https://docs.chef.io/chef_overview.html)  
Agent-based automation tooling that focuses on the concept of "Infrastructure as Code."

- [Salt](https://docs.saltstack.com/en/latest/)  
Agent-based automation tooling. Support for networking devices appears to be on the backseat, but has modules that provide some functionality like [via NSO](https://docs.saltstack.com/en/latest/ref/proxy/all/salt.proxy.cisconso.html).

### Monitoring

#### Dashboard
- [Observium](http://www.observium.org)  
"Observium is a low-maintenance auto-discovering network monitoring platform supporting a wide range of device types, platforms and operating systems ..."

#### Utility
- [Joy](https://github.com/cisco/joy)  
"A package for capturing and analyzing network flow data and intraflow data, for network research, forensics, and security monitoring."

- [pmacct](http://www.pmacct.net)  
"A small set of multi-purpose passive network monitoring tools. It can account, classify, aggregate, replicate and export forwarding-plane data, ie. IPv4 and IPv6 traffic; collect and correlate control-plane data via BGP and BMP; collect infrastructure data via streaming network telemetry."

- [ToDD](https://github.com/toddproject/todd)  
"ToDD is an extensible framework for providing natively distributed testing on demand."

## Libraries

### General Programmability

- [YDK](https://developer.cisco.com/site/ydk/)  
Model-driven APIs for simplified programmability of your network device. Generates APIs based off of YANG models that can be used programmatically.

### Python

- [Napalm](https://github.com/napalm-automation/napalm)  
Network Automation and Programmability Abstraction Layer with Multivendor support

- [Paramiko](http://www.paramiko.org/)  
Implementation of SSHv2 protocol, providing both client and server functionality.

- [Netmiko](https://github.com/ktbyers/netmiko)  
Multi-vendor library to simplify Paramiko SSH connections to network devices.

- [Trigger](https://github.com/trigger/trigger)  
"... a robust network automation toolkit written in Python that was designed for interfacing with network devices."

- [CiscoConfigParse](http://www.pennington.net/py/ciscoconfparse/)  
This library examines an IOS-style config and breaks it into a set of linked parent / child relationships for auditing, modifying, and/or building new configurations.

- [Jinja2](http://jinja.pocoo.org/docs/2.9/)  
Templating language for Python and excellent library to use for generating network device configuration from templates.

### Examples
- [Cisco gRPC Connection Libraries](https://github.com/cisco-grpc-connection-libs)  
Example repositories on how to use gRPC in Python, NodeJS, etc. for the IOS-XR end node.

- [Solenoid](https://github.com/ios-xr/Solenoid)  
App that injects routes directly into Cisco's IOS-XR RIB table

## Resources

### Books
- [Programmability and Automation with Cisco Open NX-OS](http://www.cisco.com/c/dam/en/us/td/docs/switches/datacenter/nexus9000/sw/open_nxos/programmability/guide/Programmability_Open_NX-OS.pdf)  
Understand how to utilize network programmability for NXOS *(Programmability Fundamentals, Model Driven Programming, Configuration Automation)*

- [Beej's Guide to Network Programming](http://beej.us/guide/bgnet/)  
Arguably one of the simplest and best guides to using network sockets in C. Since it's in C you get to understand a lot of concepts that might otherwise be glossed over in higher level languages. Also has basic, boilerplate examples.

- [Network Programmability and Automation](http://shop.oreilly.com/product/0636920042082.do)  
- [Network Programmability and Automation](https://www.amazon.com/Network-Programmability-Automation-Next-Generation-Engineer/dp/1491931256/ref=sr_1_1?ie=UTF8&qid=1491481634&sr=8-1&keywords=network+programmability+and+automation)
- [Network Programmability and Automation](https://www.amazon.com/Network-Programmability-Automation-Next-Generation-Engineer/dp/1491931256/ref=sr_1_1?ie=UTF8&qid=1491481634&sr=8-1&keywords=network+programmability+and+automation)  
Good foundation for Network Engineers looking to be more comfortable with the standard tools of network automation. The book is in early release on Safari Online, and should be released later in 2017.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Cisco's Innovation Edge Team has waived all copyright and
related or neighboring rights to this work.
