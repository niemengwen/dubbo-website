---
type: docs
title: "分布式事务"
linkTitle: "分布式事务"
weight: 42
description: "Dubbo 中分布式事务的支持"
---

{{% pageinfo %}} 此文档已经不再维护。您当前查看的是快照版本。如果想要查看最新版本的文档，请参阅[最新版本](/zh/docs3-v2/java-sdk/advanced-features-and-usage/service/distributed-transaction)。
{{% /pageinfo %}}

分布式事务基于 JTA/XA 规范实现。

两阶段提交：

![/user-guide/images/jta-xa.jpg](/imgs/user/jta-xa.jpg)

在 Dubbo 中，可以采用 [seata](/zh/blog/2019/01/17/如何使用seata保证dubbo微服务间的一致性/) 来完成对分布式事务的支持。