---
title: Azure PowerShell samples for virtual network | Microsoft Docs
description: Azure PowerShell samples for virtual network.
services: virtual-network
documentationcenter: virtual-network
author: jimdial
manager: jeconnoc
editor: ''
tags:
ms.assetid:
ms.service: virtual-network
ms.devlang: na
ms.topic: article
ms.tgt_pltfrm:
ms.workload: infrastructure
ms.date: 03/20/2018
ms.author: jdial

---
# Azure PowerShell samples for virtual network

The following table includes links to Azure Powershell scripts:

| | |
|----|----|
| [Create a virtual network for multi-tier applications](./scripts/virtual-network-powershell-sample-multi-tier-application.md) | Creates a virtual network with front-end and back-end subnets. Traffic to the front-end subnet is limited to HTTP, while traffic to the back-end subnet is limited to SQL, port 1433. |
| [Peer two virtual networks](./scripts/virtual-network-powershell-sample-peer-two-virtual-networks.md) | Creates and connects two virtual networks in the same region. |
| [Route traffic through a network virtual appliance](./scripts/virtual-network-powershell-sample-route-traffic-through-nva.md) | Creates a virtual network with front-end and back-end subnets and a VM that is able to route traffic between the two subnets. |
| [Filter inbound and outbound VM network traffic](./scripts/virtual-network-powershell-sample-filter-network-traffic.md) | Creates a virtual network with front-end and back-end subnets. Inbound network traffic to the front-end subnet is limited to HTTP and HTTPS. Outbound traffic to the internet from the back-end subnet is not permitted. |
