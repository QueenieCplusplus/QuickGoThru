# QueenieCplusplus/QuickGoThru

今天是帳號復原的一天，經過與 Github 團隊多次書信往來協商後，雖然我其餘 16 個帳號得以用隱藏方式保留，但我仔細想想自己技術能量已經不同於往，所有 repo 我將不打算遷移至此，因為會讓這庫變得複雜，所以那些 C# 、 iOS(swift) 、 Android(kotlin)，我不打算將過去歷史痕跡放在現在與未來，因為他們都是使得我現在如此茁壯來面對未來的技術，他們是促使進步的媒介，但不是我應該守護的東西。

本儲存庫將繼續保留 C++ 原始的研究，並且現在會以 Data Structuture 的研究 ，以及搜索引擎的應用為主，未來則將專注資料分析處理 Data Analysis 包含擷取與探勘 Data Mining 和資訊安全與駭客技術 Hack on Browser 為主要研究議題。

既然我已經不是過去的我，那傻妞 Patty & 歷經滄桑的 Kate，我是有能力駕馭難度更高技術的 Queenie，要感謝過去的努力的自己造就現在面對一切更為輕鬆的我，放眼未來的技術才是，所以那些無奈被迫隱藏的智財庫，就當消失唄！

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 資安研究 
since 2018/2 & 2019/12/22

一, XSS 或利用 CORs 旁繞 SOP, 網路應用程式的跨域及跨站攻擊
 
   https://github.com/QueenieCplusplus/ITsec_BypassSOP/blob/master/README.md#ie-瀏覽器範例
  
* On Users Behalf, 最嚴重的攻擊->針對使用者未知情況下的攻擊

  https://github.com/QueenieCplusplus/ITsec_UsersBehalf

      (1)會話識別符取得隱私的攻擊  
      (2)社交攻擊（原理和輸入攻擊相似）  
      (3)取得輸入的攻擊  
      (4)直接損毀內容的攻擊 (略)

＿＿＿＿＿＿＿＿＿＿＿＿＿

二, 擷取跨域資源後，針對應用程式的攻擊

* Web App Flaw, 針對軟體的攻擊

  (1)SQL Injection, 資料庫注入惡意代碼
  
     https://github.com/QueenieCplusplus/ITsec_SQLinjection
  
  (2)CSRF 或稱 XSRF (再行密碼重置)
  
  (3)DOS, 癱瘓伺服器
  
  (4)RCE, 遠端命令執行
 
＿＿＿＿＿＿＿＿＿＿＿＿＿

三, 底層的攻擊

* Pinning, 網路攻擊

  https://github.com/QueenieCplusplus/ITsec_PinningScanner

* Port Scanner, 通訊埠掃描攻擊

  https://github.com/QueenieCplusplus/ITsec_PortScanner
  
＿＿＿＿＿＿＿＿＿＿＿＿＿

四, 瀏覽器攻擊

* Browser, 針對瀏覽器的攻擊

      (1)Finger Printing (http header, DOM), 指紋取樣
         //其實技術術語中的指紋取樣的意思是取得平台版本。
 >>>  
 TBD...
 >>>
 
       (2)bypass (cookies, https, path), 繞過同源限制
 >>>
https://github.com/QueenieCplusplus/ITsec_BypassSOP
 >>>
 
       (3)attack SSL, 利用安全通訊協定的弱點加以攻擊之
>>>  
https://github.com/QueenieCplusplus/ITsec_BeastCrime
>>>
 
       (4)JS & heap, 堆積洞孔導致記憶體外洩
>>>   
https://github.com/QueenieCplusplus/ITsec_JSheap
>>>

       (5)Metasploit & shell
>>>
TBD...
>>>
 * Plugin Flaw, 能在瀏覽器外部獨立運作的插件有漏洞時的攻擊

 * Browsers Extensions Flaw, 瀏覽器衍生套件有漏洞時的攻擊

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 搜索引擎
since 2019/7 & 2019/12/21

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

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 安全加密和驗證授權技術
since 2019/, rollback on 2019/12/20

* Authorization & Authentication, 授權與驗證 

    https://github.com/QueenieCplusplus/DataStorage_Hadoop#4a-角色許可權管理

    https://github.com/QueenieCplusplus/ITsec_Oauth
    
    Certificate, 電子憑證(票據)與電子簽章

* Cipher & Crypto, 加密

    RSA & SHA, 常見的加密演算法
    
    Symetric & Asymetric, 對稱與非對稱的加密技術

    https://github.com/QueenieCplusplus/DataStorage_Hadoop#key-in-session-加密的安全通訊技術

    https://github.com/QueenieCplusplus/ITsec_Cipher
    
＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 資料結構  (TBD)
since 12/20, 2019

* Search, 搜索

* Sort, 排序

  sort https://github.com/QueenieCplusplus/Sort_sort

      ＊) insertion sort

      ＊) quick sort

      ) merge sort (interator, recursive)

      ) heap sort

      ) sort on keys

      ) list sort

      ) table sort

      ) internal sort

      ) external sort

* Binary Tree, 二元樹

  binary tree https://github.com/QueenieCplusplus/BinaryTree_binaryTree

      ) array

      ) linked list

      ＊) traversal

      ＊) iterators

      ) threaded trees

      ) heaps

      ＊) binary search tree (delete, join)

      ) selection tree (winner, loser)

      ) forest

      ＊) set (union, find)

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

# 大數據
since 12/18, 2019

基礎觀念：

* CAP
* ACID

涉及資料探勘與資料採擷，攸關基礎設施如存儲系統和程式設計與運算資源調度的彈性機制。

https://github.com/QueenieCplusplus/DataMining_Spark (Spark) 

https://github.com/QueenieCplusplus/DataMining_Cassandra (C＊)

https://github.com/QueenieCplusplus/DataMining_DataScientist (Data Mine)

https://github.com/QueenieCplusplus/DataStorage_Hadoop (Hadoop) 

https://github.com/QueenieCplusplus/DataBase_PostgreSQL (PostgrSQL)

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 程式語言
since 11/16 & 11/22, 2019

https://github.com/QueenieCplusplus/1122Try (C)

https://github.com/QueenieCplusplus/Cplusplus (C++)
    
https://github.com/QueenieCplusplus/Golang (Golang 還原)

Java & Kotlin (略)
   
＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 腳本語言
since 2019/8, rollback on 2019/12/20

https://github.com/QueenieCplusplus/Backend_Script （Nodejs: Express 專案未還原）

https://github.com/QueenieCplusplus/Backend_Script2 (php: CI & Laravel 專案未還原)
   
https://github.com/QueenieCplusplus/Backend_Script3 (python: Django 還原)

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 電腦科學
since 11/28 & 1216, 2019

* 網路：https://github.com/QueenieCplusplus/Networking (全還原)

* 資料：https://github.com/QueenieCplusplus/1216Data_Structure (搜索引擎原理)

* 效能：https://github.com/QueenieCplusplus/Optimization (全還原)   

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 手機前端 

since 2018/3, all repos will be hidden from public

* iOS : pattyappier & pattyluvapp

* Android : katesandroidapp & katesapp2019

* React : redpint819

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 雲端後端

since 2018/6, all repos will be hidden from public

* BaaS : quinoaPy

  https://github.com/QueenieCplusplus/BaaS （唯一還原的資源）

* iCloud : pattyluvapp

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# Content Delivery Network

since 2017/11

