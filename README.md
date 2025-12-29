# 🔐 SSL Pinning Bypass — Messenger App

This repository demonstrates how SSL/TLS **certificate pinning** works in the Messenger Android app, along with a **practical example** of bypass techniques and HTTPS traffic capture.

---

## 🎥 Demo Video

▶️ [Watch the demonstration](https://github.com/user-attachments/assets/d9069639-2a13-48c2-acc8-74a897930bf8)

---

## ⚙️ Supported Architectures
- **arm64-v8a**
- **x86_64**
---
## Messenger App Version 
- **537.0.0.52.109**
---

## 📱 Mobile Device Requirements
- Android device (**Rooted** or **Non-Rooted**)
- One of the following traffic interception tools:
  - [Proxypin](https://proxypin.com)
  - [Reqable](https://reqable.com)

---

## 💻 Emulator Setup
- Windows PC with:
  - **Reqable**, **Burp Suite**, or **Mitmproxy** installed
  - **Nox** or **LDPlayer** Android emulator
  - **Root access** enabled in the emulator

---

## 🚀 Bypass Procedure

1. Replace patched `libcoldstart.so with /data/data/com.facebook.orca/lib-compressed/libcoldstart.so`
2. Replace the patched library file:
   ```bash
   adb push D:\patched\libcoldstart.so /data/data/com.facebook.orca/lib-compressed/libcoldstart.so

3. Use Proxypin / Reqable / Burp Suite / Mitmproxy for capturing traffics.

## For latest patched libcoldstart.so contract with me.
<a href="https://t.me/MUH4MM4DSH4KIB" target="_blank">
  <img src="https://img.shields.io/badge/💬_Chat_on_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&labelColor=121212&color=26A5E4&logoWidth=20" alt="Telegram" style="border-radius: 8px;"/>
</a>
