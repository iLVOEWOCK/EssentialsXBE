![EssentialsX](https://i.imgur.com/CP4SZpB.png)

This is an unofficial port of the popular EssentialsX plugin for PocketMine-MP, a Minecraft: Bedrock Edition server software. EssentialsX is a comprehensive plugin that provides essential commands and features for server administration and player convenience.

## Under Development

This plugin is still under very heavy development, if you want to experiment with this, please use this source code along with [DevTools](https://poggit.pmmp.io/p/DevTools) so that this plugin can properly run, as Poggit PHAR compiler currently breaks the plugin.

## Features

- Core commands: Includes essential commands such as `/help`, `/teleport`, `/gamemode`, `/ptime`, `/weather`, etc. 
- Economy system: Supports an in-game economy system with commands for balance, payment, and more. 
- Home and teleportation: Allows players to set multiple homes, teleport to locations, and manage warps.
- Kits: Define and provide kits with pre-defined sets of items and permissions.
- And more: Many other features and modules to enhance your server's functionality.

## Installation

1. Download the latest release of the EssentialsX port for PocketMine-MP.
2. Place the plugin PHAR file into the `plugins` folder of your PocketMine-MP server.
3. Start or restart your server to load the plugin.

## Configuration

The plugin provides a comprehensive configuration file that allows you to customize various aspects of its functionality. You can find the configuration file at `plugin_data/EssentialsX/config.yml`. Open the file using a text editor and modify the settings as per your preferences.

## Usage

The plugin provides a wide range of commands and features. Here are some examples:

- `/gamemode`: Changes the player's game mode (survival, creative, adventure, spectator).
- `/kit`: Grants the player a pre-defined kit with items and permissions.
- `/spawn`: Teleports the player to the server spawn location.

Please refer to the official EssentialsX documentation for a complete list of commands and their usage.

## Contributing

Contributions to the EssentialsX Port for PocketMine-MP are welcome! If you have any bug reports, feature requests, or code improvements, feel free to open an issue or submit a pull request on the project's GitHub repository.

## License

This project is licensed under the [GNU General Public License v3.0](https://github.com/iLVOEWOCK/EssentialsXBE/blob/main/LICENSE).

## Credits

The EssentialsX Port for PocketMine-MP is a community-driven project based on the original EssentialsX plugin. Special thanks to the original authors and contributors for creating the original plugin.

## Contributions

Contributions to the EssentialsX Port for PocketMine-MP are welcome! If you'd like to contribute to the project, follow these steps:

1. Fork the repository and create a new branch for your contribution.
2. Make your code changes or additions.
3. Ensure your code follows the project's coding conventions and standards.
4. Test your changes thoroughly.
5. Commit your changes and push them to your forked repository.
6. Open a pull request on the main project repository, describing your changes and their purpose.

Contributions can include bug fixes, feature enhancements, documentation improvements, or any other valuable contributions to the project.

By contributing to this project, you agree to release your contributions under the project's [GNU General Public License v3.0](https://github.com/iLVOEWOCK/EssentialsXBE/blob/main/LICENSE).

## To Do

- [ ] Add Timed Teleport
- [ ] Home API
- [x] Warp API (untested)
- [ ] Pemrissions API
- [ ] Economy
- [x] Warps
- [ ] Convert Warps to use SQL
- [x] Convert Homes to use SQL
- [x] Homes
- [x] Make homes async
- [ ] Make home TP faster
- [ ] Make getAllHomes method faster
- [ ] TPA's
- [ ] Fix /anvil
- [ ] Fix /back
- [ ] Fix /afk
- [ ] Add Remaining EssnetialsX Commands
- [x] Ban Lookup
- [ ] Permission Manager
- [ ] Server Backups
- [x] Fortune Enchantment [Credits](https://github.com/Taylor-pm-pl/VanillaEC/tree/5088b9835f65303546209d0b1670723cc022d4aa/)
- [x] Smite Enchantment [Credits](https://github.com/Taylor-pm-pl/VanillaEC/tree/5088b9835f65303546209d0b1670723cc022d4aa/)
- [x] Looting Enchantment [Credits](https://github.com/Taylor-pm-pl/VanillaEC/tree/5088b9835f65303546209d0b1670723cc022d4aa/)
- [x] Bane of Arthropods [Credits](https://github.com/Taylor-pm-pl/VanillaEC/tree/5088b9835f65303546209d0b1670723cc022d4aa/)
- [x] Depth Strider
- [x] Kits
- [ ] Potions
- [ ] /trade
- [x] Make Fly messages configurable
- [x] Move messages into a messages.yml configuration
- [x] Move kits into a separate kits.yml configuration
- [ ] Make DB configurable for own server use

