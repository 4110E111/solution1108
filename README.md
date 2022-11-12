
# OSI 模型與TCP/IP protocal suite
## OSI有七層?簡述其功能
- (一) `實體層` (Physical Layer)
  - 訂定電腦連接的電氣特定協定
- (二) `資料鏈結層` (Data-Link Layer)
  - 訊框與實體位置 
- (三) `網路層` (Network Layer)
  - 邏輯定址
  - 資料封包的傳輸路徑選擇
- (四) `傳輸層` (Transport Layer)
  - 提供可靠或不可靠的傳送
- (五) `會議層` (Session Layer)
  - 負責建立、管理、以及終止兩個通訊主機的對話
- (六) `表現層` (Presentation Layer)
  - 處理不同資料格式之間的字碼轉換及編碼和解碼
- (七) `應用層` (Application Layer)
  - 提供使用者介面
## 底下網路設備運作在哪一層? Hub, switch, router, L4-switch, proxy
- Hub
  - 第一層
- Switch
  - 第二層 
- Router
  - 第三層
- L4-switch
  - 第四層
- Proxy
  - 第七層
## TCP/IP有那些層?寫出與OSI七層模型的對應!
- (一) `網路存取層` (Network Access Layer) --> 實體層、資料鏈結層
- (二) `網路互連層` (Internet Layer) --> 網路層
- (三) `傳輸層` (Transport Layer) --> 傳輸層
- (四) `應用層` (Application Layer) --> 會議層、表現層、應用層
## 簡述底下應用層協定(英文全名與簡單功能說明):
- HTTP vs HTTPs
  - HTTP
    - 超文本傳輸協定 (HyperText Transfer Protocol)
    - 是一種用來傳輸超媒體文件的應用層協定
    - 是全球資訊網的數據通信的基礎。
    - 是一種無狀態協定
    - 藉由 TCP 作為資料的傳輸方式
  - HTTPS
    - 超文本傳輸安全協定 (HyperText Transfer Protocol Secure)
    - S 是 Secure 的意思
    - HTTPS 透過 HTTP 進行通訊
    - 利用 SSL/TLS 來加密封包
    - 在不安全的網路上建立一個安全信道
- DNS vs DNSsec
  - DNS
    - 網域名稱系統 (Domain Name System)
    - 是網際網路的電話簿
    - DNS 將網域名稱轉換為 IP 位址
    - 每個 Domain Name 必須對應要一組 IP
    - 長度不能超過253個字元
- telnet vs ssh
  - telnet
    - Telnet 是一種應用層協議 
    - 提供雙向、以文字字串為主的命令列介面互動功能
    - 屬於TCP/IP協議族的其中之一
    - 常用於伺服器的遠端控制
    - Telnet 是常用的遠程控制 Web 服務器的方法
  - ssh
    - 安全外殼協定 (Secure Shell Protocol)
    - 是一種加密的網路傳輸協定
    - 可在不安全的網路中為網路服務提供安全的傳輸環境
    - SSH 使用頻率最高的場合是類Unix系統 
    - SSH 最常見的用途是遠端登入系統
- ftp vs sftp
  - ftp
    - 檔案傳輸協定 (File Transfer Protocol)
    - 是一個用於在電腦網路上在客戶端和伺服器之間進行檔案傳輸的應用層協定 
  - sftp 
    - Secure FTP 安全檔案傳送協定 
- smtp, pop3
  - smtp
    - 簡單郵遞傳送協定 (Simple Mail Transfer Protocol) 
  - pop3 
    - 郵局協議 (Post Office Protocol) 
- SNMP
    - 簡單網路管理協定 (Simple Network Management Protocol)

## 簡述底下傳輸層協定(英文全名與簡單功能說明):
- TCP vs UDP
  - TCP
    - 傳輸控制協定 (Transmission Control Protocol)
  - UDP
    - 使用者資料包協定 (User Datagram Protocol)
  
  
 - reliable(可靠的) vs unreliable(不可靠的)
 - TCP three-way handshaking(三項交握)  
 - TCP syn flood attack

## 簡述底下網路層協定(英文全名與簡單功能說明):
- IP
  - 網際協定 (Internet Protocol)
- ICMP
  - 網際網路控制訊息協定 (Internet Control Message Protocol)
