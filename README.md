<div align="center">

# 🌌 Link Share Bot ✨

<img src="https://4kwallpapers.com/images/walls/thumbs_2t/26545.png" width="100%" alt="Banner">

<br>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=30&pause=1000&color=00E6FF&center=true&vCenter=true&width=900&lines=🚀+Welcome+to+Link+Share+Bot;🔗+Share+Unlimited+Telegram+Links;⚡+Powered+by+Pyrogram+%2B+MongoDB;🛡️+Secure+%7C+Fast+%7C+Reliable;💎+Premium+Telegram+Link+Management;❤️+Crafted+with+Passion+by+Shivam" />

<br><br>

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Pyrogram](https://img.shields.io/badge/Pyrogram-Latest-6C63FF?style=for-the-badge)
![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-13AA52?style=for-the-badge\&logo=mongodb)
![Telegram](https://img.shields.io/badge/Telegram-Bot-229ED9?style=for-the-badge\&logo=telegram)
![Maintained](https://img.shields.io/badge/Maintained-Yes-success?style=for-the-badge)

<img src="https://user-images.githubusercontent.com/74038190/212257465-7dfc6794-47f2-40d5-8f1b-f0d5d8a84e3d.gif" width="100%">

</div>

---

# 🌟 About

**Link Share Bot** is a next-generation Telegram bot built to simplify channel invitation management.

Whether you're managing one channel or hundreds, it helps generate secure invite links, automate requests, enforce subscriptions, and streamline administration.

## ✨ Core Capabilities

* 📺 Unlimited Telegram channel support
* 🔗 Automatic invite link generation
* ⏳ Auto-expiring links
* 📦 Bulk link creation
* 🔄 Join request management
* 🛡️ Force subscription system
* 📊 Detailed statistics
* 👑 Powerful admin controls
* ⚡ High-speed MongoDB storage

---

# 🎯 Feature Showcase

| 🚀 Feature            | 💎 Benefit                       |
| --------------------- | -------------------------------- |
| 🔗 Smart Invite Links | Secure links generated instantly |
| 📺 Unlimited Channels | Scale without restrictions       |
| 📋 Pagination         | Easy browsing of large datasets  |
| 📦 Bulk Generation    | Save time with mass operations   |
| 🛡️ Force Subscribe   | Protect premium communities      |
| 🔄 Join Requests      | Built-in request workflow        |
| ⏱️ Auto Expiration    | Temporary secure invites         |
| 📊 Analytics          | Monitor users and usage          |

---

# 🖼️ Anime Inspired Theme

<div align="center">

<img src="https://4kwallpapers.com/images/walls/thumbs_2t/26448.png" width="32%">
<img src="https://4kwallpapers.com/images/walls/thumbs_2t/26290.jpg" width="32%">
<img src="https://4kwallpapers.com/images/walls/thumbs_2t/26082.jpg" width="32%">

</div>

---

# ⚙️ Commands

## 📂 Channel Management

```text
/addch <channel_id>
/delch <channel_id>
/channels
/reqlink
/links
/bulklink <id1> <id2> ...
/reqtime
/reqmode
/approveon
/approveoff
/approveall
```

## 👑 Administration

```text
/stats
/status
/broadcast
/cleanup
```

---

# 🔑 Environment Variables

```env
API_ID=
API_HASH=
TG_BOT_TOKEN=
OWNER_ID=
ADMINS=
DB_URL=
DB_NAME=LinkShareBot
DATABASE_CHANNEL=
```

> ⚠️ Never commit secrets or credentials to a public repository.

---

# ☁️ VPS Deployment

```bash
sudo apt update && sudo apt upgrade -y

sudo apt install -y git python3-pip python3-venv ffmpeg tmux

git clone https://github.com/animedubber46-lgtm/LinkShareBot

cd LinkShareBot

python3 -m venv venv

source venv/bin/activate

pip install -U pip

pip install -r requirements.txt

nano .env

python3 main.py
```

---

# 🐳 Docker

```bash
git clone https://github.com/animedubber46-lgtm/LinkShareBot

cd LinkShareBot

docker build -t linksharebot .

docker run -d \
--name linksharebot \
--restart unless-stopped \
--env-file .env \
linksharebot
```

---

# 🌐 Quick Deploy

| Platform              | Status      |
| --------------------- | ----------- |
| 🚂 Railway            | ✅ Supported |
| 🐳 Docker             | ✅ Supported |
| ☁️ VPS                | ✅ Supported |
| 🌍 Heroku-style Hosts | ✅ Supported |

---

# 📈 Architecture

```text
User
   │
   ▼
Telegram Bot
   │
   ▼
Pyrogram Engine
   │
   ├────────► MongoDB
   │
   ├────────► Invite Link Generator
   │
   ├────────► Force Subscribe
   │
   └────────► Request Approval System
```

---

# 💬 Community

* 👨‍💻 Developer: **Shivam**
* 🐙 GitHub: **animedubber46-lgtm**
* 📢 Support Group: **https://t.me/+tU57Z7o0Az5mZThl**
* 📡 Updates Channel: **https://t.me/+tU57Z7o0Az5mZThl**

---

<div align="center">

## ❤️ Crafted with Passion by Shivam

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1200&color=FF69B4&center=true&width=700&lines=Thanks+for+visiting!;⭐+Star+the+repository+if+you+like+it!;Happy+Coding!+🚀" />

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&height=180&color=gradient&section=footer"/>

</div>
