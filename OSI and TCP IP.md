![image](https://github.com/MyDearGreatTeacher/CS2020B/raw/master/protocol.jpg)
# OSI:
7  app  (應用層)給應用軟體用的介面  
6  presentation  (表達層)雙方互相溝通用的格式  
5  session  (會議層)負責維護兩台電腦之間的通訊連接  
4  transport  (傳輸層)TCP/UDP等網路協定  
3  network  (網路層)網際網路協定  
2  data link  (資料連結層)實體位址  
1  physical  (實體層)負責管理電腦通訊裝置跟網路媒體之間的溝通  
# TCP/IP:
4  app(應用層)  例如 HTTP DNS  
提供服務直接支援用戶應用  
3  transport(傳輸層)  例如 TCP UDP  
保證資料按照正確的順序到達  
2  internet(網路互連層)  網際網路協定  
將資料從原網路傳輸到目標網路  
1  network assess(網路連結層)  乙太 WIFI  
封包從一個裝置的網路層傳輸到另外一個裝置的網路層的方法  
# 協定protocol
communcation protocol 通訊協定  
定義電腦間互相通訊且共同認定的協議標準  
為什麼要分層?  
把某些特定功能獨立起來執行效率較高  
同時每層也可以獨立進行修改跟擴充功能  
# HyperText Transfer Protocol(HTTP)(超文本傳輸協定)
應用層  
一種Client/Server的應用  
Postman / HttpWatch Professiona  
# HyperText Transfer Protocol Secure(HTTPS)(超文本傳輸安全協定)
應用層  
一種是建立一個信息安全通道，來保證數據傳輸的安全’另一種就是確認網站的真實性  
HTTPS Everywhere  
# File Transfer Protocol(FTP)(檔案傳輸協定)
應用層  
主要的功能是在Client與Server之間傳送大量檔案資料的通訊協定  
FlashFXP / Cuteftp / FileZilla / WinSCP / Wing FTP Server / CrossFTP  
# SSH File Transfer Protocol/Secret File Transfer Protocol(SFTP)(SSH檔案傳輸協定)
應用層  
一個用於在電腦網路上在Client和Server之間進行檔案傳輸的應用層協定  
SolarWinds SFTP / Syncplify.me / Globalscape / Syncplify.me Micro / Core Mini / vsftp  
# File Transfer Protocol SSL(FTPS)
應用層  
FTP標準的擴充，添加了安全通訊協定（SSL）以及其繼任者傳輸層安全性協定（TLS）的支援  
FileZilla / IIS / zFTPServer  
# TELNET(TELNET)
應用層  
主要是用來規範不同的電腦系統，經由網路連線到遠端主機進行線上作業的標準  
PuTTY / MobaXterm  
# Secure Shell(SSH)(安全外殼協定)
應用層  
專為遠程登錄會話和其他網絡服務提供安全性的協議  
WinSCP / PuTTY  
# Simple Mail Transfer Protocol(SMTP)(簡單郵件傳輸協定)
應用層  
它能夠在傳送過程中轉發電子郵件  
MailTrap / papercut / Smtp4dev  
# Post Office Protocol - Version 3(POP3 INAP4)
應用層  
專為離線郵件處理所設計  
EVO MAIL SERVER  
# Domain Name System(DNS)(網域名稱系統)
應用層  
像網際網路的通訊錄  
ViewDNS.info / DNSQuerySniffer  
# Domain Name System Security Extensions(DNSsec)(域名系統安全擴充)
應用層  
主要是在現有DNS的基礎上，加入數位簽章的機制，用來驗證DNS伺服器解析結果的真實性  
Google Domains  
# Dynamic Host Configuration Protocol(DHCP)(動態主機設定協定)
應用層  
主要是給網絡快速自動地分配IP位址  
OpenVMS  
# Lightweight Directory Access Protocol(LDAP)(輕型目錄存取協定)
應用層  
工業標準的應用協定  
Adsiedit  
# Server Message Block(SAMBA)
應用層  
用來讓UNIX系列的作業系統與微軟Windows作業系統的SMB/CIFS網路協定做連結的自由軟體  
RHEL5 – Samba  
# Simple Network Management Protocol(SNMP)(簡單網路管理協定)
應用層  
用於交換網路裝置之間的管理資訊  
Net-SNMP  
# Real-Time Messaging Protocol(RTMP)(即時訊息協定)
應用層  
由 Adobe 所有的媒體傳輸協議  
nginx/nginx-rtmp  
# Real Time Streaming Protocol(RTSP)(即時串流協定)
應用層  
專為娛樂和通信系統的使用，以控制串流媒體伺服器  
snoop / wireshark  
# Message Queuing Telemetry Transport(MQTT)(訊息佇列遙測傳輸)
應用層  
可視為資料傳遞的橋梁  
MQTTLens  
# TCP 與UDP的差異
TCP:雙向傳輸  
reliable(可靠)  
錯誤重傳 / ThreeWay Handshaking(三向交握)  
UDP:單相傳輸  
un-reliable(不可靠)  
可能會在網路傳送過程中丟失﹑重複﹑或不依順序  
# Internet Protocol Security(IPSec)(網際網路安全協定)
如果在路由器或防火牆上執行了IPSec，它就會為周邊的通信提供強有力的安全保障。一個公司或工作組內部的通信將不涉及與安全相關的費用  
# Internet Control Message Protocol(ICMP)(網際網路控制訊息協定)
是網際網路協定套組的核心協定之一。它用於網際網路協定（IP）中傳送控制訊息，提供可能發生在通訊環境中的各種問題回饋  
# 網路硬體設備 Network Devices
# HUB(集線器)
實體層  
匯集所有區域網路中的電腦  
# Repeater(中繼器)
實體層  
一個將輸入訊號增強放大的類比裝置  
# Switch(交換器)
資料鏈結層  
通過報文交換接收和轉發資料到目標裝置，它能夠在電腦網路上連接不同的裝置  
# Bridge(橋接器)
資料鏈結層  
使用類似檔案瀏覽器的格式，管理多媒體檔案  
# Router(路由器)
網路層  
可以決定封包從來源端到目的端所經過的路由路徑  
# L4 Switch(第四層交換器)
傳輸層  
頻寬管理、優先次序處理以及策略性網路管理  
# Proxy(網路代理) 
代替網站的主機伺服器  
# Virtual Local Area Network(VLAN)虛擬區域網路
一種建構於區域網路交換技術（LAN Switch）的網路管理的技術  
# 各種address位址
# PORT(通訊埠)
在電腦網路中是一種經由軟體建立的服務，在一個電腦作業系統中扮演通訊的端點（endpoint）  
# Internet Protocol Address(IP address)(IP位址)/(網際網路協定位址)
網際協定（Internet Protocol）中用於標識傳送或接收資料報的裝置的一串數字  
# Media Access Control Address(MAC address)(媒體存取控制位址)
一個用來確認網路裝置位置的位址  
