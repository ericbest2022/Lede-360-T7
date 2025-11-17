# iStoreOS OpenWrt Custom Build

![iStoreOS](https://raw.githubusercontent.com/istoreos/istoreos/istoreos-banner.png)

## 📝 项目简介

iStoreOS 是基于 [https://github.com/padavanonly/immortalwrt-mt798x-6.6) 仓库的 OpenWrt 自定义构建版本，增加了科学上网，适用于路由器日常使用。

---

## ⚡ 功能特性

### 默认
- 管理ip：192.168.199.1
- 用户名和密码：root/password
- 无线wifi名称：mt_wifi
- 无线wifi密码：password

### 1️⃣ LuCI 插件
- **luci-app-passwall2**：全功能科学上网管理界面  
- **luci-app-easymesh**：支持 Mesh 网络管理  
- **主题**：默认切换为 `luci-theme-argon`  

### 2️⃣ USB 网络共享驱动
- **Android USB 共享**：支持 `rndis_host`、`cdc_ether`、`usbnet` 等驱动  
- **iOS 网络共享**：安装 `usbmuxd` + `libimobiledevice` 支持 iPhone 共享网络  

### 3️⃣ SSH/SFTP
- 替换默认 Dropbear，安装：
  - `openssh-server`
  - `openssh-sftp-server`
  - 支持标准 SSH 登录和 SFTP 文件传输  

### 4️⃣ 系统优化
- 默认主机名修改为 `360T7`  
  

---

## 🛠 构建说明

本仓库基于 [https://github.com/padavanonly/immortalwrt-mt798x-6.6) 仓库 `master` 分支构建，使用 GitHub Actions 或本地构建均可。

