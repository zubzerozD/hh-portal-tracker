<div align="center">

# 🏨 HH Portal Tracker

**Track rifts across Hotel Hideaway communities — in real time.**

![Discord.js](https://img.shields.io/badge/Discord.js-14-blue?logo=discord&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-15-black?logo=next.js&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-Postgres-3FCF8E?logo=supabase&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript&logoColor=white)

[![Invite Bot](https://img.shields.io/badge/Invite_Bot-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/oauth2/authorize?client_id=1537327610642567229&permissions=2147567680&scope=bot%20applications.commands)
[![Dashboard](https://img.shields.io/badge/Dashboard-0ea5e9?style=for-the-badge)](https://hh-portal-tracker.quanthia.cl)
[![Support Server](https://img.shields.io/badge/Support_Server-ff3385?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/jG6uPJDSF8)

</div>

---

## What is this?

**HH Portal Tracker** is a Discord bot + web dashboard that helps Hotel Hideaway players track rift portals across multiple communities in real time.

When someone reports a diamond or coin portal in one server, **every connected server sees it instantly** — with countdown timers, room info, and DM alerts.

## Features

| Feature | Description |
|---------|-------------|
| 🔮 **Auto-detection** | Bot detects portal reports from message format (C2 Velvet, @D1 Lobby, etc.) |
| 🌐 **Cross-server sync** | Reports are shared across all connected HH communities |
| 📊 **Live dashboard** | Real-time web UI with countdowns, stats, and manual reporting |
| 🔔 **DM alerts** | Subscribe to specific rooms and get notified instantly |
| 🏆 **Rankings** | Track who reports the most portals in your server |
| 🌍 **Bilingual** | Full Spanish & English support with `/setup language` |
| 🎭 **Role notifications** | Diamond/coin roles get pinged by portal type and tier |

## How it works

1. Player reports a portal in Discord (e.g. `C2 Velvet`)
2. Bot detects and stores the report
3. All connected servers get notified instantly
4. Web dashboard shows live countdown until expiration
5. Other players can confirm/deny if the portal is still active

## Supported rooms

Oasis Lobby · Furniture Forum · Beach · Fusion Kitchen · Velvet Room · Relaxarium · Spa · Sunset Street

## Portal types

| Type | Duration | Color |
|------|----------|-------|
| 💎 Diamond | 8 min | Blue |
| 🪙 Coin | 10 min | Orange |

## Tech stack

- **Bot:** Discord.js 14, TypeScript, Node.js
- **Web:** Next.js 15, React 19, Tailwind CSS 4
- **Database:** Supabase (PostgreSQL)
- **Deploy:** Northflank (bot) + Vercel (dashboard)

## Contact

- **Discord:** [Support Server](https://discord.gg/jG6uPJDSF8)
- **Dashboard:** [hh-portal-tracker.quanthia.cl](https://hh-portal-tracker.quanthia.cl)

---

<div align="center">

**Hotel Hideaway** is a game by [Pocket Worlds](https://pocketworlds.com). This project is an independent fansite and is not affiliated with or endorsed by Pocket Worlds.

</div>
