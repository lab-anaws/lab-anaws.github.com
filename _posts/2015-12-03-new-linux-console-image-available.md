---
layout: post
title: "New Linux Console image available"
description: ""
category: 
tags: []
---
{% include JB/setup %}

The Linux console image included into the Virtual Machine provided for Labs has the iperf3 tool bugged. 
In particular it evaluated wrong delays values and it might halt when loss is experienced. 
A new Linux Console image is provided for your convenience.
To upgrade run in the VM:

```
wget https://github.com/lab-anaws/lab6/raw/master/linux-core.qcow2
```

Create a new QEMU VM, using the default values and the linux-core.qcow2 file as hard drive. 
The QEMU binary to be used is qemu-system-x86_64 since the new image requires a 64-bit architecture.
