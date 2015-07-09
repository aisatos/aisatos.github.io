---
layout: post
title: "SOLID Design Principles"
description: ""
category: design
tags: [design, principles, SOLID]
---
{% include JB/setup %}

S.O.L.I.D is an acronym for the first five object-oriented design(OOD) principles by Robert C. Martin (Uncle Bob).

**Single-Responsability:**

  "A class should have only a single responsibility (i.e. only one potential change in the software's specification should be able to affect the specification of the class)""
  There should never be more than one reason for a class to change.

**Open-Closed:**

  "Software entities should be Open for extension but Closed for modificaction."
  In practice: Abstract the main features you need into an Interface and reference the Interface instead of the concrete Class.

**Liskov substitution:**

  "Objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program."
  Subtypes must be substitutable for their base types.
  If you follow Liskov principle, you are inherently complying with the Open-Closed principle.

**Interface segregation:**

  "Classes that implement Interfaces should not be forced to implement methods they do not use"
  Many client-specific interfaces are better than one general-purpose interface.
  In practice: Keep your Interfaces light, not bulky. In other words, use Single-Responsability principle for creating your Interfaces as well as Classes.

**Dependency Inversion:**

  "One should depend upon Abstractions. Do not depend upon concretions."
  High level modules should not depend on low level modules. Both should depend on Abstractions
  Abstractions should not depend on details. Details should depend on Abstractions.

**See Also**
  ACID: Atomicity - Consistency - Isolation - Durability
  YAGNI: "You ain't gonna need it."
  DRY: "Don't repeat yourself."
  KISS: "Keep it simple stupid."
