xtend-querydsl
==============

A small Xtend wrapper for the awesome QueryDsl library. 

[![Build Status](https://oehme.ci.cloudbees.com/job/xtend-querydsl/badge/icon)](https://oehme.ci.cloudbees.com/job/xtend-querydsl/)

Features
========

This wrapper mainly adds operator overloads for expressions. Instead of writing

    person.firstName.eq("Stefan").and(person.age.gt(20))
  
You can now write

    person.firstName == "Stefan" && person.age > 20
    
Usage
=====

Add it to your dependencies

    <dependency>
      <groupId>com.github.oehme.xtend</groupId>
      <artifactId>xtend-querydsl</artifactId>
      <version>...</version>
    </dependency>
    
And import it

    import static extension de.oehme.xtend.querydsl.QueryDslExtensions.*
