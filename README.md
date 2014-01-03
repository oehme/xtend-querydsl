xtend-querydsl
==============

A small Xtend wrapper for the awesome QueryDsl library. 

[![Build Status](https://oehme.ci.cloudbees.com/job/xtend-querydsl/badge/icon)](https://oehme.ci.cloudbees.com/job/xtend-querydsl/)

    <dependency>
      <groupId>com.github.oehme.xtend</groupId>
      <artifactId>xtend-querydsl</artifactId>
      <version>...</version>
    </dependency>

Features
========

This wrapper mainly adds operator overloads for expressions. Instead of writing

    person.firstName.eq("Stefan").and(person.age.gt(20))
  
You can now write

    person.firstName == "Stefan" && person.age > 20
