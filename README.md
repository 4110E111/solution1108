
# OSI 模型與TCP/IP protocal suite
- (一) 實體層 (Physical Layer)
  - 訂定電腦連接的電氣特定協定

- (二) 資料鏈結層 (Data-Link Layer)
  - 訊框 (frame) 與實體位置 (MAC) 
分為兩個子層：
- (三) 網路層 (Network Layer)
  - 邏輯定址
  -資料封包 (packet) 的傳輸路徑(Routing)選擇
- (四) 傳輸層 (Transport Layer)
  - 提供可靠或不可靠的遞送
  - 重傳之前先校正錯誤
- (五) 交談層 (Session Layer)
  - 負責建立、管理、以及終止兩個通訊主機的對話
- (六) 表現層 (Presentation Layer
  - 處理不同資料格式之間的字碼轉換及編碼及解碼
- (七) 應用層 (Application Layer)
  - 提供使用者介面
## OSI有七層?簡述其功能

## 底下網路設備運作在哪一層? Hub, switch, router, L4-switch, proxy
## TCP/IP有那些層?寫出與OSI七層模型的對應!

## 簡述底下應用層協定(英文全名與簡單功能說明):
- HTTP vs HTTPs
  - HTTP
    - HyperText Transfer Protocol 超文本傳輸協定
    - 是一種用來傳輸超媒體文件的應用層協定
    - 是全球資訊網的數據通信的基礎。
    - 是一種無狀態協定
    - 藉由 TCP 作為資料的傳輸方式
  - HTTPS
    - HyperText Transfer Protocol Secure 超文本傳輸安全協定
    - S 是 Secure 的意思
    - HTTPS 透過 HTTP 進行通訊
    - 利用 SSL/TLS 來加密封包
    - 在不安全的網路上建立一個安全信道
- DNS vs DNSsec
  - DNS
    - Domain Name System 網域名稱系統
    - 是網際網路的電話簿
    - DNS 將網域名稱轉換為 IP 位址
    - 每個 Domain Name 必須對應要一組 IP
    - 長度不能超過253個字元
- telnet vs ssh
  - telnet
    -  
- ftp vs sftp
- smtp, pop3
- SNMP

## 簡述底下傳輸層協定(英文全名與簡單功能說明):TCP vs UDP
- TCP
  - reliable(可靠的) vs unreliable(不可靠的)
  - TCP three-way handshaking(三項交握)  
  - TCP syn flood attack

## 簡述底下網路層協定(英文全名與簡單功能說明): IP   ICMP
- IP
- ICMP
