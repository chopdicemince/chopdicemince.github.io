---
layout: post
title: current shell
date: 2018-07-22
---

# What is a shell?

A shell is a special program on an operating system which allows you to type and run commands. For example, a shell allows you to view files.

Think of a walnut. The shell of a walnut separates the walnut from the rest of the world. Think of an operating system as a walnut. The shell program of an operating system separates the operating system from the rest of the world.

# How do I determine which shell I am using?

Type ```echo $0```, which will print the name of the currently running shell, something like ```sh``` or ```/bin/bash```.

Note: typing ```echo $SHELL``` will print the name of the default shell, which might not be currently running shell.
