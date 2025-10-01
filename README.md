# 🚀 Udemy — The Complete Ethical Hacking Course

學習完整的 **Ethical Hacking（倫理駭客）** 技能，並保護我的網站。  
本專案為課程學習筆記與安裝紀錄。

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)]()  
[![Status](https://img.shields.io/badge/status-in_progress-yellow.svg)]()

---

## 📖 目錄
- [簡介](#-簡介)
- [目標](#-目標)
- [環境準備](#-環境準備)
  - [在 VirtualBox 安裝 Kali Linux](#在-virtualbox-安裝-kali-linux)
- [學習紀錄](#-學習紀錄)
- [常用命令範例](#-常用命令範例)
- [安全與倫理聲明](#-安全與倫理聲明)
- [授權](#-授權)

---

## 📌 簡介
這是一份學習 **Udemy: The Complete Ethical Hacking Course** 的紀錄，  
透過搭建虛擬環境與 Kali Linux，練習滲透測試與資安防護技巧。

---

## 🎯 目標
- 在隔離環境中學習與實作駭客工具  
- 建立測試用的 Kali Linux 環境  
- 了解常見漏洞與如何防禦  
- 紀錄課程重點與學習心得  

---

## 🛠️ 環境準備

### 在 VirtualBox 安裝 Kali Linux

1. **下載必需品**
   - [VirtualBox](https://www.virtualbox.org/)  
   - [Kali Linux ISO](https://www.kali.org/get-kali/)  

2. **建立虛擬機**
   - 名稱：`KaliLinux`  
   - 類型：`Linux` → 版本：`Debian (64-bit)`  
   - RAM：至少 2048 MB（建議 4096 MB）  
   - 硬碟：20 GB（VDI 動態分配）  

3. **設定虛擬機**
   - CPU：2 核以上  
   - 顯示：128 MB 視訊記憶體  
   - 網路：可選 NAT 或 Host-only  
   - 光碟機掛載 Kali ISO  

4. **安裝 Kali**
   - 選擇 `Graphical Install`  
   - 設定語言、時區、使用者  
   - 完成安裝並重新開機  

5. **更新與安裝常用工具**
   ```bash
   sudo apt update && sudo apt full-upgrade -y
   sudo apt install -y net-tools curl wget vim
