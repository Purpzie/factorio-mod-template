# Factorio Mod Template
This is based off of [Raiguard's](https://github.com/raiguard) mod template. Replace `modname` in all files, then modify `src/info.json` accordingly.

Feel free to use it if you like, but be sure to modify or replace `LICENSE` *and* `src/LICENSE` to use your name. Also, modify `info.json` to use you as the author & contact. If you didn't install Factorio through Steam, you'll also need to modify `launch.json` to include the correct path to `factorio.exe`.

The below section is a part of this template.

## Tips for contributing
1. Open Factorio, install the [Editor Extensions](https://mods.factorio.com/mod/EditorExtensions) and [Factorio Library](https://mods.factorio.com/mod/flib) mods, then close the game.
1. Clone this respository.
1. Symlink `src` into [Factorio's `mods` folder](https://wiki.factorio.com/Application_directory). Name it `modname`.
1. Open this repository in VSCode and install the [Factorio Mod Debug](https://marketplace.visualstudio.com/items?itemName=justarandomgeek.factoriomod-debug) extension. A popup should also recommend this to you.
1. If you did NOT use Steam to install Factorio, modify `.vscode/launch.json` to use the correct path to `factorio.exe`. **Please do not commit this change.**
1. Viola, you can now use the debugger.
