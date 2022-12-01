
<p align="center">
<a href="https://marketplace.visualstudio.com/items?itemName=SIRILMP.dark-theme-sm"><img src="https://vsmarketplacebadge.apphb.com/installs-short/SIRILMP.dark-theme-sm.svg?style=for-the-badge&colorA=052746&colorB=abc4ff"/></a>
<a href="https://marketplace.visualstudio.com/items?itemName=SIRILMP.dark-theme-sm"><img src="https://vsmarketplacebadge.apphb.com/downloads-short/SIRILMP.dark-theme-sm.svg?style=for-the-badge&colorA=052746&colorB=abc4ff&label=DOWNLOADS"/></a>
 <a href="https://marketplace.visualstudio.com/items?itemName=SIRILMP.dark-theme-sm#review-details"><img src="https://vsmarketplacebadge.apphb.com/rating-star/SIRILMP.dark-theme-sm.svg?style=for-the-badge&colorA=052746&colorB=abc4ff"/></a>
 
 
</p>

## Getting started

You can install this awesome theme through the [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=SIRILMP.dark-theme-sm).

### Installation

Launch *Quick Open*:
  - <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf">Linux</a> `Ctrl+P`
  - <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf">macOS</a> `⌘P`
  - <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf">Windows</a> `Ctrl+P`

Paste the following command and press `Enter`:

```shell
ext install SIRILMP.dark-theme-sm
```

And pick your favorite.

## Activate theme

Launch *Quick Open*:

  - <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf">Linux</a> `Ctrl + Shift + P`
  - <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf">macOS</a> `⌘ + Shift + P`
  - <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf">Windows</a> `Ctrl + Shift + P`

Type `theme`, choose `Preferences: Color Theme`, and select one of the Dark Theme variants from the list.

## Override theme colors

You can override the Dark Theme UI and schemes colors by adding these theme-specific settings to your configuration. For advanced customization please check the [relative section on the VS Code documentation](https://code.visualstudio.com/docs/getstarted/themes#_customizing-a-color-theme).

### Color Scheme override

**Basic example**
```js
// Overrides colors
"workbench.colorCustomizations": {
    "editor.background": "#D62AD0",
    
},

// Overrides editor syntax colors and font style
"editor.tokenColorCustomizations": {
     "comments": "#78DEC7"
},
```

**Advanced example**

```js
"editor.tokenColorCustomizations": {
    
        "textMateRules": [
            {
                "scope": [
                    "punctuation.definition.comment",
                    "comment.block",
                    "comment.line",
                    "comment.block.documentation"
                ],
                "settings": {
                    "foreground": "#FF0000"
                }
            }
        ]
},
```

## Recommended settings for a better experience

```js
{
    // Controls the font family.
    "editor.fontFamily": "Operator Mono",
    // Controls the line height. Use 0 to compute the lineHeight from the fontSize.
    "editor.lineHeight": 24,
    // Enables font ligatures
    "editor.fontLigatures": true,
    // Controls if file decorations should use badges.
    "explorer.decorations.badges": false
}
```

---
