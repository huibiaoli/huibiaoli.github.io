---
layout: post
title:  "git命令技巧"
date:   2015-05-28 01:21:00
categories: 运维
keywords: 运维,git
---

比较本地分支和远程分支的方法
<pre>
git fetch
git log -p HEAD..FETCH_HEAD
</pre>
