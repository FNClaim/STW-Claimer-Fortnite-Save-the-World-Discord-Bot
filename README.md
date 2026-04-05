<div align="center">

# 🌍 STW Claimer
### Fortnite Save the World — Discord Bot

*A private Discord bot that automatically claims free llamas, tracks daily quests, and posts live mission alerts.*

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![discord.py](https://img.shields.io/badge/discord.py-2.x-5865F2?style=for-the-badge&logo=discord&logoColor=white)
![Epic Games](https://img.shields.io/badge/Epic%20Games%20API-000000?style=for-the-badge&logo=epicgames&logoColor=white)
![License](https://img.shields.io/badge/Private%20Use-Only-FF6B35?style=for-the-badge)

</div>

---

## ✨ Features

| | Feature | Description |
|---|---|---|
| 🦙 | **Auto-claim Free Llamas** | Opens your daily free llamas and displays full loot results |
| 📋 | **Daily Quest Tracker** | View active quests with live progress bars per objective |
| 🔄 | **Quest Reroll** | Reroll any daily quest directly from Discord |
| ⚡ | **STW Mission Alerts** | Get notified for rare missions — superchargers, flux, X-Ray tickets, schematics... |
| 🔐 | **Per-User Accounts** | Each Discord user manages their own Epic accounts privately |
| 🎮 | **Multi-Account Support** | Link and run multiple Epic accounts at once |
| 🤖 | **Slash Commands** | Modern Discord interface with rich embedded responses |

---

## 📋 Commands

| Command | Description | Permission |
|---|---|---|
| `/addaccount` | Link an Epic Games account via secure DM flow | Everyone |
| `/accounts` | List all your linked Epic accounts | Everyone |
| `/removeaccount` | Remove a linked account | Everyone |
| `/run` | Claim free llamas and view daily quests | Everyone |
| `/quests` | View daily quests with progress bars | Everyone |
| `/rerollquest` | Reroll a specific daily quest | Everyone |
| `/status` | Bot status and your account info | Everyone |
| `/setalertchannel` | Set the channel for STW mission alerts | `Manage Server` |
| `/alerts` | Toggle mission alerts on / off | `Manage Server` |
| `/refreshstringlist` | Force re-download item names | `Manage Server` |




---


2. Alerts post automatically whenever a notable mission appears

---

## 🔐 Privacy & Security

> This bot is designed with **privacy as the top priority**.

- ✅ Account linking is done entirely via **DM** — credentials are never posted in public channels
- ✅ Each Discord user's data is stored separately in individual `auth_<user_id>.json` files
- ✅ **Device auth tokens** are used instead of passwords — revoke them anytime from Epic settings
- ✅ **No passwords are ever stored** — only `deviceId` and `secret` from Epic's device auth
- ✅ Bot responses are **ephemeral** — only you can see your own account data and results
- ✅ All data is stored **locally** on your machine and never sent to any third party


```

---

## 🛡️ Revoking Access

To revoke the bot's access to your Epic account at any time:

1. Go to [epicgames.com](https://epicgames.com) → **Account** → **Apps & Games**
2. Find and remove the device auth entry
3. Run `/removeaccount` in Discord to remove local data



---

## ⚠️ Disclaimer

This project is **not affiliated with, endorsed by, or related to Epic Games**.
Use at your own risk. Automating Epic Games accounts may violate their [Terms of Service](https://www.epicgames.com/site/en-US/tos).
