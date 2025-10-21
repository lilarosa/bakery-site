# 🥖 Brain Best Bread Baking House

_A bilingual web project created under Ubuntu as part of a networking & webserver training (Apache + DHCP)_

一个在 **Ubuntu 虚拟机** 中完成的双语网页项目，用于学习 **DHCP 服务配置** 和 **Apache 网页服务器部署**。  
网页内容为“Brain Best Bread Baking House”面包店示例网站，包含首页与联系表单。

---

## 🌐 Demo / Online Preview
If you activated **GitHub Pages**, visit:  
👉 [https://lilarosa.github.io/bakery-site/](https://lilarosa.github.io/bakery-site/)  

（等待 GitHub Pages 部署 1–2 分钟即可生效）

---

## 📂 Project Structure / 项目结构

bakery-site/
├── index.html # Home page / 首页
├── contact.html # Contact form / 联系页
├── style.css # Shared stylesheet / 样式表
└── README.md # Project documentation

---

## 💡 Key Learning Topics / 学习要点

| Module | Description |
|---------|--------------|
| 🧠 DHCP | Understanding and simulating DORA (Discover → Offer → Request → Ack) |
| 🌐 Apache | Installing & configuring Apache web server on Ubuntu |
| 🧱 HTML + CSS | Creating a static bilingual web layout with responsive design |
| 🧰 Linux Commands | Using `ip a`, `systemctl`, `journalctl`, `tee`, `nano`, `curl`, `git` |
| 🔒 Network Safety | Running all services safely in NAT mode (no effect on home network) |

---

## 🧩 How to Run Locally / 本地运行方式

```bash
# Copy files into Apache web root
sudo cp index.html contact.html style.css /var/www/html/

# Restart Apache
sudo systemctl restart apache2

# Open in browser
http://localhost
🇩🇪 Projektbeschreibung (auf Deutsch)

Titel: DHCP- und Apache-Webserver unter Ubuntu
In diesem Lernprojekt wurde ein DHCP-Server sowie ein Apache-Webserver installiert, konfiguriert und getestet.
Im Anschluss wurde eine eigene zweisprachige Webseite („Brain Best Bread Baking House“) erstellt und erfolgreich im Browser über localhost aufgerufen.
Der DHCP-Server lief im NAT-Modus, um das Heimnetzwerk nicht zu beeinflussen.

📘 Author / 作者

Name: lilarosa
Training: Fachinformatiker/in – Fachrichtung Anwendungsentwicklung
Environment: Ubuntu (VirtualBox), Apache2, ISC-DHCP-Server
🏁 Status

✅ Completed on: October 2025
✅ Safe to run in NAT mode
✅ Fully working local web project ready for GitHub Pages deployment
