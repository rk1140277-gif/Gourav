# Telegram Bot

A Telegram bot for managing attack requests with admin approval system, MongoDB database, and external API integration.

## Features

- 🔐 User approval system with expiration dates
- 👑 Admin commands for user management
- 📊 Attack statistics and logging
- 🚫 Blocked ports validation
- 💾 MongoDB database for persistent storage
- 🔄 24/7 deployment ready (Railway, Heroku, etc.)

## Prerequisites

- Python 3.11 or higher
- MongoDB database (Atlas or local)
- Telegram Bot Token (from @BotFather)
- External API endpoint with authentication key

## Environment Variables Setup

Create a `.env` file in the root directory with the following variables:

```env
BOT_TOKEN=8582836425:AAHpZB8y26pL1HPLEeXmTFIlMNDq5qK0PzE
MONGODB_URI=mongodb+srv://nocashsmm_db_user:aCXuIg2pyhxdeqHI@cluster0.axexvbz.mongodb.net/?appName=Cluster0
DATABASE_NAME=nocashsmm_db_user
API_URL=http://api.battle-destroyer.shop
API_KEY=ak_4cb9ca2510cd7feb1f0ae060a560c52c614162d910bc7b5d
ADMIN_IDS=1390658041
```
aCXuIg2pyhxdeqHI pass