---
title: "Wikidatadump Reader"
subtitle: "version 0.1.0"
author: "hwt"
avatar: "img/authors/hwt.jpg"
image: "img/20160210.jpg"
date:   2016-02-10 22:36:12
---

# wikidata dump reader  

由于做毕设的原因，需要用到wikidata的数据，我找了官网上的下载地址[Wikidatadump](https://en.wikipedia.org/wiki/Database_dump)作为我使用的数据。

由于这个datadump有60多个G，而且只是一个文件，为了获得其中的某一条wikidata的记录十分不方便，此外，在这个datadump中，还有许多我做毕设不需要的信息，把这些信息重新处理。  

因为这个是json格式的数据，我想如果我储存在mongodb中进行信息的检索可能会比较好。
