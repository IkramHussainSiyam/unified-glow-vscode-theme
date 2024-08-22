# Unified Glow VS Code themes

There are multiple themes you like? Often changing themes for a change of pace? But afraid of installing too many extensions? Then I got you. You don't need to install multiple themes, Unified glow has all popular themes you need.

To make your vscode appeareance even more cooler follow my [recommendation](#recommendation).

## Install

1. Go to [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=IkramHussainSiyam.unified-glow-vscode-theme).
2. Click on the "Install" button.
3. Then [select your favorite theme](https://code.visualstudio.com/docs/getstarted/themes#_selecting-the-color-theme):
   - `Next.js | Unified Glow`
   - `GitHub | Unified Glow`
   - `Bearded anthracite | Unified Glow`
   - `Monokai Pro | Unified Glow`
   - `Flate | Unified Glow`
   - `Tokyo night | Unified Glow`
   - `Ayu | Unified Glow`
   - `One Monokai | Unified Glow`
   - `One Dark | Unified Glow`
   - `Nord | Unified Glow`

## Override this theme

To override this (or any other) theme in your personal config file, please follow the guide in the [color theme](https://code.visualstudio.com/api/extension-guides/color-theme) documentation. This is handy for small tweaks to the theme without having to fork and maintain your own theme.

## Recommendation

I Recommend using and italics font to make appearance even more beautiful. Personally I love [Cascadia Code](https://github.com/microsoft/cascadia-code). It has beautiful script italic variant which will help to achive more cooler look.

#### Go to `settings.json` and apply the following:

```json
"editor.tokenColorCustomizations": {
  "textMateRules": [
    {
      "scope": " ", // blank space means italic will be applied to all scopes
      "settings": {
        "fontStyle": "italic"
      }
    }
  ]
},

"editor.fontFamily": "Cascadia Code, consolas, monospace",
// enable script italics variant
"editor.fontLigatures": "'dlig','ss01','ss02','ss03','ss04','ss05','ss06','ss07','ss08','ss09','ss10','ss11','zero'",
"editor.fontWeight": "360",
"editor.fontSize": 16,
"editor.lineHeight": 1.65,
```

## Final Words

👏 Thanks for downloading this theme. If you have any ideas, suggestions, or issues, please [open an issue](https://github.com/IkramHussainSiyam/unified-glow-vscode-theme/issues/new) on GitHub.
