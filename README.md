# Edifice
易语言 MCPE0.8 Server

## 写在最前 / Write at the beginning

易语言是一款中文编程语言，以中文语法和可视化设计降低学习门槛，适合开发Windows桌面应用。但其局限性显著：仅支持Windows平台，生态系统匮乏，社区资源有限，缺乏国际认可，且代码可读性与维护性在复杂项目中较差，难以适应现代开发需求。此项目是闲着没事干做的

易语言 (EPL) is a Chinese-native programming language using Chinese syntax and visual design, ideal for Windows desktop apps. However, it faces major limitations: Windows-only compatibility, weak ecosystem, limited community support, lack of global recognition, and poor code readability/maintainability in complex projects, hindering modern development. This project is only made for fun

## 实现的特性

- RakNet协议
  - [x] 按照ip地址的会话分离
  - [x] 封包处理
  - [x] 完整握手流程
  - [ ] 分包合并 (W.I.P)
  - [ ] ping/pong协议 (W.I.P)
  - [ ] ACK/NACL协议
  - [ ] 超过mtuSize的封包分包处理

- [ ] MCPE协议握手流程(Player Login)
 
- 其他
  - [x] 二进制数据流(BianyStream)
  - [ ] 日志记录(W.I.P)
