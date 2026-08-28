# Universal Social Text Splitter

A lightweight, client-side text splitter designed to bypass character limits across social platforms without silent truncations or lost messages.

[English](#english) | [简体中文](#简体中文) | [فارسی](#فارسی)

---

## English

### Overview
A single-file HTML utility built to split long-form text for **Instagram (DM 1000 / Post 2200)**, **Twitter/X Threads (280)**, and **Discord (2000)**. 

### Key Features
* **Accurate Unicode Counting**: Correctly counts complex characters, Emojis, and Zero-Width Non-Joiners (ZWNJ).
* **Automatic Bi-Directional Layout**: Native `dir="auto"` support for Right-to-Left (RTL) scripts like Persian/Arabic and Left-to-Right (LTR) scripts like English/Chinese.
* **Safety Margin Buffer**: Customizable buffer to prevent platform-side overflow drops.
* **Zero Dependencies**: Pure HTML/CSS/JS with no build tools or external servers required.

---

## 简体中文

### 项目简介
一个轻量级纯前端单文件网页工具，专为解决 **Instagram 私信静默截断（1000 字符）**、**Instagram 帖子文案（2200 字符）**、**Twitter/X 推文串（280 字符）** 及 **Discord（2000 字符）** 的字数限制痛点而设计。

### 核心特性
* **精确 Unicode 计数**：精准识别汉字单字表意、各类 Emoji 以及波斯语特有的零宽不连字字符（ZWNJ），避免字数统计偏差。
* **原生排版自适应**：基于 `dir="auto"` 自动识别排版方向（波斯语/阿拉伯语从右至左，中英文从左至右）。
* **安全冗余保护**：支持自定义防溢出预留字符，彻底杜绝平台静默吞字。
* **单文件开箱即用**：零后端、零依赖，下载单个 HTML 文件即可在任意浏览器本地运行。

---

## فارسی

### معرفی پروژه
یک ابزار تک‌صفحه‌ای سبک و سریع برای تقسیم متن‌های طولانی در شبکه‌های اجتماعی، جهت جلوگیری از حذف خودکار پیام‌ها در **دایرکت اینستاگرام (۱۰۰۰ کاراکتر)**، **کپشن پست اینستاگرام (۲۲۰۰ کاراکتر)**، **رشته‌توییت‌های توییتر/X (۲۸۰ کاراکتر)** و **دیسکورد (۲۰۰۰ کاراکتر)**.

### ویژگی‌های کلیدی
* **شمارش دقیق کاراکترهای یونیکد**：محاسبه دقیق انواع ایموجی‌ها و نیم‌فاصله‌های پنهان (ZWNJ) در خط فارسی.
* **پشتیبانی کامل از چینش راست‌به‌چپ (RTL)**：شناسایی خودکار جهت نوشتار برای فارسی، عربی، انگلیسی و چینی.
* **حاشیه امنیت (Safety Margin)**：امکان تعیین فاصله امن برای جلوگیری از سرریز متن و خطای پلتفرم‌ها.
* **بدون نیاز به سرور**：یک فایل HTML مستقل و آماده اجرا در هر مرورگر بدون نیاز به اینترنت یا نصب ابزار اضافی.

---

## License
Distributed under the MIT License. See `LICENSE` for more information.
