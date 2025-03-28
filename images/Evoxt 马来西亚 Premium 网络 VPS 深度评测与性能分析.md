# Evoxt 马来西亚 Premium 网络 VPS 深度评测与性能分析

## 评测概览

本次测试针对 Evoxt 马来西亚 Premium 网络的 VM-0.5 套餐，具体配置如下：
- **CPU**: 1核
- **内存**: 512MB
- **存储**: 5GB SSD
- **流量**: 250GB(双向)
- **带宽**: 1Gbps

> **商家背景**:  
> Evoxt 成立于2020年，是马来西亚本土服务商，拥有自有ASN AS149440/AS212083。目前在全球设有多个数据中心，包括香港、日本东京/大阪、马来西亚、美国洛杉矶/纽约、英国、德国、荷兰、波兰、加拿大和澳大利亚等地。其中日本、香港和马来西亚提供优化网络(Premium Net)。支持中文工单服务，接受PayPal、支付宝、Stripe和加密货币等多种支付方式。

👉 [【点击查看】2025年最新 Evoxt优惠码及特价云服务器方案汇总](https://bit.ly/evoxt)

## 服务器基础性能测试

code
CPU Model          : AMD EPYC-Genoa Processor
CPU Cores          : 1 @ 4192.080 MHz
CPU Cache          : 1024 KB
AES-NI             : ✓ Enabled
VM-x/AMD-V         : ✗ Disabled
Total Disk         : 5.8 GB (2.3 GB Used)
Total Mem          : 457.8 MB (90.3 MB Used)
Total Swap         : 1024.0 MB (0 Used)
System uptime      : 0 days, 0 hour 12 min
Load average       : 0.04, 0.09, 0.05
OS                 : Debian GNU/Linux 12
Arch               : x86_64 (64 Bit)
Kernel             : 6.1.0-9-amd64
TCP CC             : bbr
Virtualization     : KVM
IPv4/IPv6          : ✓ Online / ✓ Online
Organization       : AS149440 Evoxt Enterprise
Location           : Kuala Lumpur / MY
Region             : Kuala Lumpur
----------------------------------------------------------------------
I/O Speed(1st run) : 923 MB/s
I/O Speed(2nd run) : 978 MB/s
I/O Speed(3rd run) : 963 MB/s
I/O Speed(average) : 954.7 MB/s
----------------------------------------------------------------------
Node Name        Upload Speed      Download Speed      Latency     
Speedtest.net    895.08 Mbps       805.75 Mbps         1.30 ms     
ShangHai CU      515.00 Mbps       491.69 Mbps         136.74 ms   
Paris, FR        266.64 Mbps       461.88 Mbps         233.35 ms   
Amsterdam, NL    235.82 Mbps       116.44 Mbps         245.52 ms   
Singapore, SG    624.63 Mbps       576.56 Mbps         64.48 ms    
Tokyo, JP        826.94 Mbps       673.37 Mbps         74.64 ms    
----------------------------------------------------------------------
Timestamp          : 2025-02-06 05:31:38 EST

## 全球网络性能分析

### 国际带宽测试结果

code
Node Name                       IP address                      Download Speed      Latency (TCP)   
----- Global (CDN) -----           
CacheFly, CDN                   205.234.175.175                  519.27 Mbps        6.742ms         
Cloudflare, CDN                 172.66.0.218                     672.33 Mbps        6.109ms         
----- Asia-Pacific -----           
Leaseweb, HongKong, CN          64.120.117.34                     46.03 Mbps        35.221ms        
Gcore, HongKong, CN             92.223.76.254                    199.73 Mbps        37.414ms        
EDIS, HongKong, CN              158.255.208.12                    56.53 Mbps        34.507ms        
Hinet, Taiwan                   210.61.132.1                      92.15 Mbps        89.347ms        
Linode, Tokyo, JP               139.162.65.37                     22.02 Mbps        78.860ms        
Gcore, Tokyo, JP                92.223.63.254                    103.32 Mbps        79.528ms        
Vultr, Seoul, KR                141.164.34.61                     36.76 Mbps        215.377ms       
Linode, Singapore, SG           139.162.23.4                     120.47 Mbps        6.412ms         
Vultr, Sydney, AU               108.61.212.117                    90.84 Mbps        98.033ms        
Universitas, Jakarta, ID        152.118.24.42                     53.09 Mbps        20.188ms        
----- Western Asia -----           
Dediserve, Dubai, UAE           109.169.72.30                     23.15 Mbps        191.843ms       
EDIS, Tel Aviv, IL              193.182.144.14                    27.71 Mbps        256.281ms       
----- Western US -----             
Linode, Fremont, US             50.116.14.9                       29.67 Mbps        189.027ms       
Leaseweb, San Francisco, US     23.81.166.99                      54.56 Mbps        191.490ms       
----- Central US -----             
Vultr, Chicago, US              107.191.51.12                     46.31 Mbps        206.161ms       
----- Eastern US -----             
Linode, Newark, US              50.116.57.237                     19.10 Mbps        227.566ms       
Leaseweb, Washington, US        23.105.9.80                       37.13 Mbps        239.833ms       
----- Canada -----                 
----- Western & Southern Europe -----
Linode, London, UK              176.58.107.39                     46.63 Mbps        171.792ms       
Linode, Frankfurt, DE           139.162.130.8                     44.02 Mbps        165.447ms       
Leaseweb, Amsterdam, NL         95.211.20.80                      19.96 Mbps        528.613ms       
----- Central & Eastern Europe -----
EDIS, Moscow, RU                213.183.56.10                     42.53 Mbps        200.155ms       
EDIS, Warsaw, PL                37.235.48.250                     32.44 Mbps        269.620ms       
EDIS, Bucharest, RO             194.68.44.10                      34.16 Mbps        265.808ms       
Gcore, Istanbul, TR             92.38.142.30                      37.97 Mbps        277.564ms

## 流媒体服务解锁测试

code
 ** 测试时间: Thu Feb  6 05:57:23 AM EST 2025

 ** IPv4 解锁情况
--------------------------------
 ** 您的网络为: Evoxt Enterprise (38.211.*.*)

============[ 跨国服务 ]============
 Dazn:                                  Yes (Region: MY)
 Disney+:                               Available For [Disney+ MY] Soon
 Netflix:                               Yes (Region: MY)
 YouTube Premium:                       Yes (Region: MY)
 Amazon Prime Video:                    Yes (Region: MY)
 TVBAnywhere+:                          Yes
 Spotify Registration:                  No
 OneTrust Region:                       MY [Kuala Lumpur]
 iQyi Oversea Region:                   US
 Bing Region:                           MY
 Apple Region:                          MY
 YouTube CDN:                           Tokyo
 Netflix Preferred CDN:                 Seattle, WA
 ChatGPT:                               Yes
 Google Gemini:                         Yes
 Claude:                                Yes
 Wikipedia Editability:                 Yes
 Google Play Store:                     Malaysia 
 Google Search CAPTCHA Free:            Yes
 Steam Currency:                        MYR
 ---论坛访问---
 Reddit:                                Yes

 ** IPv6 解锁情况
--------------------------------
 ** 您的网络为: Evoxt Enterprise (2400:8d60:3:*:*)

============[ 跨国服务 ]============
 Dazn:                                  IPv6 暂不支持
 Disney+:                               IPv6 暂不支持
 Netflix:                               仅限原创内容
 YouTube Premium:                       Yes (Region: MY)
 Amazon Prime Video:                    IPv6 暂不支持
 TVBAnywhere+:                          IPv6 暂不支持
 Spotify Registration:                  No
 OneTrust Region:                       MY [Kuala Lumpur]
 iQyi Oversea Region:                   IPv6 暂不支持
 Bing Region:                           MY
 Apple Region:                          MY
 YouTube CDN:                           Tokyo
 Netflix Preferred CDN:                 Seattle, WA
 ChatGPT:                               连接失败
 Google Gemini:                         Yes
 Claude:                                Yes
 Wikipedia Editability:                 Yes
 Google Play Store:                     Malaysia 
 Google Search CAPTCHA Free:            Yes
 Steam Currency:                        IPv6 暂不支持
 ---论坛访问---
 Reddit:                                IPv6 暂不支持

 ** TikTok区域检测
******************************************
 TikTok Region:         【US】(可能为IDC IP)
******************************************

## 服务器套餐与价格

Evoxt 提供多种VPS套餐选择：

- **VM-0.5**  
  CPU: 1核 | 内存: 512MB | 硬盘: 5GB SSD | 流量: 250G/月 | 带宽: 1Gbps  
  **$2.99/月**

- **VM-0.75**  
  CPU: 1核 | 内存: 1G | 硬盘: 10GB SSD | 流量: 250G/月 | 带宽: 1Gbps  
  **$4.99/月**

- **VM-1**  
  CPU: 1核 | 内存: 2G | 硬盘: 20GB SSD | 流量: 500G/月 | 带宽: 1Gbps  
  **$5.99/月**

- **VM-1.5**  
  CPU: 2核 | 内存: 2G | 硬盘: 20GB SSD | 流量: 500G/月 | 带宽: 1Gbps  
  **$6.95/月**

**专属优惠**:  
使用优惠码 `AFF1973-VPS` 可享受9.5折优惠（每个账号限用1次）

## 专业评测总结

**网络性能**:
- 国内平均TCP ping值: 
  - 电信87ms(广东深圳56ms - 西藏拉萨138ms)
  - 联通130ms(北京113ms - 西藏拉萨160ms)
  - 移动93ms(上海69ms - 新疆乌鲁木齐134ms)
  
**线路特点**:
- 上游供应商为xTom/NTT
- 中国大陆优化线路:
  - 回程: 三网CTGNet
  - 去程: 电信CTGNet, 联通/移动暂时NTT

**适用场景**:
- 性价比高，特别适合电信用户
- 移动和联通用户也可获得不错体验
- 适合需要东南亚节点的业务部署

👉 [【立即抢购】Evoxt马来西亚Premium网络VPS特惠套餐](https://bit.ly/evoxt)