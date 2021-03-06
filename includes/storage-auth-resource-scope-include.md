---
title: "include file"
description: "include file"
services: storage
author: tamram
ms.service: storage
ms.topic: "include"
ms.date: 03/21/2019
ms.author: tamram
ms.custom: "include file"
---

Before you assign an RBAC role to a security principal, determine the scope of access that the security principal should have. Best practices dictate that it's always best to grant only the narrowest possible scope.

The following list describes the levels at which you can scope access to Azure blob and queue resources, starting with the narrowest scope:

- **An individual container.** At this scope, a security principal has access to all of the blobs in the container, as well as container properties and metadata.
- **An individual queue.** At this scope, a security principal has access to messages in the queue, as well as queue properties and metadata.
- **The storage account.** At this scope, a security principal has access to all containers and their blobs, or to all queues and their messages.
- **The resource group.** At this scope, a security principal has access to all of the containers or queues in all of the storage accounts in the resource group.
- **The subscription.** At this scope, a security principal has access to all of the containers or queues in all of the storage accounts in all of the resource groups in the subscription.
