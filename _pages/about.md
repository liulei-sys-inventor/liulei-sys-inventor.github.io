---
permalink: /
title: "Welcome to Sys-Inventor Lab!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---



## Brief Biography<span id="biography"></span>

Lei Liu is an Associate Professor of Computer Science at Institute of Computing Technology (ICT), Chinese Academy of Sciences  (CAS), where he leads the Sys-Inventor Lab, which is a part of the State Key Lab of Computer Architecture. Lei Liu serves as the Chief Engineer of National Supercomputing Center (Shenzhen). He joined the ICT faculty in 2014 after receiving his Ph.D. degree in computer science from ICT (his [Ph.D. thesis](/files/phd_thesis.pdf)). Besides,  he received his MS degree in software system design at University of Science and Technology of China (USTC), and BS degree in computer science at Dalian University of Technology (DLUT), respectively. He spent several years in industry as a software engineer and senior software architect. He was a visiting scholar in CS at the University of Rochester (UR).

He has led research projects that have advanced the cloud native technologies, involving  memory systems, OS, AI for Systems, performance isolation, and profiling. 1) Technical  evolutions for memory partitioning approaches; 2) Hybrid memory  management in OS for systems using NVM-DRAM; 3) Next generation OS - leveraging ML to build core components in OS; and 4) Quantum computing technologies. As the leading author (PI),  Lei has published research articles regarding the architecture and  operating system in venues that include ISCA, HPCA, PACT, IEEE TC, TPDS, ACM TACO, ICCD, and others. Recently, his work has focused on the  intersection of the hybrid memory system (DRAM-NVM), OS for emerging  technologies (including GPU, Graph, Quantum Computing as well as AI).

Lei Liu is an IEEE and ACM member, has served as the PC/ERC  members, chairs for a number of main stream conferences (e.g., MICRO,  HPCA, SC, PACT, ICS, IISWC, ISCA, ASPLOS, ICCD, ICPP, IPDPS, HPCC,  General co-Chair of IEEE IISWC-2020, ACM ICS-2018) and reviewer for well-known Transactions (ACM TACO, ACM JETC, ACM TECS, ACM TRTS, IEEE  TPDS). He received a number of awards.

His e-mail is: [lei.liu@zoho.com](mailto:lei.liu@zoho.com); [liulei2010@ict.ac.cn](mailto:liulei2010@ict.ac.cn)

<br/>

<div class="line-height1_5">
<p>刘磊，男，1981年9月出生于新疆乌鲁木齐市，祖籍辽宁沈阳，现任中科院计算所国重副研究员（Sys-Inventor实验室PI），研究生导师；兼任国家超算中心（深圳）总工程师（中组部挂职）。刘磊分别于大连理工大学、中国科学技术大学、中国科学院大学（中科院计算所）获得计算机科学与技术工学学士学位（导师：牛纪桢）、软件系统设计工程硕士学位（导师：赵振西）和计算机体系结构工学博士学位（<a href="/files/phd_thesis.pdf">博士论文链接</a>），并于2014年留计算所工作。在进入计算所之前，刘磊在工业界有5年的软件工程师、架构师及项目管理经验。刘磊于2017年5月～2018年4月在美国罗彻斯特大学计算机科学系交流访问。</p>
<p>刘磊的研究涉及“云原生”的一系列关键领域，包括现代操作系统（如OS+AI）、新型内存系统（NVM）、新计算机系统结构（量子计算机）、优化及可扩展性、系统性能评测等多个方面。自2011年起，刘磊带领其课题组研发了面向主流多核、多通道服务器，及异构内存体系的新内存资源管理系统原型；探索了新OS的智能化；探索了量子计算机体系结构、系统软件栈及支撑环境。相关研究成果以<b>第一作者并通讯作者</b>发表于ISCA, HPCA, PACT, IEEE TC, TPDS, ACM  TACO, ICCD等领域内权威学术会议和刊物，并在业内产生了影响力。近十年，刘磊曾主持或参与多项国家级项目（包括863、973、自然科学基金、重点研发计划等横纵项目，总计超1700余万元）；此外，他还担任了一系列权威国际学术会议的程序委员会委员、外部评审委员、组委会成员，及学术期刊的审稿人40余次（并2次担任ACM/IEEE权威学术会议的总主席）。刘磊曾获得“中国科学院院长优秀奖”、“国家奖学金”、“国科大优秀毕业生”、“计算所优秀科研人员” 等荣誉。</p>
<p>本实验室招收硕士、博士研究生及实习学生，欢迎对计算机系统结构有兴趣的同学和朋友。</p>
</div>


## Sys-Inventor Lab<span id="SIL"></span>

**The research in Sys-Inventor Lab focuses on <span style="color:#953734;">new strategies for next-generation Cloud native technologies</span>, covering the interaction of OS, emerging applications and hardware. Our Research Interests include:**

- New Trend, AI and Quantum Computer
- New Memory Architecture, e.g., NVM, Near Memory Computing, Memory Management and Optimization
- New Operating System, OS for Emerging Technologies and Applications
- Architectural Interaction and Resource Scheduling
- Profiling and Performance Evaluation



## Projects - Building Next-Generation Cloud Systems<span id="projects"></span>

1. **Next-Generation OS - Leveraging AI to Enhance the OS and Build Core Mechanisms**

     <span style="color:#c00000;">News</span> - On 26/Nov, 2019, the technique report about our first step study (OSML) is available via this [**Link**](/files/OSML___Lei_Liu.pdf).

2. **Quantum Computing for Cloud**

     <span style="color:#c00000;">News</span> - The first step effort - QuCloud - is in **<span style="color:#953734;">IEEE HPCA-2021 and PACT-2020</span>**.
  
   (i) The next-generation quantum computer architecture.
   
   (ii) Software stack, OS for making the quantum computer performs better.

   (iii) Quantum computing simulation as well as AI.  

3. [**Memory Management for Large Memory Systems**](/files/apsys-2019-final.pdf)

   Now, the memory system has a much larger capacity than ever before. The virtual and physical address translation brings significant overheads at runtime in large memory systems. The Huge page mechanism is proposed to reduce the TLB misses and benefit the overall system performance. However, using huge pages might incur expensive memory compaction operations due to memory fragmentation problem, and lead to memory bloating. We propose SysMon-H, a sampling module in the OS kernel, which can obtain huge page utilization in a low overhead for both cloud and desktop applications. Furthermore, we propose H-Policy, a huge page management policy, which splits the underutilized huge pages to mitigate the memory bloating or promotes the base 4KB pages to huge pages based on the information provided by SysMon-H. The idea and first step effort are in **<span style="color:#953734;">ACM SIGOPS APSys-2019</span>**.

4. [**Non-Volatile Memory - Hybrid Memory Management for Tiered Memory Systems in OS**](/files/Memos-TPDS-2019.pdf)

   The emerging hybrid DRAM-NVM architecture is challenging the existing memory management mechanism in operating systems. In this project, we introduce Memos, which can hierarchically schedule memory resources over the entire memory hierarchy including cache, channels, main memory comprising DRAM and NVM simultaneously. Powered by our newly designed kernel-level monitoring module (HyMM) and page migration engine, Memos can dynamically optimize the data placement at the memory hierarchy in response to the on-line memory patterns, current resource utilization and memory medium features. The efforts are published in **<span style="color:#953734;">IEEE TPDS-2019 and ICCD-2016</span>**.

5. **Sysmon (2014~Now)**

   A light-weight OS-level system monitoring tool suite, which is able to profile the memory utilization (including cache utilization, memory footprint, approximate row-buffer locality, physical page level logic re-use time, access frequency, hot/cold features and write/read patterns) without any hardware supports. SysMon is especially useful in VM and system-level research work. Sysmon is now open source on Github. The beta version is introduced in ISCA-2014, TC-2016, and we further discuss reducing the sampling overhead in APPT-2017 in detail.

6. [**Hierarchically Optimizting Data Placement across Cache and Memory Banks on Cloud Servers (2013~Now)**](https://arxiv.org/pdf/1704.01198.pdf)

   To provide ideal **overall system throughput** and **QoS**, in this project, the "Vertical Partitioning" is proposed to cooperatively optimize the data placement across cache and DRAM banks. We redesign the memory management component is OS kernel (e.g. buddy system) according to memory architecture details, thus "Vertical Partitioning" can simultaneously mitigate/eliminate the memory interferences at the entire memory hierarchy (i.e. cache-bank). Moreover, we further devise the "Curve-Vertical" Partitioning approach to handle the diverse memory behaviors exhibited by the appearing "memory-diversity" workloads on multi-core platforms. The efforts are published in **<span style="color:#953734;">ISCA-2014 and IEEE TC-2016 (Featured article invited)</span>**. 

7. **Reducing Memory Conflicts on Real Cloud Servers - DRAM Bank/Channel Partitioning Mechanism (BPM/BPM+) (2011~Now)**

   This work begins with the contention/interference issues in main memory systems, and I tackle them from the Operating System angle. In existing OS, memory resources are "blindly" allocated to applications (threads), leading to memory contentions in DRAM Banks in the root. In order to solve this problem, I extend the well-known **Page-Coloring** to eliminate/mitigate the interferences between threads on memory banks and channels. These studies help and motivate many works on improving the overall system **throughput**, **locality** and **QoS**. More details are in **<span style="color:#953734;">PACT-2012 and ACM TACO-2014</span>**.

   ***<span style="color:#e36c09;">- We are glad to see these efforts from Sys-Inventors have had impact on scientific community and industry.</span>***


## Publications<span id="publications"></span>
1. [QuCloud: A New Qubit Mapping Mechanism for Multi-programming Quantum Computing in Cloud Environment](/files/QuCloud_HPCA_2021_ready.pdf) [[**<span style="color:#953734;">Slides (pptx)</span>**](/files/QuCloud.pptx)]

    **Lei Liu\***, Xinglei Dou. The 27th IEEE International Symposium on High-Performance Computer Architecture **(HPCA)**:2021   

2. [The Evolution of Memory Partitioning Technologies: A Case Study through Page Coloring](/files/JS2021.pdf)

   Jiefan Qiu, Zonghan Hua, Jing Fan, **Lei Liu\***. Journal of Software in Chinese **(软件学报)**:2021

3. [An Investigation into Quantum Program Mapping on Superconducting Quantum Computers](/files/JCRD-2021.pdf)
    
   Xinglei Dou, **Lei Liu\***, Yuetao Chen. Journal of Computer Research and Development in Chinese **(计算机研究与发展)**:2021
 
   ***<span style="color:#ca6a20;">- Special Issue on Quantum Computing in J. of Computer R&D</span>***

4. Quantum Computing Simulations and Optimizations: A Survey

   Zhichao Yu, Yangzhong Li, **Lei Liu\*** and Shengzhong Feng. Computer Engineering in Chinese **(计算机工程)**:2021

   ***<span style="color:#ca6a20;">- Invited Article in J. of Computer Engineering</span>***
 
5. [IEEE Proceedings of the IEEE International Symposium on Workload Characterization, Virtual. October 27-29, 2020](https://ieeexplore.ieee.org/xpl/conhome/9251098/proceeding)

    **General co-Chair**. IEEE 16th International Symposium on Workload Characterization  **(IISWC)**:2020   

6. A New Qubits Mapping Mechanism for Multi-programming Quantum Computing [[**<span style="color:#953734;">Slides (pptx)</span>**](/files/quantum_talk.pptx)]

    Xinglei Dou, **Lei Liu\***. The 29th ACM/IEEE Intl. Conf. on Par. Architectures and Compilation Tech. **(PACT)**:2020 ([Poster](/files/Quantum_PACT_2020-2.pdf))

7. [QoS-Aware Resources Scheduling for Microservices: A Multi-Model Collaborative Learning-based Approach](/files/OSML___Lei_Liu.pdf)

    **Sys-Inventor Technical Report (PI: Lei Liu)**:2020

8. An Analysis for Evolution of Memory Partitioning Technologies: Perspective, Opportunities and Methods

    **Sys-Inventor Technical Report (PI: Lei Liu)**:2020

9. [Monitoring Memory Behaviors and Mitigating NUMA Drawbacks on Tiered NVM Systems](/files/NPC2020.pdf) [[**<span style="color:#953734;">Slides (pptx)</span>**](/files/NVM.pptx)]

    S. Yang, X. Li, X. Dou, X. Gong, H. Liu, L. Chen, **L. Liu\***. The 17th IFIP Intl. Conf. on Network and Par. Computing **(NPC)**:2020

10. [Hierarchical Hybrid Memory Management in OS for Tiered Memory Systems](/files/Memos-TPDS-2019.pdf)

    **Lei Liu\***, Shengjie Yang, Lu Peng, Xinyu Li. IEEE Transactions on Parallel and Distributed Systems **(TPDS)**:2019

11. Architectural Support for NVRAM Persistence in GPUs

    Sui Chen, **Lei Liu**, Weihua Zhang, Lu Peng. IEEE Transactions on Parallel and Distributed Systems **(TPDS)**:2019

12. Efficient GPU NVRAM Persistence with Helper Warps

    Sui Chen, Faen Zhang, **Lei Liu** and Lu Peng. The 56th ACM/ESDA/IEEE Design Automation Conference **(DAC)**:2019

13. [Thinking about A New Mechanism for Huge Page Management](/files/apsys-2019-final.pdf)  [[**<span style="color:#953734;">Slides (pptx)</span>**](/files/apsys-2019.pptx)]

    Xinyu Li, **Lei Liu\***, Shengjie Yang, Lu Peng, Jiefan Qiu. The 10th ACM SIGOPS Asia-Pacific Workshop on Systems **(APSys)**:2019

14. [ACM Proceedings of the 2018 International Conference on Supercomputing, Beijing, China. June 12-15, 2018](https://portalparts.acm.org/3210000/3205289/fm/frontmatter.pdf?ip=159.226.43.53)

    **General co-Chair**. ACM 32nd International Conference on Supercomputing **(ICS)**:2018

15. [Tackling Diversity and Heterogeneity by Vertical Memory Management](/files/vp.pdf) 

    **Lei Liu**.[ arXiv:1704.01198](https://arxiv.org/abs/1704.01198):2017 **(Short Version for the ISCA-2014 Paper)**

16. [Memos: Revisiting Hybrid Memory Management in Modern Operating System](https://pan.cstcloud.cn/s/NV5GdcN3T3A)

    **Lei Liu\***, Mengyao Xie and Hao Yang.[ arXiv:1703.07725](https://arxiv.org/abs/1703.07725):2017

17. [SysMon: Monitoring Memory Behaviors via OS Approach](/files/appt2017-sysmon-myx.pdf)

    Mengyao Xie, **Lei Liu\***, Hao Yang, Chenggang Wu, Hongna Geng. The 12th Intl. Symp. on Adv. Par. Processing Tech. **(APPT)**:2017

18. [Memos: A Full Hierarchy Hybrid Memory Management Framework](/files/ICCD_8.pdf) (Position Paper)

    **Lei Liu\***, Hao Yang, Mengyao Xie, Lian Li, Chenggang Wu. The 34th International Conf. on Computer Design **(ICCD)**:2016

19. [Rethinking Memory Management in Modern Operating System: Horizontal, Vertical or Random?](/files/tc-2015-pass19.pdf)  [[**<span style="color:#953734;">Slides (pptx)</span>**](/files/All in TC.pptx)] 

    **Lei Liu\***, Chen Ding, Hao Yang, Chengyong Wu. IEEE Transactions on Computers **(TC)**:2016

    ***<span style="color:#ca6a20;">- Trans. Version of the ISCA-2014 paper. This article was a featured article candidate in IEEE TC.</span>***

20. Going Vertical in Memory Management

    **Lei Liu\***, et al. **ACM SIGARCH Computer Architecture News**:October, 2014

21. [Going Vertical in Memory Management: Handling Multiplicity by Multi-policy](/files/ISCA2014_FINAL_pass2.pdf)  [**[<span style="color:#953734;">Slides (pptx)</span>](/files/ISCA2014.pptx)**] 

    **Lei Liu\***, et al. The 41st ACM/IEEE International Symposium on Computer Architecture **(ISCA)**:2014 

    ***<span style="color:#ca6a20;">- The 9th ISCA paper in mainland China history since y2k.</span>*** 

22. [BPM/BPM+: Software-based Dynamic Memory Partitioning Mechanisms for Mitigating DRAM Bank-/Channel-level Interferences in Multicore Systems](/files/taco_pass24.pdf)

    **Lei Liu\***, et al. ACM Transactions on Architecture and Code Optimization **(TACO)**:2014 

23. [A Software Memory Partition Approach for Eliminating Bank-level Interference in Multicore Systems](/files/pact140-liu-final.pdf)  [[**<span style="color:#953734;">Slides (pptx)</span>**](/files/pact-liu-presentation.pptx)]

    **Lei Liu\***, et al. The 21st ACM/IEEE International Conference on Parallel Architectures and Compilation Techniques **(PACT)**:2012 

    ***<span style="color:#ca6a20;">- Influential Article in Semantic Scholar. Cited Greater than 200 Citations.</span>***

24. WiseThrottling: A New Asynchronous Task Scheduler for Mitigating I/O Bottleneck in Large-Scale Datacenter Servers

    Fang Lv\*, **Lei Liu**, Huimin Cui, Lei Wang, Ying Liu, Xiaobing Feng, P.C. Yew (UMN). J. of Supercomputing:2015

25. Dynamic I/O-Aware Scheduling for Batch-Mode Applications on Chip Multiprocessor Systems of Cluster Platforms

    Fang Lv\*, Huimin Cui, Lei Wang, **Lei Liu**, Cheng-Gang Wu, Xiao-Bing Feng, and Pen-Chung Yew (UMN). JCST:2014


      [<span style="text-decoration:none;">G</span><span style="color:#ff0000; text-decoration:none;">o</span><span style="color:#ffc000; text-decoration:none;">o</span><span style="text-decoration:none;">g</span><span style="color:#00b050;text-decoration:none;">l</span><span style="color:#ff0000;text-decoration:none;">e</span><span style="text-decoration:none;"> Citation</span>](https://scholar.google.com.hk/citations?user=yhN8bmgAAAAJ&hl=en), * corresponding author


## Patents<span id="patents"></span>

1. 一种微服务资源调度系统和方法 (Chinese Version). **First Inventor** 

2. 一种消除远程非易失性内存访问的进程调度技术 (Chinese Version). **First Inventor**

3. [Memory Resource Optimization Method and Apparatus (PCT, US).](https://patents.google.com/patent/US9857980B2/en) **First Inventor (with Wu and Feng)**. 

4. 一种存储器资源优化方法和装置 (Chinese Version). **First Inventor (with Wu and Feng). 发明人：刘磊、吴、冯晓兵**.
   
    ***<span style="color:#ca6a20;">- Part of the ideas in ISCA-2014 is within.</span>***



## Others<span id="others"></span> 
1. 成功举办IISWC-2020（IISWC-2020 is successful! News in Chinese via [ICT link](http://www.carch.ac.cn/xwdt/sysxw/202011/t20201110_590983.html)）

2. [成功举办ACM ICS-2018](/files/ics.pdf)（ACM ICS-2018 is successful! News in Chinese via [ICT link](http://www.ict.ac.cn/xwzx/jssxw/201806/t20180628_5032541.html)）

3. [多核系统内存资源管理优化技术的研究](/files/最终版本.pdf)（博士学位论文，导师：吴、冯；涵盖本人发表在ISCA、PACT、TACO的成果; Lei's Ph. D. dissertation in Chinese, covering his work in ISCA, PACT and TACO. Supervisor: Wu and Feng）[出版物链接（BOOK）](https://www.morebooks.de/store/gb/book/%E5%A4%9A%E6%A0%B8%E7%B3%BB%E7%BB%9F%E5%86%85%E5%AD%98%E8%B5%84%E6%BA%90%E7%AE%A1%E7%90%86%E4%BC%98%E5%8C%96%E6%8A%80%E6%9C%AF%E7%9A%84%E7%A0%94%E7%A9%B6/isbn/978-3-330-82280-1)

    Defense Committee (May/2014): Fengbin Qi (漆锋斌), Zhaoqing Zhang (张兆庆), Zifeng Hou (侯紫峰), Zhiyong Liu (刘志勇), Wenguang Chen (陈文光), Zhimin Tang (唐志敏), Xiaodong Zhang (张晓东)

4. [编译技术的领路人－谨祝国重编译组张兆庆研究员获得“夏培肃奖”](/files/张兆庆老师获得“夏培肃奖”.pdf)（Invited Essay in Chinese）

5. [PACT-2015 PC会议记录与硅谷工业界访问之行](/files/PACT-2015 PC副本.pdf)（Invited Essay in Chinese）

6. [ISCA-2014与北美学术之旅](/files/ISCA-2014与北美学术之旅.pdf)（Invited Essay in Chinese）

7. [Page Coloring的历史与发展](/files/Page Coloring的历史与发展.pdf)（Invited Survey in Chinese）



## Recent Professional Serivces<span id="services"></span>

1. General co-Chair of IEEE [IISWC-2020](http://www.iiswc.org/iiswc2020/index.html)
2. General co-Chair of ACM [ICS-2018](http://ics2018.ict.ac.cn/) (Record attendance! and Record submission in recent 5 years!)
3. Member of the Program Committee of ISCA-2022
4. Member of the Program Committee of MICRO-2020 (Chair of NVM session), 2021
5. Member of the Program Committee of PPoPP-2022
6. Member of the Program Committee of HPCA-2020
7. Member of the Program Committee of IPDPS-2020
8. Publicity co-Chair of IEEE [IISWC-2019](http://www.iiswc.org/iiswc2019/index.html)
9. Member of the Program Committee of SC-2019
10. Member of the Program Committee of ICCD-2018, 2019, 2020
11. Member of the Program Committee of APPT-2019
12. Member of the External Review Committee of HPCA-2019
13. Member of the Program Committee of IISWC-2017, 2021
14. Member of the Program Committee of ICPP-2017, 2020
15. Member of the Program Committee of ICS-2017, and Chair of Session 5
16. Member of the Program Committee of PACT-2015, 2016 (ERC), 2019 (ERC)
17. Member of the External Review Committee of ISCA-2016, 2021
18. Member of the Program Committee of IEEE IPDPS-2016
19. Member of the Program Committee (ERC) of ASPLOS-2016, 2017, 2018 (Chair of Session Run time, and SRC Judge), 2022
20. Member of the Program Committee of HPCC-2015, 2016
21. Member of the Program Committee of HP3C-2017, 2018, 2019
22. Reviewer of ACM TACO, ACM JETC, ACM TECS, ACM TRTS, ACM Transactions on Quantum Computing, JPDC, IEEE TPDS, IEEE CAL
23. Review Expert of National Science Foundation of China (NSFC)
24. 《计算机工程》青年编委、审稿人



## Recent News<span id="news"></span>

- "QuCloud" is accepted by HPCA-2021. Congratulations!
- Get a new funding from NSFC (2021~2024) for the research "An Investigation into the Key Technologies of Software Stack Design and Optimization for the Heterogeneous Memory and Computing Systems". Congratulations to Sys-Inventors!
- The first step effort on quantum computing is accepted as a poster by PACT-2020.
- **<span style="color:red">[Plz Note]</span>**:  I am Lei Liu (刘磊 in Chinese); I have nothing to do with the Mulan  project in ICT. The leader of this project has the same name in English  but not with the same Chinese characters. Thanks for your understanding.  More details on my work and myself can be found in this page. 
  请注意，我的名字是刘磊，我从未参与过“木兰”语言项目，研究领域也不是编程语言。该项目的负责人只是与我拼音名字相同而已。
- We  will host IEEE IISWC-2020, and I myself will serve as the chair in  general for this event. Looking forward your contributions! <a href="http://www.iiswc.org/iiswc2020/index.html"><img style="float:none;width:35px;height:48px;" width="35" vspace="0" hspace="0" height="48" border="0" src="/images/iiswc_2020.jpg"/></a>
- I am visiting LSU and College of William and Mary from 9~13/Dec 2019. The topic is "[**Achieving Better Resource Scheduling through Enhanced OS and ML Technologies**](/files/201912 - LSU-WM.pptx)".
- A paper from Sys-Inventor Lab is accepted by APSys-2019. The topic is on huge page management in OS. 
- Prof. Michael Scott visits us on 13/May, 2019. His talk is [**Systems Support for Persistent ‘In-Memory’ Data**](/files/persistence.pdf).
- Looking forword your submissions to IEEE **IISWC-2019**.
- A  paper with the topic on hybrid memory management for DRAM-NVM from  Sys-Inventor Lab is accepted by IEEE TPDS-2019. Congratulations!
- A paper co-authored with Lu Peng's group (the leading author was within) at LSU is accepted by DAC-2019.  
- Congratulations for the success of the ICS-2018. Thank people who contributed to this event. Prof. Mateo Valero's [**Keynote slides**](https://pan.cstcloud.cn/s/7R1ezKAPS0I) and Prof. Hironori's [**Keynote slides**](/files/ICS2018HKasahara20180613.pdf) for ICS-2018 are avaiable here. 
- ICS-2018 is going to start tomorrow. Thanks for your coming! 
- Hope you could [**submit**](http://ics2018.ict.ac.cn/#submissions/) your excellent work to **ICS-2018**! Here is the **CFP**. Here is the **Call for Workshop**.
- A paper is accepted in APPT-2017. 
- I am now visiting the CS department at U. of Rochester. <a href="http://www.cs.rochester.edu/" target="_blank"><img tabindex="0" style="width:30px;height:30px;float:none;" alt="cs.rochester.edu" src="/images/rochester.gif" data-bm="51" width="30" vspace="0" hspace="0" height="30" border="0"></a>
- [**ICS-2017**](http://press3.mcs.anl.gov/ics2017/) will be hold in Chicago. You are expected to submit your excellent work. Hope to see you there.:)
- Lei Liu is promoted (1/33,14/15). Thank all of my friends. :)
- A paper is accpeted in ICCD-2016, to appear at the conference in Phoenix, AZ, US. 
- <span style="color:red">**[Good News]**:</span> [**ICS-2018**](http://ics2018.ict.ac.cn/)  will be hold in Beijing, hosted by SKL, ICT, organized by Lei Liu,  Michael Gschwind, Avi Mendelson, P-C Yew and Xiaobing Feng, etc. Come and join us, and let us make ICS a great success in China! 
- I will go to attend ICS-2016 from 1/June to 3, in Istanbul, and bid for ICS-2018, Beijing. Good Luck for all of our colleagues! 
- Best Wishes to all of my friends and collaborators! I wish you a very happy and fruitful new year, 2016, way to go!
- Happy  Teachers' Day （教师节快乐） on 10/9/2015! I would like to extend my deep  thanks to Prof. Zhang, Wu and Feng for their help in my Ph.D., and on  behalf of professors in compiler team, I would like to extend our thanks  to all of the students! You are the pride of us! Stay hungry, Stay  foolish.
- Our  research entitled "An Investigation into Asymmetry Multi-Channel  Architecture for Supporting Heterogeneous Memory System and the  Corresponding Heuristic Memory Management Mechanism" will be supported  by a new funding from Natural Science Foundation (NSF) of China from  2016 to the end of 2018. Congratulations to Sys-Inventors!
- I am visiting VMware (CA,US) and Huawei research center (CA,US) from 27/July ~ 3/Aug 2015. The theme is "[Rethinking Memory Management in Modern Operating System -- Memory Optimization by Leveraging Hardware Features](/files/2015北美华为副本.pptx)".
- Congratulations! The paper entitled "Rethinking Memory Management in Modern Operating System" from our **Sys-Inventor**  group in Compiler team is Accepted by IEEE Trans. on Computers! Thank  all of the authors for their contributions. On behalf of the authors in  this paper, I would like to extend my deep thanks to these who pay  attentions on our work for their valuable comments, especially Prof.  Xiaodong Zhang (Ohio), P. C. Yew (UMN). This is a further step of our  work in ISCA-2014, and more details of new findings are presented in  this paper. You are expected to read [**it**](/files/tc-2015-pass19.pdf).
- Hao Yang and Mengyao Xie joined us. Welcome!
- I am visiting VMware in Palo Alto. CA US. (will give a talk about system optimization on 23 June 2014, Monday).  
- I go now to attend ISCA-2014 in MN US., and will present "Going Vertical in Memory Management" on 16 June Monday.  
- Congratulations! The paper "Going Vertical in Memory Management: Handling Multiplicity by Multi-policy" from our **Sys-Inventor** group in Compiler team was accepted by ISCA-2014.
- Congratulations! The further work on DRAM Bank partitioning from **Sys-Inventor**, BPM/BPM+, was accepted by ACM TACO-2014.
- Congratulations! The work on DRAM Bank partitioning from **Sys-Inventor**, was accepted by PACT-2012.



## Awards and Honors <span id="honors"></span>

- Outstanding Faculty Award, SKLCA, ICT, 2019
- 100-Academic-Stars Program, ICT, 2017
- Outstanding Scientific Researcher (Outstanding Faculty Award), ICT, 2015
- National Scholarship for Ph.D
- Chinese Academy of Sciences President's Award for Excellence, Chinese Academy of Sciences
- Outstanding Graduates, Chinese Academy of Sciences
- Advanced Individual in State Key Lab. of Computer Architecture, ICT
- The Bewinner Communications (北纬通信) Second Prize for Self-dependent Innovation
- Merit student, Chinese Academy of Sciences

## Academic Genealogy <span id="Genealogy"></span>

<div class="para-set">
<p>Lei Liu Ph.D, 2014, ICT, CAS</p>
<p>Xiaobing Feng Ph.D, 1999, ICT, CAS; Chengyong Wu Ph.D, 2000 (He is a monk and has passed away. Mourns in memoriam)</p>
<p>Zhaoqing Zhang 1960, PKU</p>
</div>

## Resume References<span id="references"></span>

Yunquan Zhang (ICT), Xiaobing Feng (ICT), Xiaowei Li (ICT), Guangyu Sun (PKU), Bin Ren (WM), Scott Michael (Rochester), P-C Yew (UMN)

## People <span id="People"></span>

**Students**

- Xinglei Dou (B.S., Jilin U.)
- Yuetao Chen (B.S., Beijing Jiaotong U. - Weihai)
- Xinyu Li (B.S., SJTU)

**Former Students** (including interns, part-time co-supervised ones)

- Shengjie Yang, Master 2021, Tencent; Outstanding graduate honor of ICT and UCAS (2%), Excellent dissertation
- Zonghan Hua, Master 2021, The People's Bank of China, Zhejiang; Excellent guest student award in SKLCA
- Hao Yang, Master 2017, Huawei
- Mengyao Xie, 9/2015~4/2018
- Hongna Geng, 10/2016~4/2018 
- Yong Li, 2014, intern, first job - engineer in VMware; co-supervised since 2013 to 2015 and A. K. Jones (PITT)
- Zehan Cui, 2015, intern, first job - ICT till 2016; co-supervised since 2011 to 2012 and Mingyu Chen


## Recommendations<span id="recommendations"></span>

- Prof. Mark D. Hill's Keynote at IISWC-2019 is [here](/files/ALP_orlando2019_11 (1).pptx).
- Prof. Lizy K. John's talk at IISWC-2019 workshop is [here](/files/IISWC2019-workshop.pdf).
- Prof. Michael Scott's talk at ICT is [here](/files/persistence.pdf).
- Prof. Mateo Valero's [Keynote slides](https://pan.cstcloud.cn/s/7R1ezKAPS0I) and Prof. Hironori's [Keynote slides](/files/ICS2018HKasahara20180613.pdf) for ICS-2018
- [The Three Golden Rules for Successful Scientific Research](https://www.cs.utexas.edu/users/EWD/transcriptions/EWD06xx/EWD637.html)
- Lei Liu's [web on University of CAS (中国科学院大学)](http://people.ucas.ac.cn/~liulei2010),[ Linkedin](https://www.linkedin.com/in/%E7%A3%8A-lei-%E5%88%98-liu-b750a8148) and [Researchgate](https://www.researchgate.net/profile/Lei_Liu213).
- [Conf. Information](http://confsearch.ethz.ch/confsearch/) in Computer Science. You will never miss your conference.:)
- [Worse-case Reviewing](https://www.sigarch.org/want-people-to-read-your-paper-consider-the-worst-case-reviewer/)
- [\[更正\] ISCA2016: 计算机体系结构顶会CNN走红，神经网络论文夺桂冠](http://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2651984404&idx=2&sn=4f776dbaaa9bf49f799dd8e780f5e184&cene=2&srcid=0705GexRpXBlYKd5LYJl06GM&from=timeline&isappinstalled=0#wechat_redirect)
- [\[体系结构顶会Micro2016\] 神经网络加速器仍是热点，但图计算加速器夺最佳论文](http://mp.weixin.qq.com/s/XyN1kK-1kTrCmzOOVVmtEw)
- [论文署名，学术不端和不正当竞争（转自科学网）](http://blog.sciencenet.cn/blog-111883-638376.html)


## Postal Address<span id="address"></span>

<div class="para-set">
<p>Address: 北京海淀区中关村科学院南路6号0612J (0612J, No.6, Kexueyuan South Road, Zhongguancun, Haidian District, Beijing, China)。</p>
<p>Post Code: 100190</p>
</div>


