# Security Knowledge



- **论文推荐**
  - **移动安全**

- **应急响应**
- **云安全**
- **Tips**
- **工具**
  - **代理**
  - **代码审计工具**
  - **漏洞利用工具**
- **攻防技术**
- **工控安全**
- **漏洞挖掘**
- **实战测试**
  - **外网突破**
  - **内网渗透**
  - **外网加内网**
  - **靶场/CTF WP**

- **漏洞分析**
- **恶意木马分析**
- **总结展望**



### 论文推荐

- [What Your Firmware Tells You Is Not How You Should Emulate It: A Specification-Guided Approach for Firmware Emulation](https://mp.weixin.qq.com/s/gWnvQZlgrkQklDrNI2EQwg)

  > CCS 2022 华中科技大学  周威
  >
  > 安全研究GoSSIP阅读推荐 2022-12-29

  > 从设备手册中的自然语言描述语句中提取出条件动作规则，构建外设交互状态机，进行物联网固件仿真。

- [坏字符：难以察觉的NLP攻击](https://mp.weixin.qq.com/s/yFPQ33aNZrzV4045WPdH2Q)

  > IEEE S&P 2022 剑桥大学
  >
  >  NISL实验室

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

  #### 移动安全（Mobile security）

- [Post-GDPR Threat Hunting on Android Phones: Dissecting OS-level Safeguards of User-unresettable Identifiers](https://mp.weixin.qq.com/s/2W6aMvoIQk2cru_5Lzbxdg)

  > NDSS 2023 澳大利亚昆士兰大学TrustLab 孟华松

  > 设计了一款名叫U2I2的分析工具，并对市面上最新的多款Android设备进行分析，最终发现即便用户的手机安装了最新的Android版本（10.0或更高），一些UUI（用户不可重置的识别信息——User-unresettable Identifiers）仍然可以被第三方App轻易获取。作者们在13款不同型号的Android设备上共发现了65处**系统级别（OS-level）**的UUI保护漏洞

### 应急响应

- [TeamTNT挖矿木马应急溯源分析](https://mp.weixin.qq.com/s/A1X3Kf_TNFsSVTLCm58KMQ)

  > Zgao

  > redis未授权访问漏洞挖矿应急

- [最实用的应急响应笔记思路小结](http://www.kxsy.work/2021/10/13/zui-shi-yong-de-ying-ji-xiang-ying-bi-ji-si-lu-xiao-jie/)

  > 告白

### 云安全

- [K8s组件和架构](https://mp.weixin.qq.com/s/xcXiTwzx9tRkpndARiMKuQ)

  > 谢公子

- [云原生安全系列（二）| 利用K8s污点容忍度横向移动主节点](https://mp.weixin.qq.com/s/OC88N93BopEdiJqe_ttcqQ)

  > 湛卢实验室

- [2022年Kubernetes主要漏洞汇总](https://www.cncf.io/blog/2023/01/04/2022-kubernetes-vulnerabilities-main-takeaways/)

  > https://www.cncf.io/

- [Azure利用CBA证书身份验证实现无密码持久化和特权提升](https://posts.specterops.io/passwordless-persistence-and-privilege-escalation-in-azure-98a01310be3f)

### Tips

- [GIT与GFW](https://mp.weixin.qq.com/s/3QUpvrzxb_aMv91Rq-5WOw)

  > 沈沉舟

  > 解决git连接github网络不稳定问题。

### 工具

#### 代理

- [无环境依赖开箱即用的代理IP池](https://github.com/pingc0y/go_proxy_pool)

  > pingc0y

- [分享几个攻击队用的代理方案](https://daidaitiehanhan.github.io/2022/08/26/%E5%88%86%E4%BA%AB%E5%87%A0%E4%B8%AA%E6%94%BB%E5%87%BB%E9%98%9F%E7%94%A8%E7%9A%84%E4%BB%A3%E7%90%86%E6%96%B9%E6%A1%88/)

  > [tiehanhan](https://daidaitiehanhan.github.io/)

#### 代码审计工具

- [TABBY：一款针对Java语言的静态代码分析工具](https://github.com/wh1t3p1g/tabby)

  > wh1t3p1g(NeSE)
  >
  > 利用代码属性图进行Java反序列化利用链挖掘

#### 杂

- [DROPS：攻击命令生成工具](https://sygnialabs.github.io/DROPS/)

- [Godzilla Payload的简单分析](https://mp.weixin.qq.com/s/PNFtaWdkLSwgl95fHwP4yA)

- [linux跟踪技术之ebpf](https://mp.weixin.qq.com/s/LPJZ4mg3nogeYRCNaWwQEQ)

- [Yi: 项目监控工具 以及 Codeql 自动运行](https://github.com/ZhuriLab/Yi)

  > 默安科技逐日实验室

- [多个网络资产测绘命令行查询工具](https://mp.weixin.qq.com/s/wSngRsRLF0TBlXrwhBGD5A)

  > ffffffff0x

  > fofa、quake、zoomeye、shodan、huneter、chaos

#### 漏洞利用工具

- [Ysomap：一款适配于各类实际复杂环境的Java反序列化利用框架](https://github.com/wh1t3p1g/ysomap)

  > wh1t3p1g(NeSE)
  
- [【技术原创】pypsrp在Exchange Powershell下的优化](https://mp.weixin.qq.com/s/CGp2Tdpr6WXFzlnuZbOo3g)

  > 3gstudent [嘶吼专业版](javascript:void(0);)

### 攻防技术

- [2023钓鱼攻击思路整理](https://mp.weixin.qq.com/s/mnuus-XBBK5gspAAIBeIPg)

  > Taoing

- [隐藏在SVG文件中的HTML Smuggling新利用](https://mp.weixin.qq.com/s/aSgb8uQT44I7MkjGsAQmhQ)

  > M01N Team

- [红队攻防之PC端微信个人信息与聊天记录取证](https://mp.weixin.qq.com/s/4DbXOS5jDjJzM2PN0Mp2JA)



- [实战|记录一次通过不断FUZZ从而获取万元赏金](https://mp.weixin.qq.com/s/g8oPRHCccUg-BVt_rZs3jw)

  > 网络安全之旅

  > H5站点 Fuzz测试

- [最全的内网凭据密码收集方法和技巧总结](https://mp.weixin.qq.com/s?__biz=MzI5MDU1NDk2MA==&mid=2247510123&idx=1&sn=84622c193dad6bcf2432af54beeba32e&chksm=ec1cfd54db6b74423eccc0f2af82485020e25704312040780a23b275d8943159e030a63ca867&mpshare=1&scene=1&srcid=1231Hze1SsiPCIWEsEPmx47k&sharer_sharetime=1672453566377&sharer_shareid=a93dd3cba873ae5faa92bd564afa6091&key=ae1404de8eb54f3241bc9cc3ba589ecce37ad3a0753be749313a7e540e561ef2f70826b109dc713e2d80a0028b873bcf2000c96c63aca7f2bb97cd0542939ff47bc6dc02ff1f6d41cd7da439c0cf1e5ce2a3ba261372deaf3c01abdddbef64033c4a47a2345a3a2831ca22b3fec090d5c111882d7054e3f1ddb0318c60cdd66b&ascene=1&uin=Mzk0MDc0MjYw&devicetype=Windows+11+x64&version=6308011a&lang=zh_CN&exportkey=n_ChQIAhIQWosHuqluGW1uaKHcG4A5mBLqAQIE97dBBAEAAAAAAI1xKfIM2bAAAAAOpnltbLcz9gKNyK89dVj0wlUzPmH1c0Q6W6tFZa2wpW5EZHuHdmiFsNHT%2B1YuiCyd27OcGz0A7EiO53t1LAAl5z35JPs2dYSoIJaMz9Gcgb7%2FmzS842IcmpnJ34Wa81x4DhlYMGIDv5bOBbycM%2F1Qz1o7uQ%2B5wQAqEXW%2BvwViEc0b85YkbaQTQVKHl%2BbxmvJLR983tfvKRO8hKEj6ih4DHg075i8xXO6GflzECKxg0KUox%2BW%2Be74HLwalirKrFlp0OtiIKPXjopNQKGglCRgs9GzAng%3D%3D&acctmode=0&pass_ticket=jgK8czkMhwiEq%2Fa4kiLJPo15xK6w%2F6pq8aA8YkNZUxWbQyRh7%2FszmkX%2BAbuh6KLrrHxocQmCMzuKN%2B%2F%2FkFJgqA%3D%3D&wx_header=1&fontgear=2)

  > 深蓝天威战队

  > RDP凭证、VNC、VPN、Wifi、微信聊天记录、SVN、FileZilla、Winscp、XShell、FinalShell、SecureCRT、Mobaxterm、Navicat、TeamViewer、SunLogin、ToDesk、浏览器、OA、Weblogic、Jboss。

- [持久后门：从内存中加载PHP扩展](https://adepts.of0x.cc/dlopen-from-memory-php/)

  > Adepts of 0xCC

- [实战|记一次从供应链的未授权访问到重大成果](https://mp.weixin.qq.com/s/IWJNCD9pli_JXY_6WaKgzw)

  > 弱口令安全实验室

  > js接口未授权逐步获取大量敏感信息

### 工控安全

- [MOSAICS 工业控制系统的扩展态势感知框架](https://mp.weixin.qq.com/s/0OZh4TLYK_2aoyMf8hIEPA)

  > 小强说

### 漏洞挖掘

- [越权漏洞自动化治理实践](https://mp.weixin.qq.com/s/rI5r3KdMC0StA9kU5IErzg)

  > 陌陌安全



### 实战测试

#### 外网突破

- [从发现SQL注入到ssh连接](https://mp.weixin.qq.com/s/OEHfL9gkI9HgJICtlT1tQQ)

  > 合天网安

- [实战|一次对企业内部EHR系统的渗透测试](https://mp.weixin.qq.com/s/vycsIwvNpueLGxAgVOg8Yw)

  > Icepaper
  
- [某众测黑盒0day挖掘获得奖金上限](https://forum.butian.net/share/2048)

  > 349223646
  
- [实战|绕过waf执行命令到拿下卡巴斯基管理端](https://mp.weixin.qq.com/s/AAmjA9CIXlQ03GK_l0BEZQ)

  > djhons

- [记一次对某非法站点从SQL注入到整站打包与本地搭建全过程](https://mp.weixin.qq.com/s/CvvBFltQYiXNBOz2D-E2kg)

  > GuoKer

#### 内网渗透

- [【实战】记一次攻防演练之vcenter后渗透利用](https://mp.weixin.qq.com/s/ayoI8MTkB0VYNR4R_hvBhw)

  > crow

  > 外网突破加内网域渗透

#### 外网加内网

- [老洞翻新——记录一次地级市HW的完整攻击链条](https://mp.weixin.qq.com/s/Cl5OR9DNw5aum3iXPsxvjw)

  > 听风安全



#### 靶场/CTF WP

- [[HTB] Jarvis Writeup](https://mp.weixin.qq.com/s/7eEGFMrYwfjK8ElNjvg6Lg)

  > 0x584A

- [ByteCTF2022 mobile系列](https://mp.weixin.qq.com/s/cmrx9jZkmzaInSEoT3eHZg)

  > e*16 a

### 漏洞分析

- [CVE-2020-1622](https://darkless.cn/2022/04/19/spring-rce-1/)



### 恶意木马分析

- [2022攻防演练木马专项分析报告](http://report.threatbook.cn/2022.pdf)

- [针对军工和教育行业的CNC组织“摆渡”木马分析](https://mp.weixin.qq.com/s/uEjNpw-rtpjGGPacJS19WQ)

  > 安天

### 总结展望

- [2022年安全架构总结以及2023安全方向展望](https://mp.weixin.qq.com/s/D0mETMfF4wu_a3dSXoxIiQ)

  > 鸟哥谈安全

  > 云上攻击、终端安全、应用安全、身份攻击

- [欧盟网络安全局 2022 年度威胁报告]([欧盟网络安全局 2022 年度威胁报告 (qq.com)](https://mp.weixin.qq.com/s/UDbOlnLfsD4pk_3PQCuGBw))

  > 威胁棱镜

  