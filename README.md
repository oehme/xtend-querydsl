xtend-querydsl
==============

A small Xtend wrapper for the awesome [QueryDsl](http://www.querydsl.com/) library. 

[![Build Status](https://travis-ci.org/oehme/xtend-querydsl.svg)](https://travis-ci.org/oehme/xtend-querydsl)
[ ![Download](https://api.bintray.com/packages/oehme/maven/xtend-querydsl/images/download.svg) ](https://bintray.com/oehme/maven/xtend-querydsl/_latestVersion)

Features
========

This wrapper mainly adds operator overloads for expressions. Instead of writing
```java
    person.firstName.eq("Stefan").and(person.age.gt(20))
```  
You can now write
```java
    person.firstName == "Stefan" && person.age > 20
```  