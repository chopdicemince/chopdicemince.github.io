---
layout: post
title: React, Facebook
date: 2018-07-17
---

# What is React?

The [React home page](https://reactjs.org/) says that React is "[a] JavasScript library for building user interfaces."

React was started between 2010 and 2013 at Facebook, by Jordan Walke and other workers.

For more history about React, see [The History of React.js on a Timeline](https://blog.risingstack.com/the-history-of-react-js-on-a-timeline/) and [React.js Conf 2015 Keynote - Introducing React Native](https://www.youtube.com/watch?v=KVZ-P-ZI6W4&t=0s&list=PLb0IAmt7-GS1cbw4qonlQztYV1TAW0sCr&index=1).

# What is the license of React?

React uses an [MIT license](https://github.com/facebook/react/blob/master/LICENSE), specifically, the [X11 license](https://directory.fsf.org/wiki/License:X11). Simply, anyone can use React, for any purpose.

[The X11 license is compatible with the GNU General Public License version 3.](https://www.gnu.org/licenses/license-list.html#X11License)

[React is a project on GitHub](https://github.com/facebook/react).

# What is the DOM?

Note: People say "the DOM," not "a DOM."

"DOM" stands for "Document Object Model." Simply, for an HTML file, the DOM is a tree of all the HTML tags.

A more-detailed definition is below. The definition is verbatim (except for links) from [What is the Document Object Model?](https://www.w3.org/TR/DOM-Level-2-Core/introduction.html):

> The Document Object Model (DOM) is an application programming interface (API) for valid HTML and well-formed XML documents. It defines the logical structure of documents and the way a document is accessed and manipulated...With the Document Object Model, programmers can build documents, navigate their structure, and add, modify, or delete elements and content. Anything found in an HTML or XML document can be accessed, changed, deleted, or added using the Document Object Model, with a few exceptions

# How does React work?

React uses a "virtual/intermediate DOM" to minimize changes from the "previous DOM" to the "next DOM." Suppose that we have two trees, each with n nodes, and we want to change one tree to the other. Such an alorithm has order n cubed. However, React uses an algorithm with order n, by using two hueristics:

1. Two elements of different types will produce different trees.

2. The developer can hint at which child elements may be stable across different renders with a key prop.

For more detail, see:

* [React's Architecture](https://conferences.oreilly.com/oscon/oscon2014/public/schedule/detail/34568), by Christopher Chedeau, at Facebook, 2014-07-24.

* [Reconciliation](https://reactjs.org/docs/reconciliation.html)
