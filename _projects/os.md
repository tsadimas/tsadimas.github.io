---
layout: page
title: Operating Systems
description: Laboratory of Operating Systems
img: assets/img/os.jpg
importance: 3
category: undergraduate
---
Introduction to UNIX, File Management, I/O Redirection, Pipes, Regular Expressions, Process Management, File System Permissions, Environment Variables, Shell Scripting, Programming UNIX Functions in C (System Calls). fork(), wait(), exec(), low-level I/O, pipe(), threads, mutexes, semaphores, networking with sockets
 


<div class="post">
<article>
{% for entry in site.data.os %}
 {% include teaching/course.html %}
{% endfor %}
</article>
</div>