# STW-Claimer-Fortnite-Save-the-World-Discord-Bot


🌍 STW Claimer — Fortnite Save the World Discord Bot

A private Discord bot that automatically claims free llamas, tracks daily quests, and posts live mission alerts for Fortnite: Save the World.


✨ Features

🦙 Auto-claim free llamas — opens your daily free llamas and shows loot
📋 Daily quest tracker — view active quests with progress bars
🔄 Quest reroll — reroll any daily quest directly from Discord
⚡ STW Mission Alerts — get notified when rare missions appear (superchargers, flux, X-Ray tickets, schematics...)
🔐 Per-user accounts — each Discord user manages their own Epic accounts privately
🎮 Multi-account support — link and run multiple Epic accounts at once
🤖 Slash commands — fully modern Discord slash command interface with rich embeds



📋 Commands
/addaccount      -
/accounts        -
/removeaccount   -
/run             -
/quests          -
/rerollquest     -
/status          -


🔐 Privacy & Security

This bot is designed with privacy as a priority:

-Account linking is done entirely via DM — no credentials are ever posted in a public or shared channel
-Each Discord user's data is stored separately in individual auth_<user_id>.json files
-Device auth tokens are used instead of passwords — you can revoke them anytime from your Epic Games account settings
-No passwords are ever stored — only Epic device auth credentials (deviceId + secret)
-Bot responses are ephemeral — only you can see your own account data and claim results
-Your data is stored locally on the machine running the bot and is never sent to any third party

🛡️ Revoking Access

To revoke the bot's access to your Epic account at any time:

Go to epicgames.com → Account → Apps & Games
Find and remove the device auth entry
Use /removeaccount in Discord to clean up local data

⚠️ Disclaimer
This project is not affiliated with, endorsed by, or related to Epic Games. Use at your own risk. Automating Epic Games accounts may violate their Terms of Service.

