# CoreGameTemplate

A template repository for Core games. In general, setting up a new repository should take only a few minutes; use this repository as a way of finding example files, and use the following checklist to ensure that you've set up the repository correctly.

## About this Template

This template provides you a quick way to get started with a Core game project on GitHub. It includes the following config files:

- `.luacheckrc` for linting and error checking your game scripts. This file will get updated with almost every Core patch so make sure to stay up to date.
- `.gitignore` for preventing you from accidentally checking in unneeded files into the repository. For Core this includes screenshots and other user specific or temporary files.
- `.editorconfig` for setting up a consistent code style across the project.
- Visual Studio Code extensions:
  - If you are using VS Code, opening this project in it will cause a popup to appear that asks you if you want to install the recommended extensions for it.
  - We suggest using at least the following three extensions: [LuaCoderAssist](https://marketplace.visualstudio.com/items?itemName=liwangqian.luacoderassist), [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) and [Core Lua API Autocomplete](https://marketplace.visualstudio.com/items?itemName=manticoregames.vscode-core).

## Checklist

Go through this checklist after creating your repository. It should only take a couple of minutes; if there is a way to make this more efficient, please open an issue or pull request with your suggestions.

### Other Files

- [ ] Delete or customize `CODE_OF_CONDUCT.md`.
- [ ] Delete or customize `CONTRIBUTING.md`.

### Dotfiles

- [ ] Make sure `.editorconfig` matches your preferred code style.

### License

- [ ] Delete or edit `LICENSE` depending on if you want to use the MIT license or a different one. Make sure to replace the placeholders in it as well.

### GitHub Metadata

- [ ] Have you added a short description to the repository?
- [ ] Have you added topics to the GitHub repository: `core`, `coregames`, `lua`, `game`, and so on?

### README

- [ ] Replace `README.md` with the contents of `example-README.md` and then delete `example-README.md`.
- [ ] Rename all instances of `$YOURGAMENAME` in the README to match your repo title.
- [ ] Manually go through and edit the rest of the README.
