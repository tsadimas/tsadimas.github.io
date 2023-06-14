---
layout: page
title: Web Information Systems
description: Web Information Systems and IoT
img: assets/img/web.jpg
#redirect: https://unsplash.com
importance: 3
category: postgraduate
---

Developing applications with the logic of microservices (comes with a lab part using fastapi, which is an async web framework in python). User authentication schemes in web applications (OAuth2, JWT) and their integration. Introduction to container concepts. Use of docker (how we create docker images, how we use public repositories such as docker hub but also private ones). Running multiple microservices using docker-compose. Creation of virtual machines in cloud computing infrastructure (example with gcloud/azure cloud, firewall configuration, static ips, ssh, dns configuration, ssl certificates). Introduction to distributed applet execution environments (kubernetes), basic entities (nodes, pods, deployments, services, ingress). Management tools for the kubernetes platform (kubectl, k9s, lens). Using microk8s for deployment of an application based on microservices. Tools for monitoring (prometheus), alerting and logging (elasticsearch-fluentd-kibana). Management of applets (servicemesh, application gateways).

<div class="post">
<article>
{% for entry in site.data.pms8 %}
 {% include teaching/course.html %}
{% endfor %}
</article>
</div>