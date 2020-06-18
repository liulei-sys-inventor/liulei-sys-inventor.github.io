---
layout: archive
title: "Projects - Next Generation Computing"
permalink: /projects/
author_profile: true
---


**1. Next Generation OS - Leveraging AI to Enhance the OS Design and Build Core Mechanisms**
<span style="color:#c00000;text-indent:0cm;font-family:arial;font-size:14px;">News</span> - On 26/Nov, 2019, the technique report about our first step study (OSML) is available via this [**Link**](http://ddl.escience.cn/f/Usd1).

**2. Quantum Computing Systems**
<span style="color:#c00000;text-indent:0cm;font-family:arial;font-size:14px;">News</span> -On 25/April, 2020, the technique report - "A New Qubits Mapping Mechanism for Multi-programming Quantum Computing" - is available via this [**Link**](https://arxiv.org/pdf/2004.12854.pdf).

**3.** [**Memory Management for Large Memory Systems**](http://ddl.escience.cn/f/SwTR)

Now,  the memory system has much larger capacity than ever before. The  virtual and physical address translation brings significant overheads at  runtime in large memory systems. The Huge  page mechanism is proposed to reduce the TLB misses and benefit the  overall system performance. However, using huge pages might incur  expensive memory compaction operations due to memory fragmentation  problem, and lead to memory bloating. We  propose SysMon-H, a sampling module in the OS kernel, which can obtain  huge page utilization in a low overhead for both cloud and desktop  applications. Furthermore, we propose H-Policy, a huge page management  policy, which splits the underutilized huge pages to mitigate the memory  bloating or promotes the base 4KB pages to huge pages based on the  information provided by SysMon-H. The idea and first step effort are in **<span style="color:#953734;">ACM SIGOPS APSys-2019</span>**.

**4.** [**Non-Volatile Memory - Hybrid Memory Management for Tiered Memory Systems in OS**](http://ddl.escience.cn/f/QDZy)

The  emerging hybrid DRAM-NVM architecture is challenging the existing  memory management mechanism in operating systems. In this project, we  introduce Memos, which can hierarchically schedule memory resources over  the entire memory hierarchy including cache, channels, main memory  comprising DRAM and NVM simultaneously. Powered by our newly designed  kernel-level monitoring module (HyMM) and page migration engine, Memos  can dynamically optimize the data placement at the memory hierarchy in  response to the on-line memory patterns, current resource utilization  and memory medium features. The efforts are published in **<span style="color:#953734;">IEEE TPDS-2019 and ICCD-2016</span>**.

**5. Sysmon (2014~Now)**

A  light-weight OS-level system monitoring tool suite, which is able to  profile the memory utilization (including cache utilization, memory  footprint, approximate row-buffer locality, physical page level logic  re-use time, access frequency, hot/cold features and write/read  patterns) without any hardware supports. SysMon is especially useful in  VM and system-level research work. Sysmon is now open source on Github.  The beta version is introduced in ISCA-2014, TC-2016, and we further  discuss reducing the sampling overhead in APPT-2017 in detail.

**6.** [**Hierarchically Optimizting Data Placement across Cache and Memory Banks (2013~Now)**](https://arxiv.org/pdf/1704.01198.pdf)

To provide ideal **overall system throughput** and **QoS**,  in this project, the "Vertical Partitioning" is proposed to  cooperatively optimize the data placement across cache and DRAM banks.  We redesign the memory management component is OS kernel (e.g. buddy  system) according to memory architecture details, thus  "Vertical Partitioning" can simultaneously mitigate/eliminate the  memory interferences at the entire memory hierarchy (i.e. cache-bank).  Moreover, we further devise the "Curve-Vertical" Partitioning approach  to handle the diverse memory behaviors exhibited by the appearing  "memory-diversity" workloads on multi-core platforms. The efforts are  published in **<span style="color:#953734;">ISCA-2014 and IEEE TC-2016 (Featured article invited)</span>**. 

**7. Reducing Memory Conflicts: DRAM Bank/Channel Partitioning Mechanism (BPM/BPM+) on Real Systems (2011~Now)**

This  work begins with the contention and interference issue in main memory  systems, and I approach it from the Operating System angle. In existing  OS, memory resources are "blindly" allocated to applications (threads),  leading to memory contentions in DRAM Banks in the root. In order to  solve this problem, I extend the well-known **Page-Coloring**  to eliminate/mitigate the interferences between threads on memory banks  and channels. These studies help and motivate many works on improving  the overall system **throughput**, **locality** and **QoS**. More details are in **<span style="color:#953734;">PACT-2012 and ACM TACO-2014</span>**.

***<span style="color:#e36c09;">- We are glad to see these efforts from Sys-Inventors have had impact on scientific community and industry.</span>***



