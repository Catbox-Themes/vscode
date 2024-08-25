# vscode

VsCode CatBox themes

## Install

Copy the JSON for your theme into `settings.json`, and select the Catppuccin Latte Theme from the [official theme](https://github.com/catppuccin/vscode) (Extension id [`Catppuccin.catppuccin-vsc`](https://marketplace.visualstudio.com/items?itemName=Catppuccin.catppuccin-vsc))

<details>
  <summary>CatBox Masala Chai</summary>

```json
    "catppuccin.colorOverrides": {
        "latte": {
            "rosewater": "#e68d70",
            "flamingo": "#d87c7a",
            "pink": "#df8f92",
            "mauve": "#a768f9",
            "red": "#d54d52",
            "maroon": "#f0606d",
            "peach": "#f07f40",
            "yellow": "#da9413",
            "green": "#4cab38",
            "teal": "#78bfb8",
            "sky": "#60bfe5",
            "sapphire": "#56adcf",
            "blue": "#6c97e1",
            "lavender": "#9799ff",
            "text": "#322c2a",
            "subtext1": "#473c36",
            "subtext0": "#5a4f44",
            "overlay2": "#6f6254",
            "overlay1": "#847564",
            "overlay0": "#988873",
            "surface2": "#ad9c86",
            "surface1": "#c1aa8e",
            "surface0": "#d8c1a4",
            "base": "#f2e5bc",
            "mantle": "#ebdbb2",
            "crust": "#d5c4a1"
        }
    },
```
</details>

## Colored Comments Support

Just add the config for your theme to your `settings.json`


<details>
  <summary>CatBox Masala Chai</summary>

```json
    "colorful-comments.tags": [

        {
            "tag": "!",
            "color": "#d54d52",
            "strikethrough": false,
            "backgroundColor": "transparent"
        },
        {
            "tag": "?",
            "color": "#6c97e1",
            "strikethrough": false,
            "backgroundColor": "transparent"
        },
        {
            "tag": "//",
            "color": "#5a4f44",
            "strikethrough": true,
            "backgroundColor": "transparent"
        },
        {
            "tag": "^",
            "color": "#da9413",
            "strikethrough": false,
            "backgroundColor": "transparent"
        },
        {
            "tag": "*",
            "color": "#4cab38",
            "strikethrough": false,
            "backgroundColor": "transparent"
        },
        {
            "tag": "&",
            "color": "#f0606d",
            "strikethrough": false,
            "backgroundColor": "transparent"
        },
        {
            "tag": "~",
            "color": "#9799ff",
            "strikethrough": false,
            "backgroundColor": "transparent"
        },
        {
            "tag": "todo",
            "color": "#f07f40",
            "strikethrough": false,
            "backgroundColor": "transparent"
        }
    ],
```
</details>
