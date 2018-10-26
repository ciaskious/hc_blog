---
title: "Day20: RegEx"
date: 2018-10-26
tags: ["regex", "notScala"]
draft: true
---


 ![regex-devrant](/images/regex.jpg)

 Today I am taking a break from Exercism and Scala. I checked my board, then I checked it again... RegEx was still there. So today, I am giving an intro to regular expressions and how to use them in the terminal to save time. I had no idea where this wanna get me but here are some findings and learnings.  


### **What's RegEx?**  


 First click on Wikipedia gave me:  

 `` In computing, regular expressions provide a concise and flexible means for identifying strings of text of interest, such as particular characters, words, or patterns of characters. Regular expressions (abbreviated as regex or regexp, with plural forms regexes, regexps, or regexen) are written in a formal language that can be interpreted by a regular expression processor, a program that either serves as a parser generator or examines text and identifies parts that match the provided specification.
 ``

 Long story short, with regexes you can match patterns of text. In most cases it's used for parsing a big text and user-input validation. My goal for today was to write some basic expressions and then use them with _grep_ and _sed_ .  

 First of all, I followed [this interactive tutorial](https://regexone.com) to get started. It is very easy to follow if you read carefully the description - I found them too long.

### **The _sed_ command**

The _sed_, as well as _grep_, are UNIX commands. With sed (**s**tream **ed**itor) you can perform search, replacements, insertions, deletions and other actions to manipulate the content of a file or multiple files. It is a non-interactive editor. While searching, I discoverd vim's _ex_ mode, which is less powerfull but it can still replace sed at some tasks. So, a basic example of sed on a file named example.txt :

``
$ cat example.txt | sed
``
