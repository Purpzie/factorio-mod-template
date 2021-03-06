# Factorio Mod Template
This is based off of [Raiguard's](https://github.com/raiguard) mod template. Replace `modname` in all files.

Feel free to use it if you like, but be sure to modify or replace `LICENSE` *and* `src/LICENSE` to use your name. Also, make sure to change `src/info.json`. If you didn't install Factorio through Steam, you'll also need to modify `launch.json` to include the correct path to `factorio.exe`.

The below section is a part of this template.

## Tips for contributing
1. Open Factorio, install the [Editor Extensions](https://mods.factorio.com/mod/EditorExtensions) and [Factorio Library](https://mods.factorio.com/mod/flib) mods, then close the game.
2. Clone this respository.
3. Symlink `src` into [Factorio's `mods` folder](https://wiki.factorio.com/Application_directory). Name it `modname`.
4. Open this repository in VSCode and install the [Factorio Mod Debug](https://marketplace.visualstudio.com/items?itemName=justarandomgeek.factoriomod-debug) extension.
5. Modify `.vscode/launch.json` to use the correct path to `factorio.exe`, or set the env variable `FACTORIO_EXE_PATH`. With the extension installed, Intellisense will suggest some possible paths. **Please do not commit this change.**
6. Viola, you can now use the debugger.
