---
layout: post
title: current shell
date: 2018-07-22
---

# What is a shell?

A shell is a special program on an operating system which allows the user to type and run commands.

For example, a shell may allow a user to create or delete files.

Think of an operating system as a walnut (or some other piece of fruit). The most important part of the operating system is the kernel (the kernel/center of the walnut), which controls the hardware. The least important part of the operating system is the shell program (the shell/outside of the walnut), which communicates with the user.

# How do I determine which shell I am using?

Type ```echo $0```, which will print the name of the currently running shell, something like ```sh``` or ```/bin/bash```.

Note: typing ```echo $SHELL``` will print the name of the default shell, which might not be currently running shell.
