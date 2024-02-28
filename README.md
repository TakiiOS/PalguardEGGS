
# PalGuard for Pterodactyl

This repository contains Pterodactyl eggs that include PalGuard, a comprehensive anti-cheat solution for Palworld servers.

## About PalGuard

PalGuard is a powerful anti-cheat plugin designed specifically for Palworld servers. It provides advanced protection against various types of cheats, hacks, and exploits, ensuring a fair and enjoyable gaming experience for all players.

## Installation

To install PalGuard on your Pterodactyl server, follow these steps:

1. Download the contents of the `PalGuard` directory from this repository.
2. Upload the `PalGuard` directory to your Pterodactyl egg directory.
3. Create a new egg in your Pterodactyl panel with the following details:
   - **Name**: PalGuard
   - **Description**: A powerful anti-cheat plugin for Palworld servers.
   - **Docker Image**: Your preferred Palworld server image.
   - **Startup Command**: The startup command for your Palworld server.
   - **Configuration**: Select `PalGuard` from the dropdown menu.
4. Create a new server in your Pterodactyl panel with the following details:
   - **Name**: Your server name
   - **Description**: Your server description
   - **Owner**: Your Pterodactyl account
   - **Nest**: PalGuard
   - **Egg**: PalGuard
   - **Docker Image**: Your preferred Palworld server image.
   - **Startup Command**: The startup command for your Palworld server.
5. Configure any additional settings as needed and click on `Create`.
6. Your server is now set up with PalGuard! You can start and manage it from the Pterodactyl panel.

## Support

For support or inquiries on the eggs use github issues with \Pal\Saved\Crashes\*random numbers*\CrashContext.runtime-xml file + palguard version used + log from Pal\Binaries\Win64\logs folder.

**Special thanks for https://github.com/CuteNatalie for main code of steamcmd wine.**
