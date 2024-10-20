# MOTDCrash Plugin

## Overview

The Crash Plugin is a malicious plugin designed for Minecraft servers. When a player connects to a server running this plugin, their game will crash continuously, forcing them to delete the `servers.dat` file located in `%appdata%\.minecraft\` to regain access to their Minecraft server list.

## Warning

**This plugin is intended for educational purposes only.** It demonstrates how server-side code can impact clients, and should not be used to harm others or disrupt gameplay. Use responsibly and ensure you have permission to test this on any server.

## Features

- Modifies the server's MOTD (Message of the Day) to a length that causes the game client to crash.
- Continues to crash the game until the user deletes their `servers.dat` file.

## Installation

1. Download the latest version of the plugin JAR file.
2. Place the JAR file into the `plugins` folder of your Minecraft server.
3. Restart the server.

## Usage

- Once the plugin is installed and the server is running, any player who attempts to connect will experience a continuous game crash.
- To recover from the crashes, the affected player must delete the `servers.dat` file located in `%appdata%\.minecraft\`.

## Disclaimer

This plugin can cause disruptions to players' gaming experiences. **Do not use it on public servers or without the explicit consent of all players involved.** Misuse of this plugin could lead to bans or other consequences within the Minecraft community.

## Support

If you encounter any issues or have questions about the plugin, feel free to open an issue on this repository.
