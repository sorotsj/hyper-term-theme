# Hyper-Dark

HyperTerm inspired VSCode theme with vivid syntaxcolors and a pitch black UI. _Drools on the floor.._

![React/JS (Details)](static/js-detail.png)

[GitHub repository](https://github.com/HasseNasse/hyper-term-theme)

# CHANGELOG

[CHANGELOG.MD](https://github.com/HasseNasse/hyper-term-theme/blob/master/CHANGELOG.md)

# Docs & Contribute

1. Install the theme
2. Reload VSCode
3. Press ctrl(⌘) + k, then press ctrl(⌘) + t, you will see a theme selection interface. Choose 'Hyper Term Black'.
4. Change the following user settings on VS Code:

```javascript
{
    "editor.fontFamily": "Menlo, 'DejaVu Sans Mono', Consolas, 'Lucida Console', monospace",
    "workbench.colorTheme": "Hyper Term Black",
    "editor.cursorStyle": "block",
    "editor.minimap.enabled": false,
    "editor.renderLineHighlight": "none"
}
```

## Zed

### Quick copy

Copy `themes/hyper-term-black.zed-theme.json` into your Zed configuration directory (typically `~/.config/zed/themes/`) and select **Hyper Term Black** from the theme picker.

### Install as a local Zed extension

1. Create a new folder inside `~/.config/zed/extensions/` named `hyper-term-black`.
2. Copy the `zed-extension/extension.json` file from this repository into that folder.
3. Copy the `themes/hyper-term-black.zed-theme.json` file into the same folder, preserving the `themes/` subdirectory (your structure should look like `~/.config/zed/extensions/hyper-term-black/themes/hyper-term-black.zed-theme.json`).
4. Restart Zed, then open the command palette and choose **Theme: Select Theme** to activate **Hyper Term Black**.

Alternatively, zip the `zed-extension` folder together with the `themes` directory and install it with `zed --install-extension <path-to-zip>`. This lets you share the theme as a standalone extension archive.
