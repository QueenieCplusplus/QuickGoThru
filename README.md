
雖然目前是行動裝置時代，然而行動裝置僅能做客戶端設備顯示使用，運算能力集中在雲端上，透過網路互相連接，故科技時代的 2016 年之後，尤其 2018 年到今年和未來，科技業展開新革命：手機應用程式（行動支付）、雲端運算(PaaS)、虛擬化後端。

但其實雲端基礎上，仍然是硬體伺服器與網路設備，所以網頁伺服器、資料庫伺服器、檔案伺服器、郵件伺服器、訊息交換伺服器並無消失，反而需求量更大，隨著虛擬機的流行，一台硬體設備安裝百千個伺服器（虛擬化叢集）已經是正常現狀，傳統的伺服器將消逝。

本儲存庫保留以往 C++ 高階程式語言、Python 腳本特色、資料擷取（和嗅探） Data Mining & Web Crawler，亦包含 Data Structure、DBA (Search Engine) 的研究著作，尚包羅資安議題 IT Security & Hack on Browser，未來將主攻『 雲端技術 Cloud Service https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#cloud-service-vm 與程式化網路技術 SDN 』，敬請拭目以待。 ：）



# Cloud Tech in 2020

since 2020. 11/11 to Future ~

基礎網管將遭淘汰，所以我將專注在雲端技術上。

https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#cloud-service-vm

# VMware 虛擬化技術 in 2018

since 2020.4/23 閱讀前導：

https://github.com/QueenieCplusplus/VM (HyperV 範例)

since 2020.4/30 閱讀前導：

https://github.com/QueenieCplusplus/QuickGoThru#kernel-hackers (核心系統)

since 2020. 10/20 - 11/10 

* 實現 FT 應用的叢集、主機、虛擬機

* 運用 vSphere 軟體建立叢集，管理主機資源，並且建立虛擬機

* 管理 vSphere 網路
 
  * 單一實體機的實體網路卡
  
  * 虛擬機的虛擬網路卡

  * vSphere 標準交換機
  
  * 標準交換機與虛擬主機通訊阜
  
* 流量控制

  * 網路資源池
  
  * 頻寬分配予虛擬機
  
* 移轉

  * 熱移轉虛擬機

* vSAN、SAN 由虛擬交換機發展為存儲區域網路

# CDN in 2020

since 2017.11/15 & since 2020.9/30-10/02

* 對 CDN 的需求

  https://github.com/QueenieCplusplus/CDN

* ALTO 應用層流量最佳化

* CDN 架構圖

  https://github.com/QueenieCplusplus/CDN_Architecture

* Peer 2 Peer

  https://github.com/QueenieCplusplus/CCNA2020_VPN#p2p-peer-to-peer-bt-bit-torrent

* CDN 與雲端

  https://github.com/QueenieCplusplus/CDN_and_Cloud

* CDN 與 Cloud 的架構圖

* CDN 與網路部署（Ping、Traceroute、SNMP）

  https://github.com/QueenieCplusplus/CDN_and_Network

* Realtime Streaming Protocol, RTSP 即時串流傳輸協議 (有狀態協定、兩端對稱的協定) 

  https://github.com/QueenieCplusplus/CDN_RTSP

* CDN 服務指標 : 命中率、傳輸量、平行處理值、回應時間、媒體傳輸品質指標（延遲、封包遺失）、 平均意見指標

  https://github.com/QueenieCplusplus/QoS_and_QoE
  
* Request Routing System, RRS 內容服務的請求路由機制 (DNS 重新導向、IP 重新導向)

* HTTP req/res 涉及的所有角色

* HTTP 實現 CDN 快取

# Nginx & K8s in 2020

since 2020. 9/20 - 10/08

* Nginx

   * ＊＊＊ Web Server 網頁服務 (IPC, IO)＊＊＊
   
     https://github.com/QueenieCplusplus/Nginx_WWW
   
   * 伺服器的設定 
   
     https://github.com/QueenieCplusplus/Nginx_Server
     
   * 後端伺服器的設定 
   
     https://github.com/QueenieCplusplus/Nginx_Backend
   
   * Mail Server 郵件服務 
   
     https://github.com/QueenieCplusplus/Nginx_Mail

   * Proxy Server 反向代理與正向代理及其 Load Balance 功能 
   
     https://github.com/QueenieCplusplus/Nginx_Proxy

   * IPC amongs Nginx Servers 代理伺服器內的通訊方式 
   
     前導(1)：https://github.com/QueenieCplusplus/CCNA2020_IPC/blob/master/README.md#ccna2020_ipc
     
     前導(2)：https://github.com/QueenieCplusplus/Nginx_WWW#處理程序
     
     前導(3)：https://github.com/QueenieCplusplus/Nginx_WWW#請求處理
   
     https://github.com/QueenieCplusplus/Nginx_IPC
     
   * VM 虛擬主機設定

   * ＊＊＊ Nginx 初始化與啟動 ＊＊＊
   
   * Serialize 網路連接序列化、Event 事件驅動（事件處理機制）
   
 * K8s
 
   * Pod 豌豆莢 (master、slave、frontend)
   
     https://github.com/QueenieCplusplus/K8s_Pod
     
   * K8s DNS 
   
     https://github.com/QueenieCplusplus/K8s_DNS
     
   * ＊＊＊ K8s Architecture ＊＊＊ 
   
     https://github.com/QueenieCplusplus/K8s_Architecture
   
   * RC 豌豆莢抄本數量管理者 
   
     https://github.com/QueenieCplusplus/K8s_RC
     
   * ＊＊＊ Service thru Pods IP 透過豌豆莢的虛擬網路位址實現不中斷服務＊＊＊ 
   
     https://github.com/QueenieCplusplus/K8s_PodsIP
   
   * Namespace 命名空間為k8s物件的群組名稱
   
     https://github.com/QueenieCplusplus/K8s_Namespace
   
   * Network
   
     https://github.com/QueenieCplusplus/K8s_Networking
   
   * Kubelet, Node 的管理軟體 
   
     https://github.com/QueenieCplusplus/K8s_Kubelet
     
   * Kubeproxy 含有 k8s 代理伺服器的調節 
   
     https://github.com/QueenieCplusplus/K8s_Kubeproxy
   
   * Kubectl, 管控叢集中的 Master Node 
   
   * Auth (AC、Secret)

# CCNA Revsersion in 2020

since 2020. 9/09 - 9/19 

繼以往閱讀的 CCNA， 20 年來都是一樣的概念，然而今年 3 月開始確認重新改版內容，故技術迷們可能要重新閱讀這些大綱細節，除了融合 ICND (設備操作方式)，最特別的是加入了『 可程式化與自動化測試、虛擬化 』新內容，提醒網路領域的工程師們要注意這方面的趨勢發展囉！當然對已經會寫程式的我是沒問題的。

不過還是希望能夠再次利用三個月休息時間好好的重新檢視閱讀與探究新版的 CCNA 2020 唄～

2019 閱讀前導：

https://github.com/QueenieCplusplus/Networking (技術詞彙)

https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#解析封包 (封包解析)

https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#icnd-ccna (ICND)

https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#ccnp (CCNP)

https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#ccnp-osi-layer-2-3 (CCNP)

https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#cisco-router (Cisco Router)

https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#ccda-cisco-certified-design-associate-網路架構師專業 (CCDA)

2020 改版大綱：

前 四 章主要是以往 ICND 的內容，即『網路設備元件』的說明。 

1. 網路元件

   https://github.com/QueenieCplusplus/ICND_Connection (Before 2020)

   https://github.com/QueenieCplusplus/CCNA2020_NetworkComponent (2020)

2. 主機與主機之間的通信模型 

   https://github.com/QueenieCplusplus/Golang (Before 2020)

   ＊＊＊ 同一部主機的 IPC 進程通信方式 ＊＊＊：https://github.com/QueenieCplusplus/CCNA2020_IPC 

   不同部主機在同一網段中的通信方式：https://github.com/QueenieCplusplus/CCNA2020_Socket1

   不同主機在不同網段下的通信方式： 詳見標題 『TCP/IP 網際網路層 - IP 與 Subnet』

3. 操作系統的軟體及功能

   ...略...

4. LAN 與 SW （RIP is widely used in LAN）

   https://github.com/QueenieCplusplus/CCNA2020_SW
   
   建議搭配閱讀：詳見標題 『STP, Spanning Tree Protocol 與 RSTP 』、『Port Trunking | Link Aggregation』

-------------------

此 六 章是網路最基本的知識包含 OSI 七層觀念。

5. TCP/IP 網路存取層 - Ethernet

   https://github.com/QueenieCplusplus/CCNA2020_Ethernet
   
   相對於 25 項次的 WLAN 而言，LAN 屬於乙太網（有線的區域網路）

6. ＊＊＊TCP/IP 網際網路層 - IP 與 Subnet ＊＊＊

   https://github.com/QueenieCplusplus/CCNA2020_IP_and_Subnet

7. 『 TCP/IP 傳輸層與應用層 』 - 雲端發展後，使用者端與客戶端可以專注在 L4 ~ L7 

    L4, TCP 略
    
    L5 ~ L6
    
    https://github.com/QueenieCplusplus/CCNA2020_L5_and_L6 (會議層與表現層)  
    
    
    L7, APP 略

8. 路由器基本配置

   ...略...

9. 跨越交換器和路由器之間的主機對主機通信

   建議搭配閱讀：詳見標題 『 TCP/IP 網際網路層 - IP 與 Subnet 』

10. 解決交換網路與 IP 地址

    建議搭配閱讀：詳見標題 『 TCP/IP 網際網路層 - IP 與 Subnet 』

-------------------

此 九 章主軸焦點為網管對於虛擬區域網路的流量設定。

11. ＊＊＊靜態路由＊＊＊

    https://github.com/QueenieCplusplus/CCNA2020_StaticRouting 

12. ＊＊＊VLAN 與 Trunk＊＊＊ 

    https://github.com/QueenieCplusplus/CCNA2020_dot1q
    
    建議搭配閱讀：詳見標題 『LAN 與 SW』、『STP, Spanning Tree Protocol 與 RSTP』、『Port Trunking | Link Aggregation』

13. 跨越 VLAN 的路由配置 

    https://github.com/QueenieCplusplus/CCNA2020_interVlans_thruRouter

14. 動態路由中的 RIP (屬於 Distance-Vector Routing Protocol)

    https://github.com/QueenieCplusplus/CCNA2020_DynamicRouting

15. 動態路由中的 OSPF (屬於 Link-State Routing Protocol)

    https://github.com/QueenieCplusplus/CCNA2020_OSPF

    建議搭配閱讀：詳見標題 『動態路由』、『LAN 與 SW』

16. STP, Spanning Tree Protocol 與 RSTP （生成樹協定能協調多個交換器的工作）

    建議搭配閱讀：詳見標題 『VLAN 與 Trunk』、『Port Trunking | Link Aggregation』

17. Port Trunking | Link Aggregation (鏈路聚合配置)

    建議搭配閱讀：詳見標題 『VLAN 與 Trunk』、『STP, Spanning Tree Protocol 與 RSTP 』

18. Redundancy, 第三層冗余協定

-------------------

最後 八 章尤為重要，呼應了 Cisco 要發展的 DevNet 與 Google 的 SRE。

19. 『 WAN 和 VPN 』(廣域網路中的虛擬私人網路)

     https://github.com/QueenieCplusplus/CCNA2020_VPN

20. 『 ACL 』（存取控制）

21. 『 DHCP 與 DNS 』(9/14)

     https://github.com/QueenieCplusplus/CCNA2020_DHCP
     
     https://github.com/QueenieCplusplus/CCNA2020_DNS (暫略)

22. 『 SDN 』（智能網路管理）

23. 『 虛擬化技術 』

24. WLC, Wireless Lan Controller (embedded in AP)

    https://github.com/QueenieCplusplus/CCNA2020_WLC (可直接觀看產品說明書)

25. 『 Wireless LAN 』無線區域網路 

    https://github.com/QueenieCplusplus/CCNA2020_WirelessLAN

26. QoS 與 SLA (對影音串流的網路品質很重要)

# Vue JS

since 2020. 9/05

https://github.com/QueenieCplusplus/Vue  


# React UI

since 2020. 7/30 （實際工作執行至 8/14）

https://github.com/QueenieCplusplus/React_favicon (icon, browser logo)

https://github.com/QueenieCplusplus/UI_app (modules to change css)

# Git Review
since long time ago...

https://github.com/QueenieCplusplus/git

https://github.com/QueenieCplusplus/git_Q

# RWD & SEO

since 2020.8/06 

https://github.com/QueenieCplusplus/React_rwd_app (useragent and their Bot...)

# GQL Schema & Resolver

it is DB coursor as well ~

since 2018.12 & 2020, 8/02, 8/08-10 (to be continued...)

https://github.com/QueenieCplusplus/gql_tag (搭配 GQL_api1 (backend))

https://github.com/QueenieCplusplus/Github_Auth (實作 GithubAuth Login React App)

https://github.com/QueenieCplusplus/Github_Auth_API (實作 GithubAuth Login React API)

# Apollo Client/Server

since 2020.7/30 & 8/01-02 (to know GQL syntax & concept)

https://github.com/QueenieCplusplus/GQL_app (frontend)

https://github.com/QueenieCplusplus/GQL_appX (private usage)

https://github.com/QueenieCplusplus/GQL_api1 (backend)

https://github.com/QueenieCplusplus/GQL_api2 (private usage)

* Review:

express app since 2019.10-11

https://github.com/QueenieCplusplus/Backend_Script

# Global State

Redux or Context

此 hook 的出現也許可以當作取代 Redux 的備案方式。（全域物件，提供 app 中所有元件讀寫的共用物件（共同存取）。）

https://github.com/QueenieCplusplus/Context_Hook

https://github.com/QueenieCplusplus/Redux_Store

# Other React Experience
since Aug 2020

* { useState }

   only applies to func, not class.

* { withRouter } 

  https://github.com/QueenieCplusplus/React_withRouter

* { NavLink }

  https://github.com/QueenieCplusplus/React_NavLink

* { redirect }

  https://github.com/QueenieCplusplus/React_redirect

* context and Provider

  https://github.com/QueenieCplusplus/Github_Auth_API/blob/master/2_basic_context.js

* 渲染時使用 bool 判斷是否顯示，如

      {{cb is true} && 元件}

# React & React Native

(Single Page APP & Responsive Web Design & Cross-Platform Apps)

since 2018.11月下旬 (10/20 黑客松比賽後) & 2019.4 & 2019.10 & 2020.2 & 2020.6/10-6/14  & 7/08-7/21 (16 days) & 7/29-30

 React Train https://github.com/ReactTraining

new version in 2020 using ES6

https://github.com/QueenieCplusplus/ES6_App (auto bind)

https://github.com/QueenieCplusplus/React_modernJS (modern JS)

https://github.com/QueenieCplusplus/React_loginApp (React Login App)

https://github.com/QueenieCplusplus/React_catApp (button, input)

https://github.com/QueenieCplusplus/ReactNative_boolApp (when val is true, show the component)

https://github.com/QueenieCplusplus/React_kissApp (counter button with hard code, plz use forEach loop.)

https://github.com/QueenieCplusplus/React_routerApp (react-router-dom)

https://github.com/QueenieCplusplus/React_muzikApp (link, iframe)

https://github.com/QueenieCplusplus/React_tryReduxApp (flux, redux)

https://github.com/QueenieCplusplus/React_tryReduxApp2 (action, reducer, store, dispatch)

https://github.com/QueenieCplusplus/Qs_ReactNative (react native)

https://github.com/QueenieCplusplus/ReactNative_imageApp (react native, image)

https://github.com/QueenieCplusplus/ReactNative_buttonApp (react native, button)

https://github.com/QueenieCplusplus/ReactNative_videoApp (react native, video mp4)

https://github.com/QueenieCplusplus/ReactNative_mapApp (react native, map)

https://github.com/QueenieCplusplus/Map_App (react, map)

https://github.com/QueenieCplusplus/React_geoApp (react, geoLocation)

https://github.com/QueenieCplusplus/ReactNative_webviewApp (react native, webview)

https://github.com/QueenieCplusplus/React_browserApp (react, browser web url)

https://github.com/QueenieCplusplus/React_cameraApp (react, camera)

https://github.com/QueenieCplusplus/React_batteryApp (react, battery)

https://github.com/QueenieCplusplus/React_screenPlaysApp (react native, navigation)

https://github.com/QueenieCplusplus/ReactNative_listApp/blob/master/README.md (react native, List)

https://github.com/QueenieCplusplus/UI_app (UI)

https://github.com/QueenieCplusplus/a_private_app (for private usage)

ES5 & ES6 https://blog.techbridge.cc/2016/04/04/react-react-native-es5-es6-cheat-sheet/

all providing version is 2016 (ES5)

* pre-study:

https://github.com/QueenieCplusplus/QuickGoThru#腳本語言

https://github.com/QueenieCplusplus/SocketIO (Express App)

https://github.com/QueenieCplusplus/AI_Watson (AI Express App)

https://github.com/QueenieCplusplus/Express_NodeRed (private)

* main-research:

https://github.com/QueenieCplusplus/npx_app (React App)

* OAuth to Login Feature 第三方登入認證

https://github.com/QueenieCplusplus/Backend_Script/tree/master/Auth

https://github.com/QueenieCplusplus/React_loginApp (React Login App, not work, Redux is difficult)

https://www.itread01.com/content/1544003766.html (ref doc)

https://github.com/QueenieCplusplus/FB_oauth （FB SDK)

https://github.com/QueenieCplusplus/Google_oauth (Google API)

* react-syntax:

  ＊ https://github.com/QueenieCplusplus/Reactsyntax_state 狀態與屬性 

  ＊ https://github.com/QueenieCplusplus/Reactsyntax_dom 類別的工廠與元件的實例元素

  ＊ https://github.com/QueenieCplusplus/Reactsyntax_flux 資料流，事件觸發導致UI的更新

  ＊ https://github.com/QueenieCplusplus/Reactsyntax_eventHandler 事件物件及內部的共用屬性和事件處理器

  ＊ https://github.com/QueenieCplusplus/Reactsyntax_propTypes 並非必要，建議使用狀態

  ＊ https://github.com/QueenieCplusplus/Reactsyntax_reactHtmlTag 超文本標記語言的標籤

  ＊ https://github.com/QueenieCplusplus/Reactsyntax_mixin 多元件共享行為與角色

* features:

  ＊ 表單介面 https://github.com/QueenieCplusplus/React_form 

  ＊ 複選項框 https://github.com/QueenieCplusplus/React_checkbox (受控元件示範)                                            

  ＊ 按鈕選單 https://github.com/QueenieCplusplus/React_radio (不受控元件示範)

  ＊ 收發信件 https://github.com/QueenieCplusplus/React_email (含樣式的附加元件)

* server side renderer:

  ＊ 伺服器渲染 https://github.com/QueenieCplusplus/React_static_markup (SEO 、 Async)

* architecture:

  ＊ 路由元件 https://github.com/QueenieCplusplus/React_router

  ＊ 自動測試  https://github.com/QueenieCplusplus/React_test (Jest)
  
  ＊ 自定義元件 https://github.com/QueenieCplusplus/React_component
  
  ＊ 單向資料流 https://github.com/QueenieCplusplus/React_flux (Flux & Immutable)

* UI transition group:

   ＊ https://github.com/QueenieCplusplus/React_css (CSS)

   ＊ ... (Interval Renderer & requestAnimationFrame)

# Cloud Service (VM)
since 2018.6 & 2020.7/02 - 7/04 (3 days)

* preview: https://github.com/QueenieCplusplus/BaaS (DB, Firebase + Firestore)

     https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#vm (VM)

     https://github.com/QueenieCplusplus/ICND_PPP/blob/master/README.md#isp--cloud-service (ISP)

* GCP

    * Developer, Google App Scripts
    
      導讀：https://medium.com/@dustfantasy/google-app-script-到底是什麼-6a37a06a85a8
      
      實驗：https://github.com/QueenieCplusplus/GCP_GAS 
      
      (串接 sheet API、自動寄信、行事曆、會議室借用通知、翻譯器、天氣預報)
     
    
    * System 系統管理： Cloud Consol & Cloud Shell & Cloud Mobile App
    
      前導：https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#linux-shell
      
      2020: 待續。
    
    * Serverless/CPU 應用程式的執行環境, App Engine
    
      GCP 重點產品！（待續）
    
    * DB 資料庫, Big Query + DataFlow + Pub/Sub 
    
      前導：https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#dba
    
      2020: 待續。

    
* GCP 網路

    * GCE 虛擬機（遠端部署環境）
    
      https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#vmware-虛擬化技術-in-2018
    
    * 雲端記憶體
    
      前導：資料結構 https://github.com/QueenieCplusplus/1216Data_Structure
      
      2020: 待續。

    * K8s 容器管理技術, GKE
    
      https://github.com/QueenieCplusplus/K8s
      
      https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#nginx--k8s-in-2020

    * Cloud Developer, Cloud SDK 
    
      GCP 重點產品！（待續）

    * Security 安全, Cloud IAM
    
      前導: https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#資安研究
      
      2020: 待續。
    
    * Hybrid 混合雲, Anthos
    
      GCP 重點產品。
    
    * Network: Coud CDN + DNS + VPC
    
      前導: https://github.com/QueenieCplusplus/QuickGoThru#ccna-revsersion-in-2020
      
      2020: https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#cdn-in-2020

    
* GCP 產業應用

    * Streaming 串流影音, Anvato
    
    * Medical 醫療, Apigee Healthcare APIx
    
    * Bank 銀行, Apigee Open Banking APIx
    
* GCP 2nd generation support Langs:

     （python 3 、 Node.js 、 Java 11 、  Go 1.12+ 、 PHP 7）


# CCNP
since 2020.6/26 ~ 7/01 (尚有 3 個子議題待完成。)

* pre-study: 

   https://github.com/QueenieCplusplus/QuickGoThru#ccnp-osi-layer-2-3 
(EIGRP & OSPF)

   https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#cisco-router 
(Dynamic Routing for Private IP)

* main-research:

1. Routing, 路由概念

  * Link-State
  
     https://github.com/QueenieCplusplus/CCNP_Linkstate (包含 OSPF)
     
     https://github.com/QueenieCplusplus/IGP_and_BGP#advertisement (LSA 的限制)
  
  * IGRP
  
     https://github.com/QueenieCplusplus/CCNP_IGRP （包含路由器的收斂方式、RIP）
     
  * Comparison of Dynamic Routing
  
     https://github.com/QueenieCplusplus/CCNP_Routing （包含 EIGRP）
     
  * HSRP
  
     回顧：https://github.com/QueenieCplusplus/HSRP (不見於 CCNP, 請詳見 Cisco Routing 一書)
       
-------------------------------

2. VPN, 虛擬私有網路 

   https://github.com/QueenieCplusplus/Networking/blob/master/VPN.md (pre-study of PPP)
   
   https://github.com/QueenieCplusplus/CCNP_VPN

3. ADSL, 非對稱數位用戶訂閱專線/迴路

   https://github.com/QueenieCplusplus/CCNP_ADSL
   
   接線請參考：https://github.com/QueenieCplusplus/ICND_Connection

-------------------------------

4. EIGRP (能選擇最佳路徑的路由協定)

   https://github.com/QueenieCplusplus/CCNP_EIGRP_2

5. OSPF （可高負載 for ISP）

   https://github.com/QueenieCplusplus/CCNP_OSPF_2
   
6. 多區域的 OSPF (for ISP)
   
-------------------------------

7. AS, 自治系統 (for ISP)

   https://github.com/QueenieCplusplus/CCNP_BGP
   
8. BGP, 邊界閘道器協定 (for ISP) 

   回顧：https://github.com/QueenieCplusplus/BGP
   
   新研究：https://github.com/QueenieCplusplus/CCNP_BGP (封包分析)
   
   指令操作：https://github.com/QueenieCplusplus/CCNP_BGP_CLI

-------------------------------

9. Route Redistribution, 路徑的再次配置

10. IP, Subnet Mask, VLSM, CIDR 位址的規劃

    https://github.com/QueenieCplusplus/CCNP_IP (CIDR 非常重要，但僅有 EIGRP 和 OSPF 支援)

11. IP ACL, 網路流量管理

    回顧：https://github.com/QueenieCplusplus/ICND_ACL (指令用法)
    
    新研究：https://github.com/QueenieCplusplus/CCNP_IP_ACL (基本觀念)


# ICND (CCNA)
since 2020.6/16 ~ 6/22

* pre-study:

https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#ccda-cisco-certified-design-associate-網路架構師專業 (LAN & WAN)

https://github.com/QueenieCplusplus/Networking

https://github.com/QueenieCplusplus/CCNP_DataLink

https://github.com/QueenieCplusplus/Network_Infra#graphics-of-network-placement

* OSI 7 Layer

https://github.com/QueenieCplusplus/ICND_OSI_7Layer

https://github.com/QueenieCplusplus/ICND_Physical_Layer

* Hub (非網路設備)

https://github.com/QueenieCplusplus/ICND_Physical_Layer#集線器 (集線器)

* Bridge | L2 SW

https://github.com/QueenieCplusplus/ICND_Bridge (橋接器的交換技術)

https://github.com/QueenieCplusplus/ICND_Data_Link_Layer (乙太網路中最常見的交換技術)

https://github.com/QueenieCplusplus/ICND_Frame (資料框內容解析)

https://github.com/QueenieCplusplus/ICND_Internet_Packet (網路封包)

* Router

https://github.com/QueenieCplusplus/ICND_Internet_Packet#路由設備 (路由器與路由表)

https://github.com/QueenieCplusplus/ICND_TCP

* 接線

https://github.com/QueenieCplusplus/ICND_Connection (RJ45 & TxRx)

* 指令

https://github.com/QueenieCplusplus/ICND_CLI (交換器與路由器設定指令)

https://github.com/QueenieCplusplus/ICND_TCPIP/blob/master/README.md#ip-set-up (為交換器介面、路由器介面、主機設定邏輯網路位置)

* CDP | LLDP

https://github.com/QueenieCplusplus/ICND_CDP (相鄰設備)

* IFS

https://github.com/QueenieCplusplus/ICND_IFS (ISO 檔案系統)

* Telnet (SSH)

https://github.com/QueenieCplusplus/ICND_Telnet (遠端設備)

* SW

  * 交換器運作原理、設定、MAC address table (略，請詳 Bridge)

* Vlan 

  * sub-prestudy
  
    https://github.com/QueenieCplusplus/Networking/blob/master/VLan.md (STP & VTP)

https://github.com/QueenieCplusplus/ICND_VLAN (虛擬區域網路，網管人的主要工作任務)

https://github.com/QueenieCplusplus/ICND_VLAN_Route (虛擬區域網路內的路由活動)

* TCP/IP 

https://github.com/QueenieCplusplus/ICND_TCPIP (傳輸層與網路層)

https://github.com/QueenieCplusplus/ICND_TCPIP#subnet-mask (網路遮罩)

* IP Route 

   * #sh ip route 
   
   * sub-prestudy
   
     https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#ccnp-osi-layer-2-3
     
   * https://github.com/QueenieCplusplus/ICND_IP_Route (路徑選擇)
   

* PPP 

   * sub-prestudy
   
      https://github.com/QueenieCplusplus/Networking/blob/master/VPN.md

   #ppp authentication 
   
   * https://github.com/QueenieCplusplus/ICND_PPP  (點對點序列式連線)
   
* Access Control

   #access list _ permit ip subnetmask (存取控制)
   
   * https://github.com/QueenieCplusplus/ICND_ACL
   
* Apple Talk (deprecated)

          1990年代，TCP/IP興起，主導了網際網路，使得這個協定支援的許多功能需要重新實作，
          以適應TCP/IP建立的環境。因此在2009年釋出Mac OS X v10.6之後，
          蘋果公司已經不再支援AppleTalk。


# DBA
since 2020.5/25 ~ 6/09 (14 days)

* pre-study:

https://github.com/QueenieCplusplus/QuickGoThru#sql

https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#postgresql

https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#hadoop

https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#dba-1

* Server Architecture 伺服器建置圖

https://github.com/QueenieCplusplus/Server_Architecture/blob/master/README.md

* High Availability 資料庫熱備援

https://github.com/QueenieCplusplus/HA_solutions

* DB Cluster 資料庫叢集

https://github.com/QueenieCplusplus/DB_Cluster

* SQL Access & Statement（DDL / DML） 資料存取與操作述句 

https://github.com/QueenieCplusplus/SQL_Statement

* Sorted using Order By 排序資料

https://github.com/QueenieCplusplus/SQL_Order_By

* null or not null 預設可否為空

https://github.com/QueenieCplusplus/SQL_NULL

* Functions 資料庫函數(有回傳值, 可以回傳 text or blob or string)

https://github.com/QueenieCplusplus/SQL_Fn

https://github.com/QueenieCplusplus/PostgreSQL/blob/master/psql_function_tips.pdf

* Stored Procedure 預存函數(無回傳值, 可以回傳 table )

https://github.com/QueenieCplusplus/SQL_Stored_Procedure

https://github.com/QueenieCplusplus/SQL_Stored_Procedure2

* Event Scheduler 事件排程器

https://github.com/QueenieCplusplus/SQL_Event_Scheduler

* Error Handler 錯誤處理經驗

https://github.com/QueenieCplusplus/SQL_Error_Code

* Flow Control 流程處理環節

https://github.com/QueenieCplusplus/SQL_SW_CASE (包含 if - else )

* Time Utility 時間工具

https://github.com/QueenieCplusplus/SQL_Time_Range

* Data Type 資料型別

https://github.com/QueenieCplusplus/SQL_Data_Type

* In Loop 迴圈

https://github.com/QueenieCplusplus/SQL_Not_In

* API

https://github.com/QueenieCplusplus/SQL_and_API/blob/master/README.md

https://github.com/QueenieCplusplus/API

# Linux Shell 
since 2019.7.01 ~ 8.01 & 2020.5/21.22

    讓我嘶吼一下！ 兩年半來買了一百多本科技書，終於輪到這本，呦呼～～～


* Basic Usage

  * ./
  
  * source
  
  * ~/.bash_profile
  
  * $PATH
  
  * alias

    https://github.com/QueenieCplusplus/LinuxShell_cmd (execution & startupFile)

* Network Setup

  * ifconfig in Unix and Linux || ipconfig in Windows
  
    https://github.com/QueenieCplusplus/LinuxShell_netmask (subnetmask)
  
  * route in Linux || netstat in Unix || route print in Windows
  
    https://github.com/QueenieCplusplus/LinuxShell_route (gateway)
  
* Networking
  
  * nslookup
  
    https://github.com/QueenieCplusplus/LinuxShell_nameserver 
  
  * ping
  
    https://github.com/QueenieCplusplus/LinuxShell_ping (^C or ^Z)
    
* Remote Connection
  
  * ssh and scp
  
    https://github.com/QueenieCplusplus/LinuxShell_ssh
  
  * ftp and wget
  
    * w

* Sys Admin

  * auth and root
  
    https://github.com/QueenieCplusplus/LinuxShell_root (whoami)
    
    * group and member
  
  * kernel info
  
    https://github.com/QueenieCplusplus/LinuxShell_kernel (uname)
    
    * cpu and memory
    
* Common Utility

  * Process & IPC
  
     * ps
     
      https://github.com/QueenieCplusplus/LinuxShell_semaphore (kill-9)
      
      https://github.com/QueenieCplusplus/LinuxShell_fgbg (fg or bg)

# Bash  (Shell Scripts for Unix)
since 2018.5 & 2019.4 & 2020.5/18 ~ 5/21 

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
since 2019.12 & 2020.5/16

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
since 2020.3 and 2020.5/17

* Preview:

https://github.com/QueenieCplusplus/PostgreSQL

https://github.com/QueenieCplusplus/QuickGoThru#搜索引擎

* Review:

https://github.com/QueenieCplusplus/PSQL_command_tool (below version 9.2)

https://github.com/QueenieCplusplus/PSQL_interactive_cli (below version 9.2)

* Where it hosts on:

https://github.com/QueenieCplusplus/PostgreSQL_Hosts

* Table & Functions

https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#dba (MySQL)


# Kernel Hackers
since 2020/4/30-5/02

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

    https://github.com/QueenieCplusplus/Kernel_Network

* VM

* Process Call & Event Log

* Kernel Tracing using System Tap

# CCNP (OSI Layer 2-3)
since 2020/4/27-29, 5/04


* Layer 2 

     *  Data Link
     
     https://github.com/QueenieCplusplus/CCNP_DataLink

* Layer 3

     * EIGRP (routing tables integration amongs routers and sw)
     
     https://github.com/QueenieCplusplus/CCNP_EIGRP

     * OSPF (forward packets amongst AS)
     
     https://github.com/QueenieCplusplus/CCNP_OSPF

# VM 
since 2020/4/22, 23 

https://github.com/QueenieCplusplus/VM

# System Security (SSCP)
since 2020/4/13, 21, 22, 24

https://github.com/QueenieCplusplus/SSCP


# C Again
since 2020/4/07 - 4/08, 4/11

https://github.com/QueenieCplusplus/Linux_sys_program


# Perl Again
since 2020/4/04 - 4/06

https://github.com/QueenieCplusplus/Perl_Again

# Cisco Router
since 2020/3/28 - 4/03, 5/03

https://github.com/QueenieCplusplus/IGP_and_BGP (自治系統網路架構間的網路設計)

https://github.com/QueenieCplusplus/PPP (點對點協定)

https://github.com/QueenieCplusplus/Network_Infra (路由與交換機) 

https://github.com/QueenieCplusplus/Routing_Strategy (路由策略)

https://github.com/QueenieCplusplus/Subnet_mask (子網域遮罩技術及其運算原理)

https://github.com/QueenieCplusplus/RIF (Routing Table's Field)

* Private IP

   * Static IP, 靜態邏輯位置設定
   
      * Static Routing, 靜態路由設定

           * https://github.com/QueenieCplusplus/Static_Routing (Static Routing)
           
           * https://github.com/QueenieCplusplus/RIP (Distance-Vector 距離向量)
          
      * Dynamic Routing, 動態路由設定     
      
           * 各路由方式的比較 https://github.com/QueenieCplusplus/CCNP_Routing
    
           * https://github.com/QueenieCplusplus/CCNP_EIGRP (僅 Cisco 支援)
     
           * https://github.com/QueenieCplusplus/HSRP (HSRP, RIP 的擴充方案)

           * https://github.com/QueenieCplusplus/OSPF (LSA 鏈結狀態通告, 也是廣播) 
     
           * https://github.com/QueenieCplusplus/CCNP_OSPF (常見於 ISP)

   * Dynamic IP, 動態邏輯位置分配

     * DHCP, 動態主機設定 (協定)
   
* Public IP

   which is my ip
   
   https://github.com/QueenieCplusplus/NAT (NAT)

Terminology:

https://github.com/QueenieCplusplus/Networking (網路觀測技術及網路應用層)

Codebase: 

https://github.com/QueenieCplusplus/Band_Width (thruput in Bit & storage in Bytes, and display their conversion in code)

Bridge: 

https://github.com/QueenieCplusplus/Source_Route_Bridging (Source_Route)

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# CCDA (Cisco Certified Design Associate 網路架構師專業)

since 2020/4/02 - 4/04 & 4/09, 5/03

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

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# DBA 
since 2020/3/04 & 3/07

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

https://github.com/QueenieCplusplus/CrawlerByUsingPython


# 解析封包
since 2017/10/20 & update on 2020/02/27 

https://github.com/QueenieCplusplus/Extension_IP_Header (Http Header)

https://github.com/QueenieCplusplus/Http_header (Http-Header-Fields & get API app)

https://github.com/QueenieCplusplus/Py_Parser (Http Req-Res Chain)

https://github.com/QueenieCplusplus/DataMining_Spark (Smarter Pandas)

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 網頁前端
since 2020/2/29 quickstart

https://github.com/QueenieCplusplus/React (React)

https://github.com/QueenieCplusplus/H5 (HTML5)

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 容器管理工具和瀏覽器平台解讀執行中的程式碼
since 2020/1/04 quickstart

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
  
  查詢詞語 
  
  https://github.com/QueenieCplusplus/SQL_DML

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

https://github.com/QueenieCplusplus/1122Try (C in 2019)

https://github.com/QueenieCplusplus/Qs_C (C in 2020)

https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#c-again (C for System Program)

https://github.com/QueenieCplusplus/Cplusplus (C++)
    
https://github.com/QueenieCplusplus/Golang (Golang 還原)

https://github.com/QueenieCplusplus/ObjC (Object-C)

https://developer.apple.com/swift/ Swift4官方網站 since 2018/3

https://kotlinlang.org Kotlin官方網站 since 2018/10 & 2019/5

https://github.com/QueenieCplusplus/AndroidApp/tree/master/2019_java_code (Java since 2018/5 & 2019/8)

https://gist.github.com/PattyAppier?fbclid=IwAR1DdgxMcrm2HJJBTpjEQkti94GkYRK1i039JQy8rX89iNoeYlxid0ORRlI (Android)
   
＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 腳本語言
since 2019/8, rollback on 2019/12/20

https://github.com/QueenieCplusplus/Backend_Script 登入驗證功能（Nodejs: Express 專案未還原）

https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#react (js: React 專案，進行中)

https://github.com/QueenieCplusplus/Backend_Script2 建立會議對話識別符 (php: CI & Laravel 專案未還原)
   
https://github.com/QueenieCplusplus/Backend_Script3 運算與圖像工具 (python: Django 還原)

https://github.com/QueenieCplusplus/Ruby_Cart 電商常用購物車 (ruby: Rail & Rack)

https://github.com/QueenieCplusplus/Perl (perl)

https://github.com/QueenieCplusplus/QuickGoThru/blob/master/README.md#perl-again (perl again)

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


* UML & Spec

     https://github.com/QueenieCplusplus/UML_Spec

* iOS 11 : pattyappier & pattyluvapp

     (code 尚未還原)
     

* Android 3: katesandroidapp & katesapp2019

     https://github.com/QueenieCplusplus/AndroidApp 
     

* React Native : redpint819

    https://github.com/QueenieCplusplus/Qs_ReactNative (跨平台 jsx from FB)

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# 雲端後端

since 2018/6, all repos will be hidden from public

* BaaS : quinoaPy

  https://github.com/QueenieCplusplus/BaaS （唯一還原的資源）
  
 https://github.com/QueenieCplusplus/SSCP_CloudSecurity/blob/master/README.md#clouds-platform-雲端服務平台 (PaaS)

* iCloud : pattyluvapp

https://gist.github.com/PattyAppier?fbclid=IwAR1DdgxMcrm2HJJBTpjEQkti94GkYRK1i039JQy8rX89iNoeYlxid0ORRlI

＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿＿

# Content Delivery Network (Storage System)

since 2017/11

Content is stored in Objective Sotage, which is distributed to Distributed Nodes (Mirror) to improve Internet Consumption Speed.

























































































