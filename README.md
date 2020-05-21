# QueenieCplusplus/QuickGoThru

本儲存庫繼續保留以往 C++ 高階 OOP 語言和 Python 腳本之特色，其他包含 Data Structure、Search Engine 的相關研究著作，現在議題包羅了 IT Security & Hack on Browser & Netwroking 和資料擷取和嗅探 Parser & Extracter 、 Data Mining，未來將研究 ARM (韌體程式邏輯) & Kernel Hacks (系統核心開發)，請拭目以待！

# ARM

preserved in Future !

# Linux Shell 
since 2020.5/21 ~ 5/24

![linux shell](http://www.drmaster.com.tw/Cover/big/MP21617.jpg)

* Shell & Bash

     * String
 
     * Computing Operation

     * Flow Control
  
* Common Utility

  * Process & IPC

  * File

  * Media (Graph, Window, Sound)

* Network

  * ifconfig
  
  * route
  
  * ssh
  
  * ping

* Sys Admin

  * sudo or root
  
  * cpu and memory
  
  * auth

# Bash  (Shell Scripts for Unix)
since 2018.5 & 2019.4 & 2020.5/18 ~ 5/21 ![bash shell](https://cf-assets2.tenlong.com.tw/products/images/000/106/490/original/9789864763672.jpg?1525538893)

* POSIX

  https://github.com/QueenieCplusplus/POSIX

* Programming

  * echo
  
  https://github.com/QueenieCplusplus/Shell_echo

  * dir & file
  
  https://github.com/QueenieCplusplus/Shell_inPath
  
  * grep & trap
  
  https://github.com/QueenieCplusplus/Shell_grep

* Tools

  * compress
   
  https://github.com/QueenieCplusplus/Shell_compress

  * date & timestamp & calendar_tool
  
  https://github.com/QueenieCplusplus/Shell_time

  * calculator
  
  https://github.com/QueenieCplusplus/Shell_calculator

* Sys Admin

  * df & disk
  
  https://github.com/QueenieCplusplus/Shell_df

* WWW

  * FTP & URL
  
  https://github.com/QueenieCplusplus/Shell_ftp
  
  https://github.com/QueenieCplusplus/Shell_url

# SQL 
since 2019.7-8 & 2020.5/10-5/15

![threads session pool connection db](https://mobisoftinfotech.com/resources/wp-content/uploads/2018/04/Understanding-DB-Connection-Pools-Architecture.png)

* Preview : 

https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#dba

https://github.com/QueenieCplusplus/QuickGoThru#搜索引擎

* Review :  

1. https://github.com/QueenieCplusplus/SQL_Concepts

2. https://github.com/QueenieCplusplus/SQL_DDL

3. https://github.com/QueenieCplusplus/SQL_DML

4. https://github.com/QueenieCplusplus/SQL_DCL

5. https://github.com/QueenieCplusplus/SQL_Session

6. https://github.com/QueenieCplusplus/Stateless_and_Stateful

* Main Study :

# Hadoop
since 2019.12 & 2020.5/16 ~

* Main Charaters:

1. 分散式存儲，並且採叢集管理。

2. 單筆檔案相對傳統來得大，約莫 500 MB 。

3. 檔案中間內容無法被竄改，只能在尾部增加，概念類似區塊鏈。

* Preview:

https://github.com/QueenieCplusplus/DataStorage_Hadoop (安全議題)

* Review:

https://github.com/QueenieCplusplus/Hadoop_and_IOE (趨勢與潮流)

https://github.com/QueenieCplusplus/GFS_and_BigTable (起源與契機)

https://github.com/QueenieCplusplus/MapReducer (運算架構基礎)

https://github.com/QueenieCplusplus/DataMining_Spark (分散式運算框架)

https://github.com/QueenieCplusplus/DataMining_Spark#spark--hadoop (Hadoop & Spark)

* Bound-Oriented 應用密集的導向：

1. Storage Bound, 存儲密集的應用

2. CPU/Memory Bound, 運算密集的應用

3. IO Bound, 網路密集的應用

# PostgreSQL
since 2020.3 and 2020.5/17~

* Preview:

https://github.com/QueenieCplusplus/PostgreSQL

https://github.com/QueenieCplusplus/QuickGoThru#搜索引擎

* Review:

![postgresql](https://covers.oreillystatic.com/images/0636920052715/lrg.jpg)

https://github.com/QueenieCplusplus/PSQL_command_tool (below version 9.2)

https://github.com/QueenieCplusplus/PSQL_interactive_cli (below version 9.2)

* Where it hosts on:

https://github.com/QueenieCplusplus/PostgreSQL_Hosts

* Table & Functions

(to be continued...)

# Kernel Hackers
since 2020/4/30-5/02
![kernels](https://scontent.ftpe8-4.fna.fbcdn.net/v/t1.0-9/92057070_4153295244684252_4015601745232134144_o.jpg?_nc_cat=102&_nc_sid=2d5d41&_nc_ohc=Ysv86wkyPncAX-zxlqN&_nc_ht=scontent.ftpe8-4.fna&oh=e959864002d891a9e194b16337e3d8ac&oe=5EB037F0)

* Source Mgmt

   * Cgroup 
   
      https://github.com/QueenieCplusplus/Kernel_Cgroup
   
   * Namespace
   
      https://github.com/QueenieCplusplus/Kernel_Namespace
   
   * Container （容器）
   
    使用 Cgroup 分割 CPU 和 Memory 資源與 Namespace 切割網路和 PID 資源所實現的。
    
   * Block I/O
   
      https://github.com/QueenieCplusplus/Kernel_BlockIO
   
   * VM
   
   (如下 bypass，筆者已於編寫 C++ 和研發 Android 系統時研究過。)
   
   * Scheduling   
   * Memory   
   * OOM Killer   
   
* Network

    https://github.com/QueenieCplusplus/Kernel_Network/blob/master/README.md

* VM

* Process Call & Event Log

* Kernel Tracing using System Tap

# CCNP (OSI Layer 2-3)
since 2020/4/27-29, 5/04


                          CORE

                           |

                       Distributin

                           |

                         Access

* Layer 2 

     *  Data Link
     
     https://github.com/QueenieCplusplus/CCNP_DataLink

* Layer 3

     * EIGRP (routing tables integration amongs routers and sw)
     
     https://github.com/QueenieCplusplus/CCNP_EIGRP

     * OSPF (forward packets amongst AS)
     
     https://github.com/QueenieCplusplus/CCNP_OSPF

# VM (Hyper-V||VMware)
since 2020/4/22, 23 

https://github.com/QueenieCplusplus/VM

# System Security (SSCP)
since 2020/4/13, 21, 22, 24

https://github.com/QueenieCplusplus/SSCP

![sscp](https://scontent.ftpe8-2.fna.fbcdn.net/v/t1.0-9/93308664_154086846081152_7897672463310389248_o.jpg?_nc_cat=103&_nc_sid=8024bb&_nc_ohc=quXC3I7Ue1sAX_T6QoC&_nc_ht=scontent.ftpe8-2.fna&oh=258bc5a665e99e0738a102e00681c6f9&oe=5EB7A3CC)


# C Again
since 2020/4/07 - 4/08, 4/11

https://github.com/QueenieCplusplus/Linux_sys_program/blob/master/README.md

![linux_sys_program](https://scontent.ftpe8-2.fna.fbcdn.net/v/t1.0-9/92228449_4150166321663811_8556874175728320512_o.jpg?_nc_cat=101&_nc_sid=2d5d41&_nc_ohc=I-y87Xkp9e8AX9q8KLN&_nc_ht=scontent.ftpe8-2.fna&oh=0ce0edfcf0ce397c374a383fce4c5e67&oe=5EAF4D40)

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# Perl Again
since 2020/4/04 - 4/06

https://github.com/QueenieCplusplus/Perl_Again

![perl](https://scontent.ftpe8-2.fna.fbcdn.net/v/t1.0-9/91909804_4142636599083450_5917151593018425344_o.jpg?_nc_cat=101&_nc_sid=2d5d41&_nc_ohc=ofXp29-FLr8AX9imAvk&_nc_ht=scontent.ftpe8-2.fna&oh=de7ca1e48c0891f58998ff077646ef0b&oe=5EADA18F)

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 網路拓樸技術
since 2020/3/28 - 4/03, 5/03

![net](https://scontent.ftpe8-3.fna.fbcdn.net/v/t1.0-9/91250330_4131843193496124_7225672568689131520_o.jpg?_nc_cat=111&_nc_sid=2d5d41&_nc_ohc=NasdR3yOZjsAX-P1vfI&_nc_ht=scontent.ftpe8-3.fna&oh=aafcfcba4b5ce5ae513ad97fc6a99ec2&oe=5EAC85D2)

* Routing Protocol Selection Criteria:

- [X] MTU

- [X] Routing Loop Prevention

- [X] Hop Count

- [X] Bandwidth 

- [X] Cost

- [X] Load

- [X] Delay

- [X] Reliability

＿＿＿＿＿＿

* AS:

   * https://github.com/QueenieCplusplus/IGP_and_BGP (自治系統網路架構間的網路設計)

＿＿＿＿＿＿

https://github.com/QueenieCplusplus/PPP (點對點協定)

＿＿＿＿＿＿

https://github.com/QueenieCplusplus/Network_Infra (路由與交換機) 

https://github.com/QueenieCplusplus/Routing_Strategy (路由策略)

https://github.com/QueenieCplusplus/Subnet_mask (子網域遮罩技術及其運算原理)

https://github.com/QueenieCplusplus/RIF (Routing Table's Field)

* Private IP

   * Static IP, 靜態邏輯位置設定

     * https://github.com/QueenieCplusplus/Static_Routing (Static Routing)

     * https://github.com/QueenieCplusplus/RIP (Dynamic Routing, Distance-Vector 距離向量)
     
       https://github.com/QueenieCplusplus/CCNP_EIGRP
     
          * https://github.com/QueenieCplusplus/HSRP (HSRP)

     * https://github.com/QueenieCplusplus/OSPF (Dynamic Routing, LSA 鏈結狀態通告) 
     
       https://github.com/QueenieCplusplus/CCNP_OSPF

   * Dynamic IP, 動態邏輯位置分配

     * DHCP, 動態主機設定 (協定)
     
     ![dhcp server as end devices](https://scontent.ftpe8-4.fna.fbcdn.net/v/t1.0-9/95108454_4236178209729288_944513370529202176_o.jpg?_nc_cat=110&_nc_sid=2d5d41&_nc_ohc=svKyATzPYs4AX8iwhiV&_nc_ht=scontent.ftpe8-4.fna&oh=51b987b5fb2b5c80f455ba755d1647b1&oe=5ECD08F3)
   
* Public IP

   NAT, 網路位置轉換（演算法）
   
   https://github.com/QueenieCplusplus/NAT (NAT)
   
＿＿＿＿＿＿

Terminology:

https://github.com/QueenieCplusplus/Networking (網路觀測技術及網路應用層)

＿＿＿＿＿＿

Codebase: 

https://github.com/QueenieCplusplus/Band_Width (thruput in Bit & storage in Bytes, and display their conversion in code)

＿＿＿＿＿＿

Bridge: 

https://github.com/QueenieCplusplus/Source_Route_Bridging (Source_Route)

＿＿＿＿＿＿

(Routers Braodcast)

(Redistribution)

(Filter Routing Info)

(Difussing Update Algorithm)

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# CCDA (Cisco Certified Design Associate 網路架構師專業)

since 2020/4/02 - 4/04 & 4/09, 5/03

![architecture](https://scontent.ftpe8-4.fna.fbcdn.net/v/t1.0-9/90356838_4112599058753871_5151945715458506752_o.jpg?_nc_cat=102&_nc_sid=2d5d41&_nc_ohc=wzWx2Snse6kAX8BStzA&_nc_ht=scontent.ftpe8-4.fna&oh=c40a5ab47e5af6b14d6ffbf8ebc60579&oe=5EABDFC5)

Assessment https://github.com/QueenieCplusplus/Static_and_Dynamic (Routing Protocols)

Interior and Exterial (Private IP & Public IP) https://github.com/QueenieCplusplus/IGP_and_BGP

https://github.com/QueenieCplusplus/Interior_and_Exterior

＿＿＿＿＿＿

ISIS (relative to OSPF) https://github.com/QueenieCplusplus/IS_IS

BGP (on contrast to IGRP) https://github.com/QueenieCplusplus/BGP

＿＿＿＿＿＿

* Rotocols in Layer 2-3

  * ARP for IPv4 https://github.com/QueenieCplusplus/ARP
  
  * ND for IPv6 (Network Discover, Router Solicitation & Advertisement) https://github.com/QueenieCplusplus/ND

  * ICMP for IPv6 https://github.com/QueenieCplusplus/ICMP (ND, Neighbour Discovering)
  
  * IGMP for IPv6 (Multicast) https://github.com/QueenieCplusplus/MLD_and_MRD

＿＿＿＿＿＿

* LAN Terminology:
 
    * FDDI https://github.com/QueenieCplusplus/FDDI (Optical Fiber)

    * Wireless https://github.com/QueenieCplusplus/Wireless_LAN (AP)
 
    * Fast Ethernet

    * Token Ring (see IEEE 802.5)

＿＿＿＿＿＿

* WAN Technology:
 
    * DSL WAN https://github.com/QueenieCplusplus/DSL

    * ISDN (Tele Service)

    * dial up https://github.com/QueenieCplusplus/Dial_UP (PPP)

    * x.25 https://github.com/QueenieCplusplus/Xdot25

    * frame relay (Streamlined Version of X.25)

    * SMDS (for PDNs, Public Data Network, see IEEE 802.6)

    * ATM (Async Transfer Mode)

＿＿＿＿＿＿

* Network Mgmt Tool:

   * SNMP https://github.com/QueenieCplusplus/SNMP

＿＿＿＿＿＿

* WAN Performance Indicators:

- [X] Data Compression

- [X] Window Size

- [X] Queue

- [X] Shape

- [X] Policy

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# DBA 
since 2020/3/04 & 3/07

![odbc](https://scontent.ftpe8-4.fna.fbcdn.net/v/t1.0-9/46682128_2730379330309191_2557865780267974656_o.jpg?_nc_cat=104&_nc_sid=dd9801&_nc_ohc=69tWO55x8FoAX8j5GPs&_nc_ht=scontent.ftpe8-4.fna&oh=8da4bae87486f36d8e8165900338462a&oe=5EAE6BC9)

* MySQL
  
https://github.com/QueenieCplusplus/MySQL

* PostgreSQL

https://github.com/QueenieCplusplus/PostgreSQL

* Session

http://einverne.github.io/post/2017/05/sqlalchemy-session.html

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# MarkDown (md)
since 2020/3/03

> I need this to do UML, good tips hereby

http://amwiki.org/doc/?file=020-教程学习篇/005-学习markdown/70-Markdwon流程图 (flow chart)

> Foot Note

http://amwiki.org/doc/?file=020-教程学习篇/005-学习markdown/11-Markdwon脚注

# Security Checklist for SE
since 2019/12/20

https://github.com/QueenieCplusplus/DataStorage_Hadoop#安全檢查清單表

https://github.com/QueenieCplusplus/SSCP_Network/blob/master/README.md#phisical-layer

https://github.com/QueenieCplusplus/SSCP_System/blob/master/README.md#checklist-for-system

 Requirement        |   |
--------------------|---|
   admin setup      | √ |
firewall            | √ |
version of system   | √ |
   anti-virus       | √ |
  port disable      | √ |
 monitor & log      | √ |               

# Bot Being
![bot](https://upload.wikimedia.org/wikipedia/commons/c/c2/Gnome-stock_person_bot.svg)since 2020/1/02 新年紀念版

https://github.com/QueenieCplusplus/CrawlerByUsingPython


# 解析封包
since 2017/10/20 & update on 2020/02/27 

![Inetnet Packet](https://scontent.ftpe8-4.fna.fbcdn.net/v/t1.0-9/78979984_100131028143401_6743161275343175680_o.jpg?_nc_cat=102&_nc_sid=05277f&_nc_ohc=F4R51Dr1QYcAX_iTdOt&_nc_ht=scontent.ftpe8-4.fna&oh=adbad6ff5506a68416d0b2800d6a52b6&oe=5EAD3048)

https://github.com/QueenieCplusplus/Extension_IP_Header (Http Header)

https://github.com/QueenieCplusplus/Http_header (Http-Header-Fields & get API app)

https://github.com/QueenieCplusplus/Py_Parser (Http Req-Res Chain)

https://github.com/QueenieCplusplus/DataMining_Spark (Smarter Pandas)

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 網頁前端
since 2020/2/29 quickstart

![front end](https://scontent.ftpe8-2.fna.fbcdn.net/v/t1.0-9/49714036_338771176967961_5749859859470221312_o.jpg?_nc_cat=101&_nc_sid=8024bb&_nc_ohc=tBb_sHdb0sgAX9D3eZw&_nc_ht=scontent.ftpe8-2.fna&oh=675033235dd6794a4a60dced0811b4aa&oe=5EAC5B0C)

https://github.com/QueenieCplusplus/React (React)

https://github.com/QueenieCplusplus/H5 (HTML5)

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 容器管理工具和瀏覽器平台解讀執行中的程式碼
since 2020/1/04 quickstart

![container](https://scontent.ftpe8-3.fna.fbcdn.net/v/t1.0-9/44590289_295590661286013_2341529828051648512_o.jpg?_nc_cat=106&_nc_sid=110474&_nc_ohc=ILqNaY8wdMUAX8JKLJi&_nc_ht=scontent.ftpe8-3.fna&oh=0d66364482942caa0bad2a7dbb4c622a&oe=5EABE530)

https://github.com/QueenieCplusplus/Jupyter

https://github.com/QueenieCplusplus/Docker

# 倉儲託管工具
since 2018/7/23 

https://github.com/QueenieCplusplus/git_Q

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 應用編程介面
since 2020/1/02 新年紀念版

https://github.com/QueenieCplusplus/API

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# SAP
since 2019/12/29

https://github.com/QueenieCplusplus/Abaper

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 敘述統計
since 2015 & 2019/12/24

- [x] Sampling, 抽樣與次數分配

  https://github.com/QueenieCplusplus/Stats_Sampling

- [x] Average, 平均數 (包含加權、中位、調和)

- [ ] Var (diff) Coficeient, 係數變數（變異係數與標準差）

- [ ] Exponentiation, 指數函數

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 駭客技術 
since 2018/2 & 2019/12/22

![black hat](https://scontent.ftpe8-1.fna.fbcdn.net/v/t1.0-9/91406067_149826639840506_1249889269011447808_o.jpg?_nc_cat=105&_nc_sid=dd9801&_nc_ohc=ieFo74uET7UAX9v61kI&_nc_ht=scontent.ftpe8-1.fna&oh=ab939810b8f1c9781b392f278580d520&oe=5EAEBEA2)

一, 利用 CORs 旁繞 SOP 再行 XSS, 網路應用程式的跨域及跨站攻擊
 
   https://github.com/QueenieCplusplus/ITsec_BypassSOP/blob/master/README.md#ie-瀏覽器範例
  
* On Users Behalf, 最嚴重的攻擊->針對使用者未知情況下的攻擊

   https://github.com/QueenieCplusplus/ITsec_UsersBehalf (總覽)

 > (1)Cookies & Session ID, 會話識別符取得隱私的攻擊 
 
    https://github.com/QueenieCplusplus/ITsec_UsersBehalf/blob/master/getSessionOrCookie.js
 
  https://github.com/QueenieCplusplus/SSCP_Admin/blob/master/README.md#owasp-top-10-open-web-app-security-project
 
 > (2)Social Phishing, 社交攻擊（原理和輸入攻擊相似） 
 
   https://github.com/QueenieCplusplus/ITsec_UsersBehalf/blob/master/Phishing.js
 
   https://github.com/QueenieCplusplus/SSCP_Admin/blob/master/README.md#owasp-top-10-open-web-app-security-project
 
 > (3)Input Capture such as iFrame, 取得輸入的攻擊 
 
   https://github.com/QueenieCplusplus/H5/blob/master/Useful_H5_Syntax/iFrame.pdf
  
   https://github.com/QueenieCplusplus/SSCP_Admin/blob/master/README.md#owasp-top-10-open-web-app-security-project
 
 > (4)直接損毀內容的攻擊 (略)
 
 > (5)主動下載被狹持的軟體如影音解碼器(略)
 
 > (6) XSS, 跨境腳本輸入

＿＿＿＿＿＿＿＿＿＿＿＿＿

二, 擷取跨域資源後，針對應用程式的攻擊

* Web App Flaw, 針對軟體的攻擊

> (1)SQL Injection, 資料庫注入惡意代碼
  
   https://github.com/QueenieCplusplus/ITsec_SQLinjection
  
   https://github.com/QueenieCplusplus/SSCP_Admin/blob/master/README.md#owasp-top-10-open-web-app-security-project
     
     solution => PreparedStatement, or SQL query with default Type Param.
  
> (2)CSRF 或稱 XSRF (再行密碼重置)
  
   https://owasp.org/www-community/attacks/csrf
  
   https://github.com/QueenieCplusplus/SSCP_Admin/blob/master/README.md#owasp-top-10-open-web-app-security-project
  
> (3)DOS, 癱瘓伺服器
  
> (4)RCE, 遠端命令執行 

   https://github.com/QueenieCplusplus/SSCP_Network#layer-6-presentation-layer-表現層
 
＿＿＿＿＿＿＿＿＿＿＿＿＿

三, 底層的攻擊

* Pinning, 網路攻擊

  https://github.com/QueenieCplusplus/ITsec_PinningScanner

* Port Scanner, 通訊埠掃描攻擊

  https://github.com/QueenieCplusplus/ITsec_PortScanner
  
* Link-state (Data-Link) Level Attack, 鏈結層的攻擊 (Block or Fame)

  https://github.com/QueenieCplusplus/SSCP_Network/blob/master/README.md#attack-in-network
  
* Packets Attacks, 偽封包的攻擊（Layer3, 4）
  
  https://github.com/QueenieCplusplus/Network_Attacks
  
＿＿＿＿＿＿＿＿＿＿＿＿＿

四, 瀏覽器攻擊

* Browser, 針對瀏覽器的攻擊

> (1)Finger Printing (http header, DOM), 指紋取樣
      
  其實技術術語中的指紋取樣的意思是取得平台版本。
  
   https://github.com/QueenieCplusplus/SSCP_System/blob/master/README.md#attack-in-sys-level
 
> (2)bypass SOP using CORs (cookies, http header, path traversal), 繞過同源限制

   https://github.com/QueenieCplusplus/ITsec_BypassSOP

 
> (3)attack SSL, 利用安全通訊協定的弱點加以攻擊之

   https://github.com/QueenieCplusplus/ITsec_BeastCrime

   https://github.com/QueenieCplusplus/SSCP_Admin/blob/master/README.md#owasp-top-10-open-web-app-security-project

 
> (4)JS & heap, 堆積洞孔導致記憶體外洩

   https://github.com/QueenieCplusplus/ITsec_JSheap

   https://github.com/QueenieCplusplus/SSCP_System/blob/master/README.md#attack-in-sys-level


> (5)Metasploit & shell

   https://github.com/QueenieCplusplus/SSCP_Network#layer-6-presentation-layer-表現層

> (6)Plugin Flaw, 能在瀏覽器外部獨立運作的插件有漏洞時的攻擊


> (7)Browsers Extensions Flaw, 瀏覽器衍生套件有漏洞時的攻擊

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 資安研究
since 2019/, rollback on 2019/12/20

![rsa](https://d1dwq032kyr03c.cloudfront.net/upload/images/20170111/201034346zInPKC8sK.png)

* Authorization & Authentication, 授權與驗證 

    - [x] Admin, https://github.com/QueenieCplusplus/DataStorage_Hadoop#4a-角色許可權管理

    - [x] Auth, https://github.com/QueenieCplusplus/ITsec_Oauth
    
    - [x] Digital Certificate & Digital Signature, 電子憑證(票據)與電子簽章
          https://github.com/QueenieCplusplus/SSCP_System/blob/master/README.md#digital-signature-aka-code-sign
    
    - [ ] X.509, 電子憑證的格式
    
      TODO

* Cipher & Crypto, 加密

    - [x] RSA & SHA, 常見的加密演算法
    https://github.com/QueenieCplusplus/Cipher_Crypto
    
    - [x] Symmetric & Asymmetric, 對稱與非對稱的加密技術
    https://github.com/QueenieCplusplus/Cipher_Crypto

    - [x] Session, https://github.com/QueenieCplusplus/DataStorage_Hadoop#key-in-session-加密的安全通訊技術

    - [x] Cipher, https://github.com/QueenieCplusplus/ITsec_Cipher
    
* TLS, 傳輸層安全協定

    - [x] SSL, https://github.com/QueenieCplusplus/ITsec_TLS
    
＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿
    
# 大數據
since 12/18, 2019

![hadoop](https://d1.awsstatic.com/Projects/Analyze%20Big%20Data/aws-project_analyze-big-data_diagram.a6eac723a050d5841a9656225b73ecdad2da18d8.png)

基礎觀念：

* CAP
* ACID

涉及資料探勘與資料採擷，攸關基礎設施如存儲系統和程式設計與運算資源調度的彈性機制。

https://github.com/QueenieCplusplus/DataMining_Spark (Spark Tool) 

https://github.com/QueenieCplusplus/DataMining_Cassandra (C＊ DB Engine)

https://github.com/QueenieCplusplus/DataMining_DataScientist (Data Mine)

https://github.com/QueenieCplusplus/DataStorage_Hadoop (Hadoop Storage) 

https://github.com/QueenieCplusplus/DataBase_PostgreSQL (PostgrSQL)

Spark & Hadoop :

* 分散式運算引擎
* 企業資料匯流排
* 資料整合與資料流分析
* 互動式統計分析與即時計算
* 事件處理與增加 SAS

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 人工智慧
since 2018/11 & 2019/10/14-11/11

|    AI Tool   |  Engine  |  Year |
|--------------|:--------:|------:|
|  TensorFlow  |  Google  | 2018  |
|    PyTorch   |  Python  | 2018  |
|    Matlab    |          | 2019  |
|     Keras    |  Python  | 2020  |

＿＿＿＿＿＿＿＿＿＿＿＿＿

- [x] Webhook, 呼叫自定義函數後回呼返回另一網站的掛鉤

  https://github.com/QueenieCplusplus/AI_Webhook

- [x] chatBot, 聊天機器人

  ![AI](https://external.ftpe8-2.fna.fbcdn.net/safe_image.php?d=AQAbvPZSvdwJWFM8&w=540&h=282&url=https%3A%2F%2Fi.ytimg.com%2Fvi%2Fh0WPJqd78Qg%2Fhqdefault.jpg&cfs=1&upscale=1&fallback=news_d_placeholder_publisher&_nc_hash=AQDA1N5O8yMqy1He)
  
  plz click on this url: https://www.youtube.com/watch?v=h0WPJqd78Qg&feature=youtu.be&fbclid=IwAR3vyXC6PN0tDHxNB-2T7Tu6IS6Xs_aDFkqQviJjY4F0d4L7geMGykGe2gY

  https://github.com/QueenieCplusplus/AI_LineChatBot

- [x] Watson, 華生

  https://github.com/QueenieCplusplus/AI_Watson

- [x] Heroku, 發布平台

  https://github.com/QueenieCplusplus/AI_Heroku/blob/master/README.md
  
＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 搜索引擎
since 2019/7 & 2019/12/21

* GraphQL 

  https://github.com/QueenieCplusplus/GraphQL/blob/master/README.md

* U.C. Berkerly PostgreSQL (TBD)

  * 大部

  https://github.com/QueenieCplusplus/DBA_SearchEngine （搜索引擎架構）
  
  https://github.com/QueenieCplusplus/DBA_QueryOptimization （查詢最佳化)
  
  https://github.com/QueenieCplusplus/DBA_QueryPlan （查詢計畫）
  
  * 細部
  
  https://github.com/QueenieCplusplus/DBA_Entity (查詢實體)
  
  https://github.com/QueenieCplusplus/DBA_Logics (查詢邏輯)
  
  查詢詞語 (略)
  
* Oracle MySQL (Done)

* Redis DB

  https://redisbook.readthedocs.io/en/latest/internal/rdb.html
    
＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 資料結構 
since 12/20, 2019

* Search, 搜索

* Sort, 排序

  sort https://github.com/QueenieCplusplus/Sort_sort
  
   ＊) insertion sort & quick sort TBD
   
     ) merge sort (interator, recursive)
     
     ) heap & key
     
     ) list & table


* Binary Tree, 二元樹

  binary tree https://github.com/QueenieCplusplus/BinaryTree_binaryTree

    ＊) traversal & iterators TBD
    
    ＊) binary search tree (delete, join) TBD
    
    ＊) set (union, find) TBD

 ＿＿＿＿＿＿＿＿＿＿＿＿＿
 
 應用於資料庫管理應用程式和網路的路由表

* Hash Table (static, dynamic), 雜湊映射表或稱字典 

    https://github.com/QueenieCplusplus/DataStructure_HashTable
    
 ＿＿＿＿＿＿＿＿＿＿＿＿＿
  
  串流和輸出入序列的應用

* Queue, 佇列 (與堆疊相似)

    https://github.com/QueenieCplusplus/DataStructure_Queue
    
 ＿＿＿＿＿＿＿＿＿＿＿＿＿
  
  方程式的暫存存儲資料結構

* Heap, 堆積（串列的一種）

    https://github.com/QueenieCplusplus/DataStructure_Heap
    
* Heap v.s Stack 堆積與堆疊

    https://github.com/QueenieCplusplus/ITsec_JSheap#heap--stack
    
 ＿＿＿＿＿＿＿＿＿＿＿＿＿
  
  基礎概念

* Stack 堆疊

* Linked List, 鏈結串列

* Array, 陣列 (one dimension, two dimentions)

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 程式語言
since 11/16 & 11/22 & 12/25, 2019

![C++](https://scontent.ftpe8-4.fna.fbcdn.net/v/t1.0-9/76194400_1161384307585687_7259639227355234304_o.jpg?_nc_cat=102&_nc_sid=2d5d41&_nc_ohc=A7XJCvyj97EAX-LTQdO&_nc_ht=scontent.ftpe8-4.fna&oh=b1b4c93808a384805470a959ba3055a8&oe=5EAC935E)

https://github.com/QueenieCplusplus/1122Try (C in 2019)

https://github.com/QueenieCplusplus/Qs_C (C in 2020)

https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#c-again (C for System Program)

https://github.com/QueenieCplusplus/Cplusplus (C++)
    
https://github.com/QueenieCplusplus/Golang (Golang 還原)

https://github.com/QueenieCplusplus/ObjC (Object-C)

https://developer.apple.com/swift/ Swift4官方網站 since 2018/3

https://kotlinlang.org Kotlin官方網站 since 2018/10 & 2019/5

Java (since 2018/5 & 2019/8)

https://gist.github.com/PattyAppier?fbclid=IwAR1DdgxMcrm2HJJBTpjEQkti94GkYRK1i039JQy8rX89iNoeYlxid0ORRlI (Android)
   
＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 腳本語言
since 2019/8, rollback on 2019/12/20

![hackathon](https://scontent.ftpe8-4.fna.fbcdn.net/v/t1.0-9/70703759_487561688755575_4016249688293376_o.jpg?_nc_cat=110&_nc_sid=8024bb&_nc_ohc=X_X9uQCoTooAX86FrHg&_nc_ht=scontent.ftpe8-4.fna&oh=3287770d7e85d474f62c55c2f7b9c220&oe=5EAD38A9)

https://github.com/QueenieCplusplus/Backend_Script 登入驗證功能（Nodejs: Express 專案未還原）

https://github.com/QueenieCplusplus/Backend_Script2 建立會議對話識別符 (php: CI & Laravel 專案未還原)
   
https://github.com/QueenieCplusplus/Backend_Script3 運算與圖像工具 (python: Django 還原)

https://github.com/QueenieCplusplus/Ruby_Cart 電商常用購物車 (ruby: Rail & Rack)

https://github.com/QueenieCplusplus/Perl (perl)

https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#perl-again (perl again)

![php](https://scontent.ftpe8-2.fna.fbcdn.net/v/t1.0-9/53419721_371771003667978_5518997636369088512_n.jpg?_nc_cat=103&_nc_sid=110474&_nc_ohc=oZH25eTIOPcAX9S1gRN&_nc_ht=scontent.ftpe8-2.fna&oh=c06fc88120602233b5614c64b24e64cd&oe=5EADB8E8)

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 電腦科學
since 11/28 & 1216, 2019

* 網路：https://github.com/QueenieCplusplus/Networking (全還原)

* 資料：https://github.com/QueenieCplusplus/1216Data_Structure (搜索引擎原理)

* 效能：https://github.com/QueenieCplusplus/Optimization (全還原)   

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 手機前端 

since 2018/3, all repos will be hidden from public

2018 Memoir
https://www.facebook.com/pattyluvapp/videos/627286591019953/?redirect=false

Sandbox https://github.com/QueenieCplusplus/SSCP_System/blob/master/README.md#sandbox-沙盒

VM https://github.com/QueenieCplusplus/SSCP_System/blob/master/README.md#vm-虛擬機

VM https://github.com/QueenieCplusplus/VM/blob/master/README.md#vm

codebase(2018) https://gist.github.com/PattyAppier?fbclid=IwAR1DdgxMcrm2HJJBTpjEQkti94GkYRK1i039JQy8rX89iNoeYlxid0ORRlI

Lifecycle of app https://github.com/QueenieCplusplus/SSCP_Admin/blob/master/README.md#system-software-security

![C](https://scontent.ftpe8-3.fna.fbcdn.net/v/t1.0-9/46499002_277135316275746_6852937246404771840_o.png?_nc_cat=111&_nc_sid=dd9801&_nc_ohc=EIHTNLFf74sAX9v9m-K&_nc_ht=scontent.ftpe8-3.fna&oh=65c1987f940a95125fab594403a71f48&oe=5EACFB23)

![mylucky7app](https://scontent.ftpe8-4.fna.fbcdn.net/v/t1.0-9/32853922_165886317589782_5830205589338193920_o.jpg?_nc_cat=110&_nc_sid=daf655&_nc_ohc=O49aJEhX50wAX_YTNFm&_nc_ht=scontent.ftpe8-4.fna&oh=696479d634e2bd39d0f4cedf9de69270&oe=5EACB694)

![myios](https://scontent.ftpe8-3.fna.fbcdn.net/v/t1.0-9/91160543_556288008360474_5139629866672455680_n.jpg?_nc_cat=111&_nc_sid=110474&_nc_ohc=-bZKzU09FrcAX9yqu-P&_nc_ht=scontent.ftpe8-3.fna&oh=69484c6da9289a1da94d287d6fca70fd&oe=5EAE7E5D)

![react_native](https://akkar.media/wp-content/uploads/2018/12/khoa-hoc-lap-trinh-com-phong-van-vi-tri-react-native-6-thang-kinh-nghiem-can-nhung-gi-87676.png)

* UML & Spec

     https://github.com/QueenieCplusplus/UML_Spec

* iOS 11 : pattyappier & pattyluvapp

     https://developer.apple.com/ (Apple 開發者官網)
     
     ![ios](https://scontent.ftpe8-4.fna.fbcdn.net/v/t31.0-8/30167559_148789092632838_6815308864428869549_o.jpg?_nc_cat=104&_nc_sid=daf655&_nc_ohc=t96yDdGFCbIAX86krOJ&_nc_ht=scontent.ftpe8-4.fna&oh=ca4095aca3df89857b4d20e412daf2ed&oe=5EE09A13)
     
     ![ios2](https://scontent.ftpe8-3.fna.fbcdn.net/v/t31.0-8/30846638_148789082632839_5464428596532847837_o.jpg?_nc_cat=111&_nc_sid=daf655&_nc_ohc=RpHcsDlBMnIAX_E4gB8&_nc_ht=scontent.ftpe8-3.fna&oh=6b6bf6c709df082b1dd96016aa0e6ab9&oe=5EE13E70)

* Android 3: katesandroidapp & katesapp2019

     https://developer.android.com/about/versions/10 （Android 開發者官網）
     
     ![pokemon](https://scontent.ftpe8-2.fna.fbcdn.net/v/t1.0-9/33141809_168523297326084_8569444557161234432_o.jpg?_nc_cat=100&_nc_sid=daf655&_nc_ohc=qZndPQuVmXUAX8pPJc2&_nc_ht=scontent.ftpe8-2.fna&oh=7d7fe38bf25d12d2dbfd590a5d85bf81&oe=5EAE5831)
     
     ![myandroid](https://scontent.ftpe8-2.fna.fbcdn.net/v/t1.0-9/91398353_556287971693811_2258677452190515200_n.jpg?_nc_cat=100&_nc_sid=110474&_nc_ohc=GSlq76-Y-xwAX8tzwkk&_nc_ht=scontent.ftpe8-2.fna&oh=d9b968960ee96a4086fe6106c7e418b2&oe=5EAE88E6)

* React Native : redpint819

    https://github.com/QueenieCplusplus/Qs_ReactNative (跨平台 jsx from FB)

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 雲端後端

since 2018/6, all repos will be hidden from public

![GCP](https://scontent.ftpe8-1.fna.fbcdn.net/v/t1.0-9/48389805_900814930309294_4733238699620302848_n.png?_nc_cat=105&_nc_sid=8024bb&_nc_ohc=tV5F4PeHOMUAX-X6gw8&_nc_ht=scontent.ftpe8-1.fna&oh=5cbc5dbc9c43e1a92a3d0d138bd0f8fd&oe=5EAED3DB)

* BaaS : quinoaPy

  https://github.com/QueenieCplusplus/BaaS （唯一還原的資源）
  
 https://github.com/QueenieCplusplus/SSCP_CloudSecurity/blob/master/README.md#clouds-platform-雲端服務平台 (PaaS)

* iCloud : pattyluvapp

https://gist.github.com/PattyAppier?fbclid=IwAR1DdgxMcrm2HJJBTpjEQkti94GkYRK1i039JQy8rX89iNoeYlxid0ORRlI

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# Content Delivery Network (Storage System)

since 2017/11

Content is stored in Objective Sotage, which is distributed to Distributed Nodes (Mirror) to improve Internet Consumption Speed.

![akamai](https://scontent.ftpe8-3.fna.fbcdn.net/v/t1.0-9/50103917_341680980010314_5406345544752693248_o.jpg?_nc_cat=111&_nc_sid=110474&_nc_ohc=o5yfDcT8a0AAX90Z6je&_nc_ht=scontent.ftpe8-3.fna&oh=544a896052994748b766dd289de73478&oe=5EAD014C)


