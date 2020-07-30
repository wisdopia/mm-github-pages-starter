---
layout: post
title:  "Useful Java APIs for Coding Interview"
---

# Sorting 2D Array

```
Arrays.sort(intervals, Comparator.comparingInt(item -> item[0]));
Arrays.sort(intervals, Comparator.comparing(item -> item[0], Comparator.reverseOrder()));
```
