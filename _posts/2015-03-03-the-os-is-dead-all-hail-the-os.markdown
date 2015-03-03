---
layout: post
title: "The OS is Dead, All Hail the OS!"
date: "2015-03-03 14:45:57 -0600"
---
Virtualization has dramatically decreased infrastructure provisioning time, and
has permitted much more efficient utilization of hardware resources.
Inevitably, when you make something easy, you get more of it.  As a result, VM
deployments are outstripping our ability to manage operating system configuration at scale.
Tools to manage OS configuration are becoming ubiquitous, e.g., Chef, Puppet,
Ansible, Salt.  However, these tools really just fix a symptom.  The problem
is:

Operating Systems contain too much stuff!
======================================
In what twisted universe does it make sense for an OS to include four text
editors, five programming languages, and seven different network debugging
tools?

In the modern Cloud Computing and Service Oriented Architecture worlds , the principal value of an OS
is to serve as a container for an application.  In other words, the role of an
OS is approximately the same as the role of the Java Virtual Machine.

OS configuration should be externalized and OS instantiation should be
parameterized to the point that starting an OS instance
is a very light-weight operation.

This concept, "OS as a Library", is gaining steam.

[Docker](https://www.docker.com/)

> An open platform for distributed applications for developers and sysadmins.

[CoreOS](https://coreos.com)

> Linux for Massive Server Deployments

[OSv](http://osv.io)

> OSv is the open source operating system designed for the cloud. Built from
> the ground up for effortless deployment and management, with superior
> performance.

[Unikernels](http://queue.acm.org/detail.cfm?id=2566628)

> What if all the software layers in a virtual appliance were compiled within
> the same safe, high-level language framework?

[NixOS](http://nixos.org)

> NixOS is a Linux distribution with a unique approach to package and
> configuration management. Built on top of the Nix package manager, it is
> completely declarative, makes upgrading systems reliable, and has many other
> advantages.
>
> Declarative specs and safe upgrades make NixOS a great system for DevOps use.
> NixOps, the NixOS cloud deployment tool, allows you to provision and manage
> networks of NixOS machines in environments like Amazon EC2 and VirtualBox.

