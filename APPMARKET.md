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

### dddd
- **ID**: dddd
- **仓库**: SleepingBag945/dddd
- **分类**: scanning
- **平台**: windows, darwin, linux
- **语言**: Go

### httpx
- **ID**: httpx
- **仓库**: projectdiscovery/httpx
- **分类**: scanning
- **平台**: windows, darwin, linux
- **语言**: Go

### gogo
- **ID**: gogo
- **仓库**: chainreactors/gogo
- **分类**: scanning
- **平台**: windows, darwin, linux
- **语言**: Go

### spray
- **ID**: spray
- **仓库**: chainreactors/spray
- **分类**: scanning
- **平台**: windows, darwin, linux
- **语言**: Go

### ffuf
- **ID**: ffuf
- **仓库**: ffuf/ffuf
- **分类**: scanning
- **平台**: windows, darwin, linux
- **语言**: Go

### dirsearch
- **ID**: dirsearch
- **仓库**: maurosoria/dirsearch
- **分类**: scanning
- **平台**: windows, darwin, linux
- **语言**: Python

### ihoneyBakFileScan
- **ID**: ihoneybakfilescan
- **仓库**: VMsec/ihoneyBakFileScan_Modify
- **分类**: scanning
- **平台**: windows, darwin, linux
- **语言**: Python

### EHole
- **ID**: ehole
- **仓库**: EdgeSecurityTeam/EHole
- **分类**: scanning
- **平台**: windows, darwin, linux
- **语言**: Go

### cdnChecker
- **ID**: cdnchecker
- **仓库**: alwaystest18/cdnChecker
- **分类**: scanning
- **平台**: windows, darwin, linux
- **语言**: Go

### xray
- **ID**: xray
- **仓库**: chaitin/xray
- **分类**: scanning
- **平台**: windows, darwin, linux
- **语言**: Go

### kscan
- **ID**: kscan
- **仓库**: lcvvvv/kscan
- **分类**: scanning
- **平台**: windows, darwin, linux
- **语言**: Go

---

## 漏洞利用 (Exploitation)

### Apt_t00ls
- **ID**: apt_t00ls
- **仓库**: White-hua/Apt_t00ls
- **分类**: exploitation
- **平台**: windows
- **语言**: Java

### Hyacinth
- **ID**: hyacinth
- **仓库**: pureqh/Hyacinth
- **分类**: exploitation
- **平台**: windows, darwin, linux
- **语言**: Java

### I-Wanna-Get-All
- **ID**: iwannagetall
- **仓库**: R4gd0ll/I-Wanna-Get-All
- **分类**: exploitation
- **平台**: windows, darwin, linux
- **语言**: Python

### YYBaby-Spring_Scan
- **ID**: yybaby
- **仓库**: CllmsyK/YYBaby-Spring_Scan
- **分类**: exploitation
- **平台**: windows, darwin, linux
- **语言**: Java

### NacosExploit
- **ID**: nacosexploit
- **仓库**: h0ny/NacosExploit
- **分类**: exploitation
- **平台**: windows, darwin, linux
- **语言**: Java

### WeblogicTool
- **ID**: weblogictool
- **仓库**: KimJun1010/WeblogicTool
- **分类**: exploitation
- **平台**: windows, darwin, linux
- **语言**: Java

### jeecg-
- **ID**: jeecg
- **仓库**: MInggongK/jeecg-
- **分类**: exploitation
- **平台**: windows, darwin, linux
- **语言**: Java

### xxl-job-attack
- **ID**: xxljobattack
- **仓库**: pureqh/xxl-job-attack
- **分类**: exploitation
- **平台**: windows, darwin, linux
- **语言**: Go

### ShiroAttack2
- **ID**: shiroattack2
- **仓库**: SummerSec/ShiroAttack2
- **分类**: exploitation
- **平台**: windows, darwin, linux
- **语言**: Java

### ShiroEXP
- **ID**: shiroexp
- **仓库**: Y5neKO/ShiroEXP
- **分类**: exploitation
- **平台**: windows, darwin, linux
- **语言**: Java

### Frchannel
- **ID**: frchannel
- **仓库**: 7wkajk/Frchannel
- **分类**: exploitation
- **平台**: windows, darwin, linux
- **语言**: Go

### ActiveMQ-RCE-Exploit
- **ID**: activemqrce
- **仓库**: Arlenhiack/ActiveMQ-RCE-Exploit
- **分类**: exploitation
- **平台**: windows, darwin, linux
- **语言**: Python

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

### Struts2VulsScanTools
- **ID**: struts2
- **仓库**: abc123info/Struts2VulsScanTools
- **分类**: exploitation
- **平台**: windows
- **语言**: .NET

---

## Webshell 管理 (Webshell)

### Godzilla
- **ID**: godzilla
- **仓库**: BeichenDream/Godzilla
- **分类**: webshell
- **平台**: windows, darwin, linux
- **语言**: Java

### Z-Godzilla_ekp
- **ID**: zgodzilla
- **仓库**: ekkoo-z/Z-Godzilla_ekp
- **分类**: webshell
- **平台**: windows, darwin, linux
- **语言**: Java

### Behinder
- **ID**: behinder
- **仓库**: rebeyond/Behinder
- **分类**: webshell
- **平台**: windows, darwin, linux
- **语言**: Java

### skyscorpion
- **ID**: skyscorpion
- **仓库**: shack2/skyscorpion
- **分类**: webshell
- **平台**: windows, darwin, linux
- **语言**: Java

### antSword
- **ID**: antsword
- **仓库**: AntSwordProject/antSword
- **分类**: webshell
- **平台**: windows, darwin, linux
- **语言**: JavaScript

---

## 后渗透 (Post-Exploitation)

### java-memshell-generator
- **ID**: javamemshell
- **仓库**: pen4uin/java-memshell-generator
- **分类**: post-exploitation
- **平台**: windows, darwin, linux
- **语言**: Java

### VcenterKiller
- **ID**: vcenterkiller
- **仓库**: Schira4396/VcenterKiller
- **分类**: post-exploitation
- **平台**: windows, darwin, linux
- **语言**: Go

### MDUT
- **ID**: mdut
- **仓库**: SafeGroceryStore/MDUT
- **分类**: post-exploitation
- **平台**: windows, darwin, linux
- **语言**: Java

### JDumpSpider
- **ID**: jdumpspider
- **仓库**: whwlsfb/JDumpSpider
- **分类**: post-exploitation
- **平台**: windows, darwin, linux
- **语言**: Java

### Hikvision
- **ID**: hikvision
- **仓库**: wafinfo/Hikvision
- **分类**: post-exploitation
- **平台**: windows, darwin, linux
- **语言**: Python

### DockerApiRCE
- **ID**: dockerapirce
- **仓库**: 0xchang/DockerApiRCE
- **分类**: post-exploitation
- **平台**: windows, darwin, linux
- **语言**: Python

### JNDI-Inject-Exploit
- **ID**: jndiexploit
- **仓库**: exp1orer/JNDI-Inject-Exploit
- **分类**: post-exploitation
- **平台**: windows, darwin, linux
- **语言**: Java

---

## 代理工具 (Proxy)

### suo5
- **ID**: suo5
- **仓库**: zema1/suo5
- **分类**: proxy
- **平台**: windows, darwin, linux
- **语言**: Go

---

## 贡献指南

欢迎通过 Pull Request 添加新工具！请确保：

1. 工具是开源的安全测试工具
2. 有明确的 GitHub Release 版本
3. 按照上述格式添加工具信息
4. 工具 ID 使用小写字母和数字，不含特殊字符
