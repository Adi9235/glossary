---
title: 混沌工程
status: Completed
category: 概念
tags: ["安全", "", ""]
---

## 是什么

混沌工程或 CE 是在生产中对 [分布式系统](/distributed-systems/) 进行实验的学科，以建立对系统承受动荡和意外情况时能力的信心。

## 解决的问题

[SRE](/site_reliability_engineering/) 和 [DevOps](/devops/) 实践侧重于提高产品弹性和 [可靠性](/reliability/) 的技术。
系统在故障容灾时确保服务质量的能力通常是对软件开发提出的要求。这里涉及到几个方面可能导致应用程序中断，例如基础设施、平台或（基于[微服务](/microservices/)）的应用程序的其他部分。
高频地持续部署新功能到生产环境会增加服务中断和恶性事件发生的可能性，乃至于对业务产生重大影响。

## 如何帮助

混沌工程是一种满足弹性要求的技术。它用于实现对基础架构、平台和应用程序等意外发生时的故障容灾。
混沌工程师使用混沌实验主动注入随机故障，以验证应用程序、基础架构或平台是否可以自我修复，并且故障不会对客户产生明显影响。
混沌实验旨在发现盲点（例如监控或自动伸缩技术）并在恶性事件发生期间增强团队之间的沟通。
这种方法有助于提高复杂系统的弹性和团队对其的信心，尤其是在生产环境。
