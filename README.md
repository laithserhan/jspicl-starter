# Build your PICO-8 games in JavaScript
This project uses jspicl-cli to transpile your JavaScript code into PICO-8 cardridges.

`npm start` - Runs the game in PICO-8 and watches the source files for changes. Whenever a file is updated the cartridge is automatically reloaded with the new changes<sup>1</sup>.

`npm run build` - Only generates the cartridge for you.

## Updating spritesheet
With jspicl-CLI you don't need to draw your sprites in PICO-8 anymore. Simply edit the spritesheet file, save and the cart will be reloaded with the new changes.

![](https://github.com/AgronKabashi/assets/raw/814f6efe24bc9aca5d9d6ca6259279733529e300/rollup-plugin-jspicl/spritesheetLiveReload.gif)

## Other `jspicl` games
* [https://github.com/topics/jspicl-sample](https://github.com/topics/jspicl-sample)

<hr>
<sup>1</sup> Currently only works on MacOS. You will have to manually refresh PICO-8 (Ctrl+R) on other platforms.
