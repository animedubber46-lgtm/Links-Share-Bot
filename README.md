🌟 What is LinkShareBot?

LinkShareBot is a modern Telegram bot that allows you to share and manage unlimited Telegram channel links with automatic invite link generation and management.

Powered by Pyrogram, it provides a seamless experience for users to join channels through secure, auto-expiring links. The bot includes advanced features like force subscription, bulk link generation, and request link management.

🚀 Features

🌟 Feature

🔎 Description

📺 Unlimited Channels

Add and manage unlimited Telegram channels

🔗 Auto Invite Links

Generate secure, auto-expiring invite links

⏱️ Auto Revoke

Links automatically revoke after 5 minutes

📦 Bulk Generation

Generate links for multiple channels at once

📋 Pagination Support

Navigate through large channel lists easily

🔄 Request Links

Support for join request links

🛡️ Force Subscription

Require users to join specific channels

📊 Bot Statistics

Monitor bot usage and user statistics

🛠️ Commands

Channel & Link Management (Owner/Admins)

/addch <channel_id> — Add a channel to the bot (admin only)

/delch <channel_id> — Remove a channel from the bot (admin only)

/channels — Show all connected channels as buttons (paginated)

/reqlink — Show all request links for channels (paginated)

/links — Show all channel links as text (paginated)

/bulklink <id1> <id2> ... — Generate links for multiple channel IDs at once

/channels — Show all connected channel IDs and names (paginated, with next/prev buttons and auto-deleting "please wait..." status)

/reqtime — Set the auto-approve request timer duration.

/reqmode — Toggle auto request approval mode (ON/OFF).

/approveon — Enable auto request approval for a specific channel.

/approveoff — Disable auto request approval for a specific channel.

/approveall — Approve all pending join requests in a channel using userbot (make sure to fill your session string in approve.py).

Admin Commands

/stats — Show bot stats (owner only)

/status — Show bot status (admins)

/broadcast — Broadcast a message to all users (admins)

/cleanup — Remove inactive users from database (admins)

🔑 Environment Variables

Below are the required and optional environment variables for deployment.

API_ID=              # Required - Get from https://my.telegram.org
API_HASH=            # Required - From https://my.telegram.org
TG_BOT_TOKEN=        # Required - Get from @BotFather
OWNER_ID=            # Required - Your Telegram user ID
ADMINS=              # Required - Admin user IDs (space separated)
DB_URL=              # Required - MongoDB connection string
DB_NAME=             # Optional - MongoDB database name (default: LinkShareBot)
DATABASE_CHANNEL=    # Required - Private channel ID for link storage

⚠️ Never expose raw credentials or tokens in public repos. Use safe paste services like Pastebin or Batbin.







☕ VPS Setup Guide

🎵 Deploy LinkShareBot on VPS

# Step 1: Update & Install Dependencies
sudo apt update && sudo apt upgrade -y
sudo apt install -y git curl python3-pip python3-venv ffmpeg unzip tmux

# Step 2: Clone & Setup
git clone https://github.com/yourusername/LinkShareBot
cd LinkShareBot
tmux new -s LinkShareBot

# Inside tmux:
python3 -m venv venv
source venv/bin/activate
pip install -U pip && pip install -r requirements.txt

# Create .env file with your environment variables
nano .env

# Run the bot
python3 main.py

### Useful Commands
tmux detach                      # Use Ctrl+B, then D
tmux attach-session -t LinkShareBot       # Reattach session
tmux kill-session -t LinkShareBot         # Kill bot session
rm -rf LinkShareBot                # Uninstall bot



🐳 Docker Deployment

### Step 1: Clone Repo
git clone https://github.com/yourusername/LinkShareBot
cd LinkShareBot

### Step 2: Create .env File
nano .env
# Paste your environment variables here and save (Ctrl+O, Enter, Ctrl+X)

### Step 3: Build Image
docker build -t linksharebot .

### Step 4: Run Container
docker run -d --name linkshare --env-file .env --restart unless-stopped linksharebot

### Step 5: Manage Container
docker logs -f linkshare        # View logs (Ctrl+C to exit)
docker stop linkshare           # Stop container
docker start linkshare          # Start again
docker rm -f linkshare          # Remove container
docker rmi linksharebot         # Remove image



☁️ Quick Deploy

Platform

Deploy Link

🌍 Heroku Deploy



💬 Community & Support



🔖 Credits

 ᴄʀᴀғᴛᴇᴅ ᴡɪᴛʜ ᴘᴀssɪᴏɴ ʙʏ ʏᴀᴛᴏ
