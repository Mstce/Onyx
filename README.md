简体中文 | [English](README.md)

# Onyx - 安全测试工具集

![Onyx](https://socialify.git.ci/Mstce/Onyx/image?custom_description=%E5%A4%9A%E5%8A%9F%E8%83%BD%E5%AE%89%E5%85%A8%E6%B5%8B%E8%AF%95%E5%B7%A5%E5%85%B7&custom_language=Go&description=1&forks=1&issues=1&language=1&name=1&owner=1&pulls=1&stargazers=1&theme=Light)

**一款基于 Wails v2 + Vue 3 的跨平台安全测试桌面应用**

[![Go Version](https://img.shields.io/badge/Go-1.22+-00ADD8?logo=go)](https://golang.org/)
[![Vue Version](https://img.shields.io/badge/Vue-3.5+-4FC08D?logo=vue.js)](https://vuejs.org/)
[![Wails](https://img.shields.io/badge/Wails-v2.0-60A5FA?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iI2ZmZiIgZD0iTTIyIDJIMmExIDEgMCAwIDAtMSAxdjE2YTEgMSAwIDAgMCAxIDFoMjBhMSAxIDAgMCAwIDEtMVYzYTEgMSAwIDAgMC0xLTF6bS0xIDE1SDNWN2gxOHYxMHpNNiAxMGg0djJINnYtMnptOCAwaDR2MmgtMnYtMnoiLz48L3N2Zz4=)](https://wails.io/)
[![Version](https://img.shields.io/badge/version-1.1.3-brightgreen.svg)](https://github.com/Mstce/Onyx/releases)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg)](https://github.com/Mstce/Onyx/releases)

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

## 功能

### 快速启动工具箱

渗透测试工具快速启动

<img width="1616" height="998" alt="image" src="https://github.com/user-attachments/assets/b7bd56ff-2b5b-4c0f-8dd1-d6851a36688d" />


### 空间测绘

支持多种网络空间测绘引擎

<img src="images/image-20260112133014894.png" alt="image-20260112133014894" style="zoom:33%;" />

### 漏洞扫描

- **Nuclei** - POC兼容Nuclei模板格式
- **POC 编辑器** - Monaco 编辑器，支持语法高亮
- **请求重放** - 支持自定义 HTTP 请求

**漏洞管理：**

<img src="images/image-20260112133152139.png" alt="image-20260112133152139" style="zoom: 33%;" />

**自定义POC：**

<img src="images/image-20260112133404924.png" alt="image-20260112133404924" style="zoom:33%;" />

#### 请求重放

- 自定义 HTTP 请求
- 支持各种请求方法
- 实时查看请求和响应

#### 示例

<img src="images/image-20260112134831768.png" alt="image-20260112134831768" style="zoom:33%;" />

<img src="images/image-20260112134915011.png" alt="image-20260112134915011" style="zoom:33%;" />

### 信息搜集

- 通过域名查询相关企业信息

- 股权结构分析

- 资产收集与关联分析

<img width="1616" height="998" alt="image" src="https://github.com/user-attachments/assets/30a7c81e-544b-4a72-8b22-50ad68397d90" />


### 攻防赋能

#### FScan 结果处理

自动解析和格式化 FScan 扫描结果

<img width="1616" height="998" alt="image" src="https://github.com/user-attachments/assets/ff6cb2b5-fb63-4d50-a0ba-0ecae757c272" />


#### 快速截图

结果批量截图
<img width="1616" height="998" alt="image" src="https://github.com/user-attachments/assets/d2e15627-95bd-45db-a276-96972aa4bce8" />



#### 示例

<img src="images/image-20260112140401729.png" alt="image-20260112140401729" style="zoom:33%;" />

### 泄漏利用

#### 微信利用

支持公众号、小程序、企业微信的 AK、SK 利用

<img width="1623" height="998" alt="image" src="https://github.com/user-attachments/assets/e15cdb5f-b3a5-45be-8f97-a25883d30bca" />


#### 钉钉利用

支持标准钉钉、专属钉钉利用

<img src="images/image-20260112140738119.png" alt="image-20260112140738119" style="zoom:33%;" />

#### 常见资产密文加解密

渗透测试常见高危资产密文加解密

<img src="images/image-20260112141508645.png" alt="image-20260112141508645" style="zoom:33%;" />

### 微信小程序

- **自动扫描** - 自动扫描微信小程序
- **小程序反编译** - 微信小程序反编译与代码分析
- **小程序敏感信息搜集** - 自动提取小程序中的敏感信息
- **自定义正则表达式** - 支持自定义正则表达式进行信息匹配

<img src="images/image-20260112141431981.png" alt="image-20260112141431981" style="zoom:33%;" />

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

| 平台    | 格式                 |
| ------- | -------------------- |
| Windows | `.exe` / `.msi`      |
| macOS   | `.dmg` / `.app`      |
| Linux   | `.AppImage` / `.deb` |

## 免责声明

**重要提示：本工具仅供安全研究和授权测试使用。**

1. **授权要求** - 使用本工具前，必须获得目标系统所有者的明确授权
2. **法律责任** - 未经授权使用本工具进行测试可能违反《网络安全法》等相关法律法规
3. **使用风险** - 使用本工具产生的一切后果由使用者自行承担，作者不承担任何责任
4. **教育目的** - 本工具旨在帮助安全研究人员提升技能，加强网络安全防护

**请确保在合法合规的前提下使用本工具！**

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Mstce/Onyx&type=Date)](https://star-history.com/#Mstce/Onyx&Date)

