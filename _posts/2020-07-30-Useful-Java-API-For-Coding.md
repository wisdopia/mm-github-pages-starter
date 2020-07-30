---
title:  "Useful Java APIs for Coding Interview"
categories:
  - Java
tags:
  - Coding Interview
  - Java
  - Sorting
---

# Sorting 2D Array


```java
Arrays.sort(intervals, Comparator.comparingInt(item -> item[0]));
Arrays.sort(intervals, Comparator.comparing(item -> item[0], Comparator.reverseOrder()));
```
