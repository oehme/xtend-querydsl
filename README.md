xtend-querydsl
==============

A small Xtend wrapper for the awesome [QueryDsl](http://www.querydsl.com/) library. 

[![Build Status](https://oehme.ci.cloudbees.com/job/xtend-querydsl/badge/icon)](https://oehme.ci.cloudbees.com/job/xtend-querydsl/)

    <dependency>
      <groupId>com.github.oehme.xtend</groupId>
      <artifactId>xtend-querydsl</artifactId>
      <version>...</version>
    </dependency>

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
![](http://www.cloudbees.com/sites/default/files/Button-Built-on-CB-1.png)
