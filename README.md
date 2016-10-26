# IBM Color Palette
This is a fork of Mike Schultz' great desktop app [Materialette](https://github.com/mike-schultz/materialette),
using the [IBM Color Palette](https://github.com/IBM-Design/colors/) instead.

Made using [electron](http://electron.atom.io/).

## Install

### macOS
1. Download the latest build from the [releases](https://github.com/mike-schultz/materialette/releases) section. Make sure to choose your operating system appropriately.
2. Unzip the Materialette.zip.
3. Move the Materialette.app file to the `/Applications` directory

### Windows 7.1+
1. Unzip to a desired location and run the exe

### Linux (Some distros)
1. Unzip to a desired location and run the exe

Note: There are some known issues with using electron + [menubar](https://github.com/maxogden/menubar) with Linux.

#### Confirmed:
* Ubuntu 16.04
  * Requires libappindicator1. Install with `sudo apt-get install libappindicator1`.
  * Upon opening, a blank button is presented. Clicking it will load Materialette.
* Fedora 24

If you are able to run the app successfully in a different distro, please update this README!

## Develop
* Install dependencies: `$ npm install`
* Compile SCSS -> CSS `$ gulp sass` or `$ gulp sass:watch`
* Start the application with `$ npm start `
* Build the application with  `$ npm run build`
