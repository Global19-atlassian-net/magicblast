---
layout: page
category: cook
title: "Multi-threading"
order: 6
---

To use multiple CPUs, specify the maximal number of threads with the
```-num_threads``` parameter:

```
magicblast -query reads.fa -db genome -num_threads 10
```
