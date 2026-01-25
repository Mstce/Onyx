## 项目简介

**Onyx** 是一款安全测试工具集，集合多种渗透测试常用的功能和工具，赋能攻防、渗透等场景。整合空间测绘、漏洞扫描、主机探测、信息收集等能力，提供一站式的渗透测试工作台，告别需要到处切换工具、网站的麻烦。

### 

| 模块           | 说明                                                         |
| :------------- | :----------------------------------------------------------- |
| **空间测绘**   | 集成 **Fofa**、**Hunter**、**Quake** 三大测绘引擎，支持批量资产导出 |
| **漏洞扫描**   | 基于 **Nuclei** 引擎，支持 POC 管理、批量扫描、请求包可视化、一键生成验证图片 |
| **辅助工具**   | 内置 **CyberChef**、JWT 密钥爆破、编码转换、Fscan 结果处理、攻防批量截图 |
| **应用加解密** | 提供 **FinalShell**、**Navicat**、**蓝凌**、**致远**、**帆软**、**Druid**、**JBoss** 等常见应用/中间件的加解密工具 |
| **小程序分析** | 支持微信小程序自动识别、反编译 (`.wxapkg`)、敏感信息正则提取 |
| **企业信息**   | 支持 IP 归属地查询、ICP 备案信息查询、企业与股权结构分析     |
| **信息探测**   | 包含端口扫描、杀软识别、指纹识别、敏感信息采集 (JS 分析)     |

## 提示
macos打不开请运行：
sudo xattr -d com.apple.quarantine Onyx.app

## 功能

### 快速启动工具箱

渗透测试工具快速启动

<img width="1616" height="998" alt="image" src="https://github.com/user-attachments/assets/501d2f98-a7b1-4744-9689-d37145df0c2e" />



### 空间测绘

支持多种网络空间测绘引擎

<img width="1291" height="794" alt="image" src="https://github.com/user-attachments/assets/35180389-9b97-4650-8173-db867d435589" />


### 漏洞扫描

- **Nuclei** - POC兼容Nuclei模板格式
- **POC 编辑器** - Monaco 编辑器，支持语法高亮
- **请求重放** - 支持自定义 HTTP 请求

**漏洞管理：**

<img width="1293" height="795" alt="image" src="https://github.com/user-attachments/assets/b1d82867-c792-46ee-ae63-b6a2e6be8df6" />


**自定义POC：**

<img width="1295" height="795" alt="image" src="https://github.com/user-attachments/assets/f2f8ac2c-b8be-4246-b4a7-97679897d680" />
-- 支持AI助力生成POC
<img width="1291" height="799" alt="image" src="https://github.com/user-attachments/assets/70b902c4-b9d6-435b-a080-d139999baef0" />

#### 请求重放

- 自定义 HTTP 请求
- 支持各种请求方法
- 实时查看请求和响应

#### 示例

<img width="1288" height="786" alt="image" src="https://github.com/user-attachments/assets/6ed340b4-e907-4c02-85de-fae3afb40301" />

### 信息搜集

- 通过域名查询相关企业信息

- 股权结构分析

- 资产收集与关联分析

<img width="1616" height="998" alt="image" src="https://github.com/user-attachments/assets/bd9f4da5-5d21-4b15-87b8-5dd369e700dc" />



### 攻防赋能

#### FScan 结果处理

自动解析和格式化 FScan 扫描结果

<img width="1616" height="998" alt="image" src="https://github.com/user-attachments/assets/ff6cb2b5-fb63-4d50-a0ba-0ecae757c272" />


#### 快速截图

结果批量截图
<img src="images/image-20260112140401729.png" alt="image-20260112140401729" style="zoom:33%;" />

### 泄漏利用

#### 微信利用

支持公众号、小程序、企业微信的 AK、SK 利用

<img width="1623" height="998" alt="image" src="https://github.com/user-attachments/assets/e15cdb5f-b3a5-45be-8f97-a25883d30bca" />

#### 常见资产密文加解密

渗透测试常见高危资产密文加解密

<img src="images/image-20260112141508645.png" alt="image-20260112141508645" style="zoom:33%;" />

### 微信小程序

- **自动扫描** - 自动扫描微信小程序
- **小程序反编译** - 微信小程序反编译与代码分析
- **小程序敏感信息搜集** - 自动提取小程序中的敏感信息
- **自定义正则表达式** - 支持自定义正则表达式进行信息匹配

<img width="2590" height="1600" alt="image" src="https://github.com/user-attachments/assets/c062d3b9-758d-4d8c-b883-cfe9951685d6" />


## 感谢名单

感谢以下贡献者对本项目的支持：

<!-- CONTRIBUTORS:START -->

| 头像                                                         | 用户名 | 链接                                 |
| ------------------------------------------------------------ | ------ | ------------------------------------ |
| <img src="https://avatars.githubusercontent.com/Mstce" width="40" /> | Mstce  | [@Mstce](https://github.com/Mstce)   |
| <img src="https://avatars.githubusercontent.com/Y5neKO" width="40" /> | Y5neKO | [@Y5neKO](https://github.com/Y5neKO) |
| <img src="https://avatars.githubusercontent.com/In1t0" width="40" /> | In1t0  | [@In1t0](https://github.com/In1t0)   |
| <!-- CONTRIBUTORS:END -->                                    |        |                                      |

## 快速开始

访问 [Releases](https://github.com/Mstce/Onyx/releases) 下载对应平台的安装包：

## 联系信息
|  |  |
|---|---|
| <img src="https://github.com/user-attachments/assets/d0a6df13-3c0a-4001-bd8f-450c01cbeed8" width="220" /> | <img src="https://github.com/user-attachments/assets/f28392dc-c5e1-44a7-a611-2eed0fcbe621" width="220" /> |
| **关注微信公众号** | **微信** |

## 免责声明

**重要提示：本工具仅供安全研究和授权测试使用。**

1. **授权要求** - 使用本工具前，必须获得目标系统所有者的明确授权
2. **法律责任** - 未经授权使用本工具进行测试可能违反《网络安全法》等相关法律法规
3. **使用风险** - 使用本工具产生的一切后果由使用者自行承担，作者不承担任何责任
4. **教育目的** - 本工具旨在帮助安全研究人员提升技能，加强网络安全防护

**请确保在合法合规的前提下使用本工具！**

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Mstce/Onyx&type=Date)](https://star-history.com/#Mstce/Onyx&Date)

