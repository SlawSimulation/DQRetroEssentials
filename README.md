# DQRetroEssentials

A lightweight, customizable Minecraft Spigot plugin offering essential quality-of-life commands for survival servers.

🧩 Built specifically for **DQRetro’s server**, this plugin includes enhanced gameplay utilities and features like **RealTimeStrat** — a real-time synchronization system that aligns the Minecraft world clock with real-world time, including immersive hourly broadcasts.

## Features

- `/sethome` & `/home` – Save and return to a personal home location
- `/spawn` & `/setspawn` – Teleport to and define the server spawn point
- `/tp` or `tpto <player>` – Teleport to another player (OP only)
- `/gamemode <0|1|2>` – Change your gamemode (OP only)
- `/timeirl` or `/time` – Display the current real-world time in-game
- **RealTimeStrat** – Optional automatic syncing of in-game time with real-world hours
- Hourly broadcast messages for immersive play

## Permissions

| Command         | Permission                       | Default |
|----------------|-----------------------------------|---------|
| `/sethome`      | `dqretroessentials.sethome`      | true    |
| `/home`         | `dqretroessentials.home`         | true    |
| `/spawn`        | `dqretroessentials.spawn`        | true    |
| `/setspawn`     | `dqretroessentials.setspawn`     | op      |
| `/tp`           | `dqretroessentials.tpto`         | op      |
| `/gamemode`     | `dqretroessentials.gamemode`     | op      |

## Installation

1. Build the plugin using Maven or your preferred IDE
2. Place the `.jar` file into your server’s `/plugins` directory
3. Restart or reload your server
4. (Optional) Edit `config.yml` to customize spawn points and behavior

## Requirements

- Spigot 1.20+ or compatible
- Java 17+

---

🔧 **Built with love by @SlawSimulation for an immersive and streamlined Minecraft survival experience.**
