---
id: bXQOBs0Pou9vQzWhPmP4N
title: Dependencyinversion
desc: ''
updated: 1641456083232
created: 1641455065030
---

## Dependency Inversion 

The direction of dependency within the application should be in the direction of abstraction, not implementation details.


Regular Applications

![Direct Dependency Graph](/assets/images/2022-01-06-13-28-51.png)

Most applications are written such that compile-time dependency flows in the direction of runtime execution, producing a direct dependency graph. 
That is, if class A calls a method of class B and class B calls a method of class C, then at compile time class A will depend on class B, and class B will depend on class 


̦
