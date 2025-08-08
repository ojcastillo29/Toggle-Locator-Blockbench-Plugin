# Toggle Locators - Blockbench Plugin

A simple yet powerful Blockbench plugin that allows you to quickly toggle the visibility of all locators in your Bedrock entity models.

## Features

- **One-click toggle**: Hide or show all locators in your model instantly
- **Smart detection**: Automatically finds locators by name, type, and data properties
- **Keybind**: Quickly toggle locators with the following keybind:  Ctrl + Shift + L
- **Clean workspace**: Perfect for cleaner view when working on animations or textures
- **Format support**: Support for Bedrock Entity Models (Made for Cobblemon related Models) 

## Installation

### Method 1: Manual Installation (Recommended)
1. Download the `toggle_locators.js` file from this repository
2. Open Blockbench
3. Go to **File → Plugins**
4. Click **Load Plugin from File**
5. Select the downloaded `toggle_locators.js` file
6. The plugin will be installed and ready to use

## Usage

### Via Menu
1. Open a Bedrock entity model with locators
2. Go to **View → Toggle Locators**
3. All locators will be hidden/shown based on current visibility state

### What Gets Detected as Locators
The plugin detects locators using multiple criteria:
- Elements with `type === 'locator'`
- Elements with names starting with `locator_`
- Elements containing locator data properties

## Supported Formats

- ✅ Bedrock Edition
- ✅ Bedrock Edition (Old)
- ✅ OptiFine Entity

## Screenshots

*Screenshots coming soon - feel free to contribute some!*

## Requirements

- Blockbench version 4.6.0 or higher
- A Bedrock entity model with locators

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Setup
1. Fork this repository
2. Make your changes to `toggle_locators.js`
3. Test thoroughly in Blockbench
4. Submit a pull request

## Issues and Support

If you encounter any issues or have suggestions for improvements:

1. Check the [Issues](../../issues) page to see if your issue has already been reported
2. If not, [create a new issue](../../issues/new) with:
   - Blockbench version
   - Operating system
   - Steps to reproduce the problem
   - Expected vs actual behavior

## Changelog

### v1.0.0 (Current)
- Initial release
- Toggle visibility for all locators
- Smart locator detection
- Support for Bedrock formats

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Created by **Ojcastillo29**

---

### Like this plugin?

If you find this plugin useful, please consider:
- ⭐ Starring this repository
- 🐛 Reporting any bugs you find
- 💡 Suggesting new features
- 🔄 Sharing it with other Blockbench users

---

*This plugin is not officially affiliated with Blockbench or Mojang Studios.*
