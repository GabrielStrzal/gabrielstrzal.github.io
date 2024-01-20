---
layout: post
title:  String repeat
tag: codewars
---


## Thinking of different solutions to String repeat challenge.

I was doing some CodeWars challanges and this looked interesting:

> Write a function that accepts an integer n and a string s as parameters, and returns a string of s repeated exactly

initially my guess is to brute force this challenge to just append things:

Some of the solutions:
- Stringbuilder
  ```java
  sb.append(string);
  ```
- Simple Strings
  ```java
  s += string
  ```
- String methods (java 11)
  ```java
  string.repeat(repeat);
  ```


which is the best?
