# Meson for VisualStudio Code

This extension provides support for [Meson](http://mesonbuild.com/) in [Visual Studio Code](https://code.visualstudio.com/).
This is entirely based on the grammar found in the [atom extension](https://github.com/TingPing/language-meson) from [Patrick Griffis](https://github.com/TingPing).

Meson logo by @jpakkane, [licensed for use by this project](http://mesonbuild.com/legal.html).
Icons from the [Material Design Icons](https://materialdesignicons.com/) project.

## Features

- Syntax Highlighting
- Automatic Task Provider
- Code Snippets
- Linting\*
- Formatting\*

\* - requires an installation of [muon](https://muon.build).

# New extension ID

If you come from a previous installation, please make sure you are on the **mesonbuild.mesonbuild** extension.
There are 3 variants/versions of this extension on the store, and only that one is released from this repository.

# Building

1. `npm install -g vsce`
1. Maybe bump the version in `package.json`
1. `vsce package`
1. Should generate a `.vsix` in the root.
1. F1 -> Extensions Install from VSIX
