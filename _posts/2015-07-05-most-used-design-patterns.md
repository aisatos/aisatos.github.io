---
layout: post
title: "Most used Design Patterns"
description: "Creation and Stragegy patterns"
category: design
tags: [patterns, design]
---
{% include JB/setup %}

Read [Effective Java - Chapter 2]( https://www.google.de/url?sa=t&rct=j&q=&esrc=s&source=web&cd=2&cad=rja&uact=8&ved=0CCgQFjAB&url=http%3A%2F%2Fuet.vnu.edu.vn%2F~chauttm%2Fe-books%2Fjava%2FEffective.Java.2nd.Edition.May.2008.3000th.Release.pdf&ei=2HeZVZKcNcelsgHXl4uIDg&usg=AFQjCNHaTVJ7cBfChZStN4QTEuewWLo98Q&sig2=IJlN2Z-fwa3_jFtq8ixtrQ&bvm=bv.96952980,d.bGg)

Reviewing the most used types of Design Patterns: Creational and Behavioural:

**Creational**

    Factory: Singleton. Returns a new object of the type required by parameter (such as a .class)

    Abstract Factory: Singleton. Returns a Factory of the type required by parameter.

    Builder: Used to create unmutable objects. It hides the setters and constructor.
      For an Annotation based coding you can use [Lombok library](https://projectlombok.org/).
      Example use: Pizza.Builder().cheese(true).jam("sure").pineaple("oh please no!").build();

**Behavioural**

    Strategy: The good old switch turned object-oriented. Each strategy (case) implements an Interface of action or validation and the list of strategies is executed on a loop. Careful with the order of execution (ej: x is not null, x.something bigger than..)
