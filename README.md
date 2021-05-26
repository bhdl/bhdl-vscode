# bhdl-vscode extension

This extension add syntax highlights for BHDL keywords. After installation, edit
a `.rkt` file, and you will see syntax highlights for BHDL keywords, like the
image below.

![image](assets/example.png)

## Installation

To install the extension, download the `.vsix` file (e.g. `bhdl-0.0.1.vsix`) in the [release page](https://github.com/bhdl/bhdl-vscode/releases), and run:

```
code --install-extension bhdl-0.0.1.vsix
```

To remove the extension from your VSCode, you should be able to uninstall it in
VSCode's extension manager.

## Development

Generating the `.vsix` file:

```
vsce package
```
