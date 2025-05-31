# BuptNetworkLab_PacketAnaysis

这个仓库是北京邮电大学2024-2025学年《计算机网络》课程实验二：IP 和 TCP 数据分组的捕获和解析 的作业仓库。由我个人完成。

## 项目内容

实验要求内容：
1. 捕获在使用网络过程中产生的分组：IP 数据包、ICMP 报文、DHCP 报文、TCP 报文段；
2. 分析各种分组的格式，说明各种分组在建立网络连接和通信过程中的作用；
3. 分析 IP 数据报分片的结构：理解长度大于 1500 字节 IP 数据报分片传输的结构；
4. 分析 TCP 建立连接、拆除连接和数据通信的过程；

个人拓展研究内容：
1. 捕获并分析 ARP 报文及协议；
2. 捕获并分析 IPv6 数据包及协议；
3. 捕获并分析 HTTP 报文及协议；
4. 一些与教学内容不符的实际工作情况分析：包括 IPv6 和 IPv4 混用、TCP “三次挥手”等；

## 实验环境

| 配置项          | 参数                   |
| --------------- | ---------------------- |
| 操作系统        | macOS Sequoia 15.4     |
| CPU             | Apple M3               |
| 内存            | LPDDR5 16GB            |
| 网卡            | Wi-Fi (0x14E4, 0x4388) |
| 支持 PHY        | 802.11 a/b/g/n/ac/ax   |
| Wireshark       | Version 4.4.6          |
| iTerm2 Terminal | Build 3.5.3            |

## 其他材料

关于实验报告和提交的源代码，可以从 [Release](https://github.com/Yokumii/BuptNetworkLab_PacketAnaysis/releases/) 中获取。

## 特别说明

代码不保证绝对的正确性，请谨慎借鉴或使用，并自行遵循有关学术规范，如产生任何后果与作者无关。有问题可以发起 [ISSUE](https://github.com/Yokumii/BuptNetworkLab_PacketAnaysis/issues/) ，但作者后续不一定继续维护该作业仓库。