---
layout: post
title:  "linux下查看监听端口"
date:   2015-05-26 01:21:00
categories: 运维
keywords: 运维,linux,监听,端口
---

mac
<pre>
sudo lsof -i -P | grep -i "listen" | grep 22
</pre>

centos
<pre>
netstat -nap | grep LISTEN | grep 9001
</pre>