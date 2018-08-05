---
layout: post
title: Objective-C
date: 2018-08-05
---

# What is Objective-C?

Objective-C is a programming language created in the early 1980's by Brad Cox.

Objective-C adds a small set of features to C to make it object-oriented.

See [Introduction To Objective-C](https://www.cs.colorado.edu/~kena/classes/5448/f12/lectures/13-introtoobjectivec.pdf).

# Who uses Objective-C?

In 1985, Steve Jobs was fired from Apple, after a power struggle with CEO John Sculley. (In 1976, Steve Jobs and Steve Wozniak had founded Apple.) Later in 1985, Steve Jobs co-founded NeXT, a computer company, and Pixar Animation Studios.

In 1988, NeXT licensed Objective-C, using it to write its operating system, called NeXTSTEP.

In 1996, Apple bought NeXT. Apple turned NeXTSTEP into Mac OS X (now called macOS), which was released in 2000.

See [Introduction To Objective-C](https://www.cs.colorado.edu/~kena/classes/5448/f12/lectures/13-introtoobjectivec.pdf).

See [When Steve Jobs Got Fired By Apple](https://abcnews.go.com/Technology/steve-jobs-fire-company/story?id=14683754).

# What is Objective-C used for?

At Apple, Objective-C is used for Cocoa, which is a set of two libraries:

1. The Foundation library has classes for "foundation" objects such as strings and arrays.

2. The AppKit library has classes for creating applications.

On iOS, AppKit is replaced by UIKit ("User Interface Kit"), and "Cocoa" is called "Cocoa touch."

As of 2008, Objective-C was the main language for creating applications for iOS, for the iPhone and iPad.

As of 2012, Objective-C was one of the main languages for creating applications for macOS.

See [Introduction To Objective-C](https://www.cs.colorado.edu/~kena/classes/5448/f12/lectures/13-introtoobjectivec.pdf).

# What does Objective-C look like?

Objective-C uses the keyword ```#import```, which is like ```#include``` in C, except that Objective-C will include header files exactly once.

Objective-C sometimes has names begining with "NS", which stands for "NeXTSTEP." Examples of such names are NSLog (the print function), NSObject, and NSString.

The keyword ```@interface``` indicates the start of a class. The keywords ```@end``` indicates the end of a class.

A class has two files:

1. A header file has the extension ".h" ("header"). It contains the instance variables and method signatures.

2. An implemntation file has the extension ".m" ("implementation"). It contains the method bodies.

The keywords ```@property``` defines three things: an instance variable, a getter, and a setter.
