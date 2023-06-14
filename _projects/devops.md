---
layout: page
title: DevOps
description: Basic DevOps concepts and tools
img: assets/img/devops.jpg
importance: 1
category: under
---

 The aim of the course is to become familiar with management, automation and monitoring tools for computing units (physical or virtual). Also cloud application management and development.

Upon successful completion of the course, the student will be able to manage and automate several software installation/configuration processes as well as the preparation of the infrastructure and services that will support modern information systems.

Sections git, automation tools (ansible), containers (docker, docker-compose), CI/CD tools (Jenkins), kubernetes, forward proxies/reverse proxies, application gateways, monitoring tools, microservices.

<div class="post">
<article>
{% for entry in site.data.devops %}
 {% include teaching/course.html %}
{% endfor %}
</article>
</div>

