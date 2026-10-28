<div align="center">

<img src="images/marketplace-icon.png" width="140" />

# Menthol Theme

> A modern and minimalistic color theme for Visual Studio Code featuring mint accents and warm contrasting colors. Optimized for semantic highlighting across major programming languages.

[![Install from VS Code Marketplace](https://img.shields.io/badge/VS%20Code-Install%20Menthol%20Theme-007ACC?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=UltraKostik.vscode-menthol-theme)
[![Install from Open VSX](https://img.shields.io/badge/Open%20VSX-Install%20Menthol%20Theme-C160EF?style=for-the-badge)](https://open-vsx.org/extension/UltraKostik/vscode-menthol-theme)

![Preview of the extension](images/readme-slide.png)

</div>

---

## Overview

The Menthol Theme extension includes three carefully crafted color schemes to suit different working environments and accessibility needs:

*   **Menthol Theme (Standard):** The original dark theme with signature mint and warm contrasts.
*   **Menthol Theme Dark:** A deeper, slightly muted variation for low-light environments.
*   **Menthol Theme High Contrast:** A high-accessibility version designed for maximum readability, featuring a pure black background and bright, distinct accent colors compliant with high-contrast standards.

## Installation

### From Visual Studio Code Marketplace

1. Visit the [Menthol Theme page](https://marketplace.visualstudio.com/items?itemName=UltraKostik.vscode-menthol-theme) on the Visual Studio Code Marketplace.
2. Click the **Install** button.
3. After installation, open the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`).
4. Select **Preferences: Color Theme** and choose one of the Menthol Theme variations.

For more details on selecting themes, please refer to the [Visual Studio Code Color Theme documentation](https://code.visualstudio.com/docs/getstarted/themes#_selecting-the-color-theme).

### From Open VSX (VSCodium, Cursor, Theia, etc.)

1. Visit the [Menthol Theme page](https://open-vsx.org/extension/UltraKostik/vscode-menthol-theme) on Open VSX.
2. Click the **Install** button, or use your editor's built-in extension marketplace.
3. After installation, open the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`).
4. Select **Preferences: Color Theme** and choose one of the Menthol Theme variations.

### From GitHub (Manual Installation)

```bash
git clone https://github.com/UltraKostik/vscode-menthol-theme.git
cd vscode-menthol-theme
npm install
npx @vscode/vsce package
```

Then, in Visual Studio Code: Extensions view → `...` → **Install from VSIX...** → select the generated `.vsix` file.

## Customization

To customize any of the Menthol Theme variations, you can override colors in your user or workspace settings. For example:

```json
{
  "workbench.colorCustomizations": {
    "[Menthol Theme]": {
      "editor.background": "#0A1118",
      "activityBarBadge.background": "#5AC8A8"
    }
  },
  "editor.tokenColorCustomizations": {
    "[Menthol Theme]": {
      "comments": "#5A9A7A"
    }
  }
}
```

Please refer to the official guide on [customizing a color theme](https://code.visualstudio.com/docs/getstarted/themes#_customize-a-color-theme) for more advanced adjustments.

## Contributing

Contributions, bug reports, and feature requests are welcome. Please use the following guidelines:

- **Bug Reports & Feature Requests**: Open an issue via [GitHub Issues](https://github.com/UltraKostik/vscode-menthol-theme/issues).
- **Pull Requests**: Submit your enhancements directly.
- **Support**: Star the repository if you find the theme useful.

### How to contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`.
3. Make your changes.
4. Commit: `git commit -m 'Add some feature'`.
5. Push: `git push origin feature/your-feature`.
6. Open a Pull Request.

All contributions are welcome and appreciated.
