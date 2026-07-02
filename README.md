<div align="center">

# 🤖 Shad Bot

### Automation Toolkit for SHAD & Rubika Web

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Selenium](https://img.shields.io/badge/Selenium-Automation-green?logo=selenium)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-orange)
![Platform](https://img.shields.io/badge/Platform-Windows-blue)
![License](https://img.shields.io/badge/License-MIT-green)

A desktop automation tool for **SHAD** and **Rubika Web** built with **Python**, **Selenium** and **Tkinter**.

---

### 🇮🇷 فارسی | 🇺🇸 English

</div>

---

# 🇮🇷 فارسی

## 📖 معرفی

Shad Bot یک نرم‌افزار دسکتاپ است که برای خودکارسازی فعالیت‌ها در نسخه وب **شاد** و **روبیکا** طراحی شده است.

این برنامه با استفاده از Selenium مرورگر Chrome را کنترل می‌کند و امکانات مختلفی برای ارسال پیام، مدیریت مخاطبین، زمان‌بندی پیام و شرکت خودکار در نظرسنجی‌ها فراهم می‌کند.

---

# ✨ امکانات

## 🔐 ورود خودکار

- ورود به حساب شاد
- ورود به حساب روبیکا
- ذخیره شماره تلفن
- استفاده از Chrome Profile

---

## 💬 ارسال پیام

- ارسال پیام به یک مخاطب
- انتخاب مخاطب از لیست
- وارد کردن متن دلخواه
- بازگشت خودکار به صفحه اصلی

---

## 👥 ارسال گروهی

ارسال یک پیام به چندین مخاطب به صورت همزمان.

کافی است نام مخاطبین را با علامت `+` از هم جدا کنید.

مثال:

```
علی+محمد+رضا
```

---

## ⏰ ارسال زمان‌بندی شده

قابلیت ارسال پیام در ساعت مشخص.

ویژگی‌ها:

- تعیین ساعت
- تعیین دقیقه
- شمارش معکوس
- ارسال خودکار

---

## 📋 مدیریت مخاطبین

- افزودن مخاطب
- حذف مخاطب
- ذخیره در فایل
- بارگذاری خودکار هنگام اجرای برنامه

---

## 🔍 وارد کردن مخاطبین

دریافت مخاطبین از نسخه وب شاد یا روبیکا و اضافه کردن آن‌ها به لیست برنامه.

---

## 🤖 ربات نظرسنجی

یکی از جذاب‌ترین قابلیت‌های پروژه.

ربات به صورت خودکار:

- چت‌های جدید را بررسی می‌کند.
- نظرسنجی‌ها را پیدا می‌کند.
- گزینه اول را انتخاب می‌کند.
- این فرآیند را تا ۳ دقیقه ادامه می‌دهد.

---

# 🖥️ رابط کاربری

رابط کاربری با استفاده از Tkinter طراحی شده است.

---

# ⚙️ پیش‌نیازها

- Python 3
- Google Chrome
- ChromeDriver
- Selenium

نصب:

```bash
pip install selenium
```

---

# 🚀 اجرا

```bash
python main.py
```

---

# 💾 فایل profile.txt

برنامه اطلاعات زیر را در این فایل ذخیره می‌کند:

- شماره تلفن
- لیست مخاطبین

---

# ⚠️ نکات

- ChromeDriver باید با نسخه Chrome هماهنگ باشد.
- برنامه فقط روی نسخه وب کار می‌کند.
- هنگام اجرای ربات نظرسنجی بهتر است از سایر بخش‌های برنامه استفاده نشود.

---

# 👨‍💻 توسعه‌دهنده

**Erfan Sadeghi**

Telegram:

**@Gamerfan82**

---

# 🇺🇸 English

## 📖 About

Shad Bot is a desktop automation tool for **SHAD Web** and **Rubika Web**.

It uses **Python**, **Selenium**, and **Tkinter** to automate common messaging tasks.

---

## ✨ Features

### 🔐 Login

- SHAD login
- Rubika login
- Phone number saving
- Chrome automation

---

### 💬 Send Message

- Send message to a single contact
- Choose contact from saved list
- Custom message support

---

### 👥 Bulk Messaging

Send the same message to multiple contacts.

Example:

```
Ali+Reza+Mohammad
```

---

### ⏰ Scheduled Messages

Schedule a message to be sent automatically.

Features:

- Hour selection
- Minute selection
- Countdown
- Automatic sending

---

### 📋 Contact Manager

- Add contacts
- Remove contacts
- Save contacts
- Load contacts automatically

---

### 🔍 Import Contacts

Import contacts directly from SHAD/Rubika Web.

---

### 🤖 Auto Survey Bot

Automatically:

- Monitors recent chats
- Detects new polls
- Selects the first option
- Runs for approximately 3 minutes

---

## 🖥 GUI

Built with **Tkinter**.

Includes:

- Login page
- Contact manager
- Message sender
- Bulk sender
- Scheduler
- Survey bot

---

## ⚙️ Requirements

- Python 3
- Google Chrome
- ChromeDriver
- Selenium

Install:

```bash
pip install selenium
```

---

## 🚀 Run

```bash
python main.py
```

---

## 📁 Project Structure

```
Shad_bot
│
├── main.py
├── chromedriver.exe
├── profile.txt
└── README.md
```

---

## 🛠 Built With

- Python
- Selenium
- Tkinter
- Threading

---

## ⚠️ Notes

- ChromeDriver version must match your Chrome version.
- Designed for SHAD Web and Rubika Web.
- Avoid using other features while the Survey Bot is running.

---

## 👨‍💻 Developer

**Erfan Sadeghi**

Telegram:

**@Gamerfan82**

---

# ⭐ If you like this project, don't forget to leave a Star!
