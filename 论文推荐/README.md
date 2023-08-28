### 论文推荐

- [What Your Firmware Tells You Is Not How You Should Emulate It: A Specification-Guided Approach for Firmware Emulation](https://mp.weixin.qq.com/s/gWnvQZlgrkQklDrNI2EQwg)

  > CCS 2022 华中科技大学  周威
  >
  > 安全研究GoSSIP阅读推荐 2022-12-29

  > 从设备手册中的自然语言描述语句中提取出条件动作规则，构建外设交互状态机，进行物联网固件仿真。

- [坏字符：难以察觉的NLP攻击](https://mp.weixin.qq.com/s/yFPQ33aNZrzV4045WPdH2Q)

  > IEEE S&P 2022 剑桥大学
  >
  > NISL实验室

  > 基于语言编码的文本对抗攻击（利用不可见、同形字、重定向、删除等Unicode编码），可在保证对抗文本难以被人类识别（攻击“扰动更小”）的基础上，达到与已有的、易被人类察觉（攻击“扰动更大”）的对抗文本相似的攻击效率。

- [从开源项目和库的Issue和Bug报告中挖掘情报](https://mp.weixin.qq.com/s/WaPpf20x7flfePP5-T7XIg)

  > ISI 2018
  >
  > 安全学术圈

- [AEM: Facilitating Cross-Version Exploitability Assessment of Linux Kernel Vulnerabilities](https://mp.weixin.qq.com/s/nxY2Tm8lJPpstgp1JZRohQ)

  > IEEE S&P 2023
  >
  > 安全研究GoSSIP阅读推荐 2023-01-03 AEM

  > 跨内核版本的自动化漏洞利用程序迁移。

- [Open-CyKG：开放式网络威胁知识知识图谱](https://mp.weixin.qq.com/s/dxYkIbGDOFOFL6Ta-ixpKA)

  > [I Sarhan](https://scholar.google.com/citations?user=Otq5vX0AAAAJ&hl=zh-CN&oi=sra), [M Spruit](https://scholar.google.com/citations?user=GFvyyeAAAAAJ&hl=zh-CN&oi=sra) - Knowledge-Based Systems, 2021 - Elsevier
  >
  > 安全学术圈

  > 包括三个主要模块
  >
  > - 用于从非结构化的APT报告中提取关系三元组的普通OIE系统
  > - 一个使用预定义标签来识别和分类的网络空间安全领域的NER模型
  > - 一个知识图谱构建和融合模块

- [异质信息网络在软件工程方向的应用调研](https://mp.weixin.qq.com/s/ZdSOop-I1e8WblBK9oQJjw)

  > 张中健 北邮 GAMMA Lab

  > 异质图在代码理解，软件检测，API推荐，缺陷报告检测等领域的应用。

- [SLEUTH：基于COTS审计数据的实时攻击场景重构](https://mp.weixin.qq.com/s/0zgoFUn1R3mS5m3UCOaYSg)

  > *Hossain M N(石溪大学/Stony Brook University ), Milajerdi S M(伊利诺大学芝加哥分校/University of Illinois at Chicago), Wang J(石溪大学)*
  >
  > 安全学术圈


#### 神经网络模型后门

- [FreeEagle: Detecting Complex Neural Trojans in Data-Free Cases](https://mp.weixin.qq.com/s/z29F7L-9HskdCezi-ChLAQ)

  > Chong@NESALab 安全研究GoSSIP
  >
  > 浙大神经网络后门检测

#### API安全

- [NAUTILUS: Automated RESTful API Vulnerability Detection](https://mp.weixin.qq.com/s/g_Y-fbxDiIkYCGK92o7urQ)

  > **新加坡南洋理工大学** **奇安信代码安全实验室**
  >
  > https://mp.weixin.qq.com/s/AywZm5A2v7ivxTumZnn7uQ

#### 协议安全

- [QUICforge: Client-side Request Forgery in QUlC](https://mp.weixin.qq.com/s/xW23ntLHjxLJprrwmrAGjw)

  > 柏林工业大学分布式基础设施安全实验室的 Yuri Gbur 和 Florian Tschorsch 
  >
  > 针对 QUIC（Quick UDP Internet Connection）协议发起客户端请求伪造攻击

#### 移动安全

- [Post-GDPR Threat Hunting on Android Phones: Dissecting OS-level Safeguards of User-unresettable Identifiers](https://mp.weixin.qq.com/s/2W6aMvoIQk2cru_5Lzbxdg)

  > NDSS 2023 澳大利亚昆士兰大学TrustLab 孟华松

  > 设计了一款名叫U2I2的分析工具，并对市面上最新的多款Android设备进行分析，最终发现即便用户的手机安装了最新的Android版本（10.0或更高），一些UUI（用户不可重置的识别信息——User-unresettable Identifiers）仍然可以被第三方App轻易获取。作者们在13款不同型号的Android设备上共发现了65处**系统级别（OS-level）**的UUI保护漏洞

- [Lalaine: Measuring and Characterizing Non-Compliance of Apple Privacy Labels](https://mp.weixin.qq.com/s/XeULA0DNB8l17K45xBdE6w)

  > Yue@IU 安全研究GoSSIP
  >
  > 测量和评估苹果APP隐私标签的不合规性

#### 智能充电桩

- [ChargePrint: A Framework for Internet-Scale Discovery and Security Analysis of EV Charging Management Systems](https://www.ndss-symposium.org/wp-content/uploads/2023/02/ndss2023_s84_paper.pdf)

  > NDSS2023
  >
  > 作者开发了一个名字叫做`ChargePrint`的框架，在互联网上首先去搜索EVCMS的存在。在网上找到了44个EVCMS之后，进一步分析（黑掉？）它们，然后发现了27439个在线的EVCS，同时提交（刷）了120个0-day漏洞，拿到了超过20个CVE！