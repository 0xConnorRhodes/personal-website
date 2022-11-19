---
title: "DevOps Essentials Course"
date: 2022-11-19T10:41:34-06:00
tags: ['DevOps', 'git', 'CI/CD', 'Jenkins', 'Continuing Education']
---

{{< cert src="/certs/devops-essentials.jpg" link="https://verify.acloud.guru/DB37EE5174D0" >}}

William Boyd's [DevOps Essentials course](https://acloudguru.com/course/devops-essentials) provides an introduction to the DevOps approach to writing and deploying software. Boyd begins with the historical and conceptual background for the DevOps movement. DevOps is best understood as a *cultural movement* towards stronger collaboration and shared responsibilty between engineers who write code (Dev) and engineers who deploy code (Ops.) This cultural movement gave rise to a set of practices that enable the two groups of engineers to work together more effecively and an ecosystem of tools to support this goal.

From a tooling perspective, this course focuses primarily on git (which I have [studied before](/tags/git)) and Jenkins. This course's capstone lab, in particular, presents you with a fully-built CI/CD pipeline consisting of a git repo, a Jenkins server, a staging web server, and a production web server. Through the course of the lab you merge a feature branch into production and deploy it to the staging and production web servers. You also simulate a deployment of bad code and go through the process of rolling back to the last good deployment.

My key takeways from this course were:
1. The insight that **DevOps is best understood as a cultural movement** first which gives rise to practices that produce tooling. These practices and tooling are not DevOps per se. They are products of the DevOps movement.
2. **Understanding how Jenkins works as part of a CI/CD pipeline**. Going through the process of deploying a code change to production and rolling back from a broken deployment helped me understand why Jenkins is so popular in the CI/CD space.
