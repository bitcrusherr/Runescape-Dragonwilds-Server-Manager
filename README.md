# Runescape-Dragonwilds-Server-Manager
# TSP Dragonwilds Server Manager

Control panel and live tracker for **RuneScape: Dragonwilds** dedicated servers.

Built for community hosts (including [TSP / The Stealth Pancakes](https://tsp-server.com)) — start/stop, live map & players, public status, Discord slash ops, alerts, backups, multi-server fleet, and more.

**Free** covers day-to-day hosting. **Pro** unlocks Discord automation, smart alerts, Backup Pro, branding/embed, staff seats, player CRM, and deep statistics.

> This repository is the **private product source**. Customers get the portable zip / Setup build, not this repo.

## Features
- Live player tracker, Ashenfall map, public status page
- Admin dashboard (start/stop, announce, moderation, achievements)
- Discord webhooks + slash commands (`/status`, `/online`, …) — Pro
- Smart alerts, automation playbooks, scheduled messages — Pro
- Control Centre + world backups, SteamCMD update helpers
- Multi-server profiles, branding/embed widget, staff seats, player CRM — Pro

## Stack
- PHP (XAMPP / portable runtime)
- Python tracker
- Windows host tooling (SteamCMD / `Start-Server.bat`)

## Docs
- Customer Pro guide: `standalone/PRO.md`
- Standalone / packaging: `standalone/README.md`
- Changelog: `standalone/CHANGELOG.md`

## License
Proprietary — see `standalone/LICENSE.txt`. Runtime packages may be distributed; source redistribution is not permitted without permission.
