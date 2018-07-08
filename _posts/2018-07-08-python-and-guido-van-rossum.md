---
layout: post
title: Python, Guido van Rossum
date: 2018-07-08
---

# What is Python?

Python is a programming language. It is object-oriented. The main website is [Python](https://www.python.org/).

Python files end with the extension ".py".

One notable feature of Python is that indentation is important. If you change the indentation of Python code, you might change its meaning. (This situation contrasts with many other languages.) For example, consider the following two pieces of Python code:

```python
if 1 == 2:
  print('a')
  print('b')
print('c')
```

The above code will print 'c'. But suppose we change the indentation of the line for printing 'b':

```python
if 1 == 2:
  print('a')
print('b')
print('c')
```

The above code will print 'b' and 'c'.

# How did Python get its name?

The name "Python" comes from the British comedy show "Monty Python's Flying Circus," in the 1970s. See [Why is it called Python?¶](https://docs.python.org/3/faq/general.html#id19).

# What is CPython?

[CPython](https://github.com/python/cpython) is an implementation of Python which is written in C. CPython is the main implementation of Python. If you do not know which implementation you are using, probably it is CPython.

Suppose that you are using CPython and you type the following command, to run some Python code:

```python
python my_code.py
```

Then CPython does the following steps:

1. CPython translates Python code to an intermediate language, sometimes called (Python) bytecocde. This intermediate language is stored in files that end with the extension ".pyc". You can think of "pyc" as meaning "Python compiled code."
1. CPython runs the intermediate language in a virtual machine.

CPython is not the only implementation of Python. There are [many implementations of Python which are written in other languages](https://wiki.python.org/moin/PythonImplementations). For example, [Jython](http://www.jython.org/) is an implementation of Python which is written in Java. Jython will translate your Python code to Java bytecode, which is stored in files that end with the extension ".class". Jython will run the Java bytecode in the JVM (Java Virtual Machine).

# Who is Guido van Rossum?

[Guido van Rossum](https://gvanrossum.github.io) is creator of Python. He is from the Netherlands.

Below is a picture of Van Rossum in 2014 at Dropbox, his workplace. (Dan Stroud took the[ original picture](https://commons.wikimedia.org/wiki/File:Guido-portrait-2014.jpg), which has the license CC-BY-SA-4.0.)

![2014: Van Rossum worked at Dropbox](https://github.com/chopdicemince/chopdicemince.github.io/blob/master/images/2014-guido-van-rossum-at-dropbox.png '2014: Van Rossum worked at Dropbox')

Trivia: Van Rossum used to live in Virginia and had a vanity license plate that said "PYTHON."

# When was Python created?

Van Rossum created Python in 1989, when he had a lot of time around Christmas. He wanted Python to be a better version of the language ABC, which he was using at work. The language Modula-3 was a source/model for parts of Python. In 1991, Van Rossum wrote about Python on USENET.

See [Why was Python created in the first place?](https://docs.python.org/3/faq/general.html#id7).
