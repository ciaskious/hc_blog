---
title: "Day9: TGIF and Data Stuctures"
date: 2018-10-12
tags: ["scala"]
draft: false
---

### val daysOfTheWeek = Map("Friday" -> "YAY")

Today lots of things got clear in my head: Tuples, Maps, Lists and Arrays. It was about time, as since university times all I have worked with is [(H)Arrays](https://ciatastrophe.netlify.com/post/day7/) and today it was a nice opportunity to recap while reading chapter 4.

So here is a general overview of data structures in Scala.
#### **Array**
As we all know, arrays are fixed-sized collections, where collections of elements of the same type are stored. In an array of potatoes, there is no room for carrots. We can traverse the values and its indices.

``` scala
for ( day <- daysOfTheWeek ) { println(day)}
for ( i <- 0 to daysOfTheWeek.length) { println(day)}
```
However, you can create dynamic arrays and modify their size by using an _Array Buffer_

#### **Tuple**
A general rule is, that you create a tuple when you want your function to return more that one value. It was one of the lessons I learned during my coding interview at HolidayCheck!
A tuple is a sequence of values, that don't have to be of the same type.
``` scala
val myTuple = ( 1, 2.3, "Anastasia" )
```
 Unlike arrays, the positions in a tuple start from 1 instead of 0.
 ```
 scala> myTuple._1
 res0: Int = 1
 ```
#### **Map**


#### Lists

#### Special: Options
