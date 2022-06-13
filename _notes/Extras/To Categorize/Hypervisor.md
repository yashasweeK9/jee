---
date created: Sunday, June 12th 2022, 1:26:58 pm
date modified: Sunday, June 12th 2022, 1:47:43 pm
title: Hypervisor
---

# Hypervisor

+ Hypervisor is a piece of software or firmware that creates and run Virtual Machines.
+ A Hypervisor is also called Virtual Machine Manager (VMM)

## 1. Types of Hypervisor

>[!lecpg] Lecture Slide marking Differences between Native and Hosted Hypervisor
>![](https://i.imgur.com/10frUyu.png)

### 1.A. Native

>[!conc] Concept
>![](https://i.imgur.com/0U1v1eU.png)
+ It is a piece of a Firmware
+ It is also called Bare Metal Hypervisor
+ Used majorly in enterprises
+ It runs directly on the sytem hardware.
+ A guest O.S runs on another level above the Hypervisor
+ ESXi being a Native Hypervisor runs on the host server hardware without an Underlying O.S
+ It acts as their own operting System.
+ It provieds a Virtualization Layer that abstracts C.P.U Resources of the Physical Host into multiple Virtual Machines.

### 1.B. Hosted

>[!conc] Concept of a Hosted Hypervisor
>![](https://i.imgur.com/3zlyuj1.png)

+ Here, Hypervisor acts as a Software.
+ Used majorly in Learning and Testing Process
+ Hypervisor that runs within the O.S Environment
+ It does not have direct access to the host Hardware and Resources.
