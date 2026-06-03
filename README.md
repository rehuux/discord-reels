# Instagram Media Downloader Discord Bot

**Developer:** Syed Rehan

---

## 📌 Overview

This script allows you to create a **Discord Bot** that downloads Instagram content — including **Reels**, **Posts**, and **Stories** — directly within your Discord server.

Users simply send an Instagram link, and the bot returns the downloadable media file within seconds.

> 🎯 Perfect for Discord communities that want to share Instagram content without leaving the server.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 📹 **Reels Download** | Download any Instagram Reel |
| 🖼️ **Posts Download** | Download single or multiple image posts |
| 📸 **Stories Download** | Download Instagram Stories (public accounts) |
| ⚡ **Fast Response** | Media ready in just seconds |
| 🔔 **Simple Commands** | Easy to use with !ping and !help |

---

## 🤖 Bot Commands

| Command | Description |
|---------|-------------|
| `!ping` | Check bot response time (latency) |
| `!help` | Show all available commands and usage guide |
| `!download <url>` | Download Instagram Reel/Post/Story from given link |
| `!status` | Check bot health and uptime |

**Usage Example:**
```

!download https://www.instagram.com/reel/xxxxx

```

---

## 🔍 How It Works

```

1. User sends !download + Instagram URL
   ↓
2. Bot processes the Instagram link
   ↓
3. Bot fetches media from Instagram servers
   ↓
4. Bot downloads and processes the content
   ↓
5. Bot sends downloadable file back to Discord channel
   ↓
6. User saves the media — All within Discord!

```

> No need to leave Discord or visit Instagram directly.

---

## 🚀 What You Can Do With This Script

| Use Case | Description |
|----------|-------------|
| 📢 **Create Your Own Bot** | Build and host your custom Discord bot |
| 👥 **Add to Your Server** | Deploy bot in your Discord community |
| 🎉 **Help Server Members** | Let members download Instagram content easily |
| 🔧 **Customize Commands** | Modify and add features as needed |

---

## 🛠️ Technical Requirements

| Requirement | Detail |
|-------------|--------|
| Language | Python / Node.js (specify your stack) |
| Dependencies | Discord API, Instagram scraper/downloader |
| Hosting | Local PC, VPS, or Cloud (Railway, Render, etc.) |
| Account | Discord Bot Token (from Discord Developer Portal) |

---

## 📥 Installation (Quick Setup)

```bash
# Clone the repository
git clone https://github.com/rehuux/discord-reels.git

# Install dependencies
pip install -r requirements.txt   # For Python
# OR
npm install                        # For Node.js

# Configure bot token
# Add your Discord Bot Token in .env file

# Run the bot
python bot.py   # or node bot.js
```

---

🎮 Bot in Action

User sends:

```
!download https://www.instagram.com/reel/ABC123
```

Bot responds:

```
✅ Processing your request...
📥 Downloading Instagram Reel...

[Media File Attached]

✨ Done! Enjoy your download.
```

Ping Check:

```
User: !ping
Bot: 🏓 Pong! Latency: 85ms
```

---

💡 Why This Bot?

Problem Solution
Instagram has no native download option Bot adds download functionality
Downloading requires third-party sites Bot works directly in Discord
Many tools are unsafe or spammy Self-hosted, clean, no ads
Sharing reels across platforms is hard One click, instant share in server

---

⚠️ Disclaimer

This bot is for educational and fair-use purposes only.

· Only download content you have permission to download
· Respect Instagram's Terms of Service
· Do not use for mass downloading or copyright infringement
· The developer is not responsible for misuse of this tool

---

👨‍💻 Developer

Syed Rehan

---

📄 License

This project is open for educational use. Redistribution or commercial use requires permission.

---

🤝 Contributing

Feel free to fork, improve, and submit pull requests. Give credit if you redistribute.

---

📞 Support

For issues or suggestions, contact the developer.

---

Made with ❤️ by Syed Rehan
