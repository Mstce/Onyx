# Onyx 应用市场

本文档定义了 Onyx 应用市场中可用的安全工具列表。

## 格式说明

每个工具使用以下格式定义：

```
### [工具名称]
- **ID**: 唯一标识符
- **仓库**: GitHub 仓库地址（owner/repo）
- **分类**: scanning | exploitation | webshell | post-exploitation | proxy
- **平台**: windows, darwin, linux（逗号分隔）
- **语言**: Go, Java, Python, .NET, JavaScript 等
```

---

## 扫描工具 (Scanning)

### fscan

- **ID**: fscan
- **仓库**: shadow1ng/fscan
- **分类**: scanning
- **平台**: windows, darwin, linux
- **语言**: Go
- **描述**: 一款内网综合扫描工具，方便一键自动化、全方位漏扫扫描。

### dddd

- **ID**: dddd
- **仓库**: SleepingBag945/dddd
- **分类**: scanning
- **平台**: windows, darwin, linux
- **语言**: Go
- **描述**: dddd是一款使用简单的批量信息收集,供应链漏洞探测工具，旨在优化红队工作流，减少伤肝的机械性操作。支持从Hunter、Fofa批量拉取目标

### httpx

- **ID**: httpx
- **仓库**: projectdiscovery/httpx
- **分类**: scanning
- **平台**: windows, darwin, linux
- **语言**: Go
- **描述**: httpx is a fast and multi-purpose HTTP toolkit that allows running multiple probes using the retryablehttp library.

### gogo

- **ID**: gogo
- **仓库**: chainreactors/gogo
- **分类**: scanning
- **平台**: windows, darwin, linux
- **语言**: Go
- **描述**: 面向红队的, 高性能高度自由可拓展的自动化扫描引擎 | A highly controllable and extensionable automated scanning engine for red teams

### spray

- **ID**: spray
- **仓库**: chainreactors/spray
- **分类**: scanning
- **平台**: windows, darwin, linux
- **语言**: Go
- **描述**: 最好用最智能最可控的目录Fuzz工具 | The most powerful, user-friendly, intelligent, and precise HTTP Fuzzer.

### ffuf

- **ID**: ffuf
- **仓库**: ffuf/ffuf
- **分类**: scanning
- **平台**: windows, darwin, linux
- **语言**: Go
- **描述**: Fast web fuzzer written in Go

### dirsearch

- **ID**: dirsearch
- **仓库**: maurosoria/dirsearch
- **分类**: scanning
- **平台**: windows, darwin, linux
- **语言**: Python
- **描述**: Web path scanner

### ihoneyBakFileScan

- **ID**: ihoneybakfilescan
- **仓库**: VMsec/ihoneyBakFileScan_Modify
- **分类**: scanning
- **平台**: windows, darwin, linux
- **语言**: Python
- **描述**: 批量网站备份文件扫描器，增加文件规则，优化内存占用

### EHole

- **ID**: ehole
- **仓库**: EdgeSecurityTeam/EHole
- **分类**: scanning
- **平台**: windows, darwin, linux
- **语言**: Go
- **描述**: EHole(棱洞)3.0 重构版-红队重点攻击系统指纹探测工具

### cdnChecker

- **ID**: cdnchecker
- **仓库**: alwaystest18/cdnChecker
- **分类**: scanning
- **平台**: windows, darwin, linux
- **语言**: Go
- **描述**: A tool to detect CDN for given domains

### xray

- **ID**: xray
- **仓库**: chaitin/xray
- **分类**: scanning
- **平台**: windows, darwin, linux
- **语言**: Go
- **描述**: 一款长亭自研的完善的安全评估工具，支持常见 web 安全问题扫描和自定义 poc | 使用之前务必先阅读文档

### kscan

- **ID**: kscan
- **仓库**: lcvvvv/kscan
- **分类**: scanning
- **平台**: windows, darwin, linux
- **语言**: Go
- **描述**: Kscan是一款纯go开发的全方位扫描器，具备端口扫描、协议检测、指纹识别，暴力破解等功能。支持协议1200+，协议指纹10000+，应用指纹20000+，暴力破解协议10余种。

---

## 漏洞利用 (Exploitation)

### Apt_t00ls

- **ID**: apt_t00ls
- **仓库**: White-hua/Apt_t00ls
- **分类**: exploitation
- **平台**: windows
- **语言**: Java
- **描述**: 高危漏洞利用工具

### Hyacinth

- **ID**: hyacinth
- **仓库**: pureqh/Hyacinth
- **分类**: exploitation
- **平台**: windows, darwin, linux
- **语言**: Java
- **描述**: 一款java漏洞集合工具

### I-Wanna-Get-All

- **ID**: iwannagetall
- **仓库**: R4gd0ll/I-Wanna-Get-All
- **分类**: exploitation
- **平台**: windows, darwin, linux
- **语言**: Python
- **描述**: 综合漏洞后渗透利用工具

### YYBaby-Spring_Scan

- **ID**: yybaby
- **仓库**: CllmsyK/YYBaby-Spring_Scan
- **分类**: exploitation
- **平台**: windows, darwin, linux
- **语言**: Java
- **描述**: 一款针对Spring框架的漏洞扫描及漏洞利用图形化工具

### NacosExploit

- **ID**: nacosexploit
- **仓库**: h0ny/NacosExploit
- **分类**: exploitation
- **平台**: windows, darwin, linux
- **语言**: Java
- **描述**: Nacos 综合漏洞利用工具

### WeblogicTool

- **ID**: weblogictool
- **仓库**: KimJun1010/WeblogicTool
- **分类**: exploitation
- **平台**: windows, darwin, linux
- **语言**: Java
- **描述**: WeblogicTool，GUI漏洞利用工具，支持漏洞检测、命令执行、内存马注入、密码解密等（深信服深蓝实验室天威战队强力驱动）

### jeecg-

- **ID**: jeecg
- **仓库**: MInggongK/jeecg-
- **分类**: exploitation
- **平台**: windows, darwin, linux
- **语言**: Java
- **描述**: jeecg综合漏洞利用工具

### xxl-job-attack

- **ID**: xxljobattack
- **仓库**: pureqh/xxl-job-attack
- **分类**: exploitation
- **平台**: windows, darwin, linux
- **语言**: Go
- **描述**: xxl-job漏洞综合利用工具

### ShiroAttack2

- **ID**: shiroattack2
- **仓库**: SummerSec/ShiroAttack2
- **分类**: exploitation
- **平台**: windows, darwin, linux
- **语言**: Java
- **描述**: shiro反序列化漏洞综合利用,包含（回显执行命令/注入内存马）修复原版中NoCC的问题 https://github.com/j1anFen/shiro_attack

### ShiroEXP

- **ID**: shiroexp
- **仓库**: Y5neKO/ShiroEXP
- **分类**: exploitation
- **平台**: windows, darwin, linux
- **语言**: Java
- **描述**: Shiro漏洞利用工具

### Frchannel

- **ID**: frchannel
- **仓库**: 7wkajk/Frchannel
- **分类**: exploitation
- **平台**: windows, darwin, linux
- **语言**: Go
- **描述**: 帆软bi反序列化漏洞利用工具

### ActiveMQ-RCE-Exploit

- **ID**: activemqrce
- **仓库**: Arlenhiack/ActiveMQ-RCE-Exploit
- **分类**: exploitation
- **平台**: windows, darwin, linux
- **语言**: Python
- **描述**: ActiveMQ RCE (CVE-2023-46604) 回显利用工具

### cf

- **ID**: cf
- **仓库**: teamssix/cf
- **分类**: exploitation
- **平台**: windows, darwin, linux
- **语言**: Go

### ThinkphpGUI

- **ID**: thinkphpgui
- **仓库**: Lotus6/ThinkphpGUI
- **分类**: exploitation
- **平台**: windows, darwin, linux
- **语言**: Java
- **描述**: Thinkphp(GUI)漏洞利用工具，支持各版本TP漏洞检测，命令执行，getshell。

### Struts2VulsScanTools

- **ID**: struts2
- **仓库**: abc123info/Struts2VulsScanTools
- **分类**: exploitation
- **平台**: windows
- **语言**: .NET
- **描述**: 1、点击“检测漏洞”，会自动检测该URL是否存在S2-001、S2-005、S2-009、S2-013、S2-016、S2-019、S2-020/021、S2-032、S2-037、DevMode、S2-045/046、S2-052、S2-048、S2-053、S2-057、S2-061、S2相关log4j2十余种漏洞。  2、“批量验证”，（为防止批量geshell，此功能已经删除，并不再开发）。  3、S2-020、S2-021仅提供漏洞扫描功能，因漏洞利用exp很大几率造成网站访问异常，本程序暂不提供。  4、对于需要登录的页面，请勾选“设置全局Cookie值”，并填好相应的Cookie，程序每次发包都会带上Cookie。  5、作者对不同的struts2漏洞测试语句做了大量修改，执行

---

## Webshell 管理 (Webshell)

### Godzilla

- **ID**: godzilla
- **仓库**: BeichenDream/Godzilla
- **分类**: webshell
- **平台**: windows, darwin, linux
- **语言**: Java
- **描述**: 哥斯拉

### Z-Godzilla_ekp

- **ID**: zgodzilla
- **仓库**: ekkoo-z/Z-Godzilla_ekp
- **分类**: webshell
- **平台**: windows, darwin, linux
- **语言**: Java
- **描述**: 哥斯拉webshell管理工具二次开发规避流量检测设备

### Behinder

- **ID**: behinder
- **仓库**: rebeyond/Behinder
- **分类**: webshell
- **平台**: windows, darwin, linux
- **语言**: Java
- **描述**: “冰蝎”动态二进制加密网站管理客户端

### skyscorpion

- **ID**: skyscorpion
- **仓库**: shack2/skyscorpion
- **分类**: webshell
- **平台**: windows, darwin, linux
- **语言**: Java
- **描述**: 新版将不再对外公开发布。天蝎权限管理工具采用Java平台的JavaFX技术开发的桌面客户端，支持跨平台运行，目前基于JDK1.8开发，运行必须安装JDK或JRE 1.8，注意不能是open jdk，只能是oracle的jdk。 天蝎权限管理工具基于冰蝎加密流量进行WebShell通信管理的原理，目前实现了jsp、aspx、php、asp端的常用操作功能，在原基础上，优化了大文件上传下载、Socket代理的问题，修改了部分API接口代码。

### antSword

- **ID**: antsword
- **仓库**: AntSwordProject/antSword
- **分类**: webshell
- **平台**: windows, darwin, linux
- **语言**: JavaScript
- **描述**: 中国蚁剑是一款跨平台的开源网站管理工具。AntSword is a cross-platform website management toolkit.

---

## 后渗透 (Post-Exploitation)

### java-memshell-generator

- **ID**: javamemshell
- **仓库**: pen4uin/java-memshell-generator
- **分类**: post-exploitation
- **平台**: windows, darwin, linux
- **语言**: Java
- **描述**: 一款支持自定义的 Java 内存马生成工具｜A customizable Java in-memory webshell generation tool.

### VcenterKiller

- **ID**: vcenterkiller
- **仓库**: Schira4396/VcenterKiller
- **分类**: post-exploitation
- **平台**: windows, darwin, linux
- **语言**: Go
- **描述**: 一款针对Vcenter的综合利用工具，包含目前最主流的CVE-2021-21972、CVE-2021-21985以及CVE-2021-22005、One Access的CVE-2022-22954、CVE-2022-22972/31656以及log4j，提供一键上传webshell，命令执行或者上传公钥使用SSH免密连接

### MDUT

- **ID**: mdut
- **仓库**: SafeGroceryStore/MDUT
- **分类**: post-exploitation
- **平台**: windows, darwin, linux
- **语言**: Java
- **描述**: MDUT - Multiple Database Utilization Tools

### JDumpSpider

- **ID**: jdumpspider
- **仓库**: whwlsfb/JDumpSpider
- **分类**: post-exploitation
- **平台**: windows, darwin, linux
- **语言**: Java
- **描述**: HeapDump敏感信息提取工具

### Hikvision

- **ID**: hikvision
- **仓库**: wafinfo/Hikvision
- **分类**: post-exploitation
- **平台**: windows, darwin, linux
- **语言**: Python
- **描述**: 海康威视综合安防平台后渗透利用工具

### DockerApiRCE

- **ID**: dockerapirce
- **仓库**: 0xchang/DockerApiRCE
- **分类**: post-exploitation
- **平台**: windows, darwin, linux
- **语言**: Python
- **描述**: DockerApiRCE

### JNDI-Inject-Exploit

- **ID**: jndiexploit
- **仓库**: exp1orer/JNDI-Inject-Exploit
- **分类**: post-exploitation
- **平台**: windows, darwin, linux
- **语言**: Java
- **描述**: 解决FastJson、Jackson、Log4j2、原生JNDI注入漏洞的高版本JDKBypass利用，探测本地可用反序列化gadget达到命令执行、回显命令执行、内存马注入

---

## 代理工具 (Proxy)

### suo5

- **ID**: suo5
- **仓库**: zema1/suo5
- **分类**: proxy
- **平台**: windows, darwin, linux
- **语言**: Go
- **描述**: 高性能 HTTP 正向代理工具 | A high-performance http tunneling tool

---

## 贡献指南

欢迎通过 Pull Request 添加新工具！请确保：

1. 工具是开源的安全测试工具
2. 有明确的 GitHub Release 版本
3. 按照上述格式添加工具信息
4. 工具 ID 使用小写字母和数字，不含特殊字符
