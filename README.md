# Unified Glow VS Code themes

There are multiple themes & icons you like? Frequently switching between themes & icons for a change of pace? But don't want to install too many extensions & every time? Then I got your back. You don't need to install multiple themes every time just for a change of pace, **Unified glow** has all popular **themes & icons** you need in one place.

To make your VSCode appearance even more cooler follow my [recommendation](#recommendation).

## Install

1. Go to [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=IkramHussainSiyam.unified-glow-vscode-theme).
2. Click on the "Install" button.
3. Then [select your favorite theme](https://code.visualstudio.com/docs/getstarted/themes#_selecting-the-color-theme):
4. That's enjoy 🎉🥳

## Override this theme

To override this (or any other) theme, you need to edit `theme-name.json` file in your `.vscode/extensions` folder. You can follow [This guide](https://code.visualstudio.com/api/references/theme-color) to learn more about theme customization. This is handy for small tweaks to the theme without having to fork and maintain your own.

> **Note:** VSCode theme folder location:
> `user-location/.vscode/extensions/extension-publisher.extension-name-extension-version/themes/theme-name.json`

## Recommendation

Lately I've been using a cool font combined with the theme, and it's look stunning, and gives you kinda `hackery vibe`.
First you need to install [Kode Mono](https://fonts.google.com/specimen/Kode+Mono) font. This font will enable the hackery vibe paired with `Sequoia retro` or `Tokyo Night` theme.

#### Go to `settings.json` and apply the following:

```json
"editor.fontFamily": "Kode Mono, consolas, monospace",
"editor.fontWeight": "400",
"editor.fontSize": 18,
"editor.lineHeight": 1.5,
"window.zoomLevel": 2,
```

#### 💡 Pro Tip:

By default VSCode only changes editor's font, if you want to change the font of your entire editor (e.g. sidebar font, explorer font, title bar font, etc.) you need to install an extension called [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items/?itemName=be5invis.vscode-custom-css).

- First install the extension.
- Create a file called `custom-vscode-styles.css` in your desired location (any where).
- Add the following code to your `settings.json` file:

  ```json
  "vscode_custom_css.imports": [
    // example: file:///D:/vscode-settings/custom-vscode-styles.css
    "your-file-locaion/custom-vscode-styles.css"
  ],

  ```

- Go to `custom-vscode-styles.css` by pressing `CTRL + Left Click` and add the following code:

  ```css
  * {
    font-family: "Kode Mono", monospace;
  }
  ```

- Boom 🎉, That's it, It's done, enjoy VSCode's hacker mode.

## Final Words

👏 Thanks for downloading this theme. If you have any ideas, suggestions, or issues, please [open an issue](https://github.com/IkramHussainSiyam/unified-glow-vscode-theme/issues/new) on GitHub.
