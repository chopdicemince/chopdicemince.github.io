---
layout: post
title: current shell
date: 2018-07-22
---

# What is a shell?

A shell is a special program on an operating system which allows you to type and run commands. For example, a shell allows you to view files.

Think of an operating system as a walnut (or some other piece of fruit). The most important part of the operating system is the kernel (the kernel/center of the walnut), which controls the hardware. You are outside the operating system. The shell program is like the shell of the walnut. You can use the shell program to communicate with the operating system.

# How do I determine which shell I am using?

Type ```echo $0```, which will print the name of the currently running shell, something like ```sh``` or ```/bin/bash```.

Note: typing ```echo $SHELL``` will print the name of the default shell, which might not be currently running shell.
