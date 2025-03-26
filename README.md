# Moxer Constrast Theme

![screen](assets/cover.png)

## Palette

![palette](assets/palette.jpg)

* ![#000000](https://placehold.co/16/000000/000000.png) `#000000` Black
* ![#435AAD](https://placehold.co/16/435AAD/435AAD.png) `#435AAD` Blue
* ![#946A52](https://placehold.co/16/946A52/946A52.png) `#946A52` Brown
* ![#81C5DA](https://placehold.co/16/81C5DA/81C5DA.png) `#81C5DA` Cyan
* ![#B2E4AE](https://placehold.co/16/B2E4AE/B2E4AE.png) `#B2E4AE` Green
* ![#BD733D](https://placehold.co/16/BD733D/BD733D.png) `#BD733D` Orange
* ![#7CA4C0](https://placehold.co/16/7CA4C0/7CA4C0.png) `#7CA4C0` Paleblue
* ![#D491B9](https://placehold.co/16/D491B9/D491B9.png) `#D491B9` Pink
* ![#6D6BA5](https://placehold.co/16/6D6BA5/6D6BA5.png) `#6D6BA5` Purple
* ![#D46C6C](https://placehold.co/16/D46C6C/D46C6C.png) `#D46C6C` Red
* ![#A99BE2](https://placehold.co/16/A99BE2/A99BE2.png) `#A99BE2` Violet
* ![#FFFFFF](https://placehold.co/16/FFFFFF/FFFFFF.png) `#FFFFFF` White
* ![#F5DFA5](https://placehold.co/16/F5DFA5/F5DFA5.png) `#F5DFA5` Yellow
* ![#FFF017](https://placehold.co/16/FFF017/FFF017.png) `#FFF017` Accent
* ![#090A0F](https://placehold.co/16/090A0F/090A0F.png) `#090A0F` Background
* ![#8E95B4](https://placehold.co/16/8E95B4/8E95B4.png) `#8E95B4` Foreground
* ![#212431](https://placehold.co/16/212431/212431.png) `#212431` Shade1
* ![#2C303F](https://placehold.co/16/2C303F/2C303F.png) `#2C303F` Shade2
* ![#35394B](https://placehold.co/16/35394B/35394B.png) `#35394B` Shade3
* ![#3F445A](https://placehold.co/16/3F445A/3F445A.png) `#3F445A` Shade4
* ![#555B77](https://placehold.co/16/555B77/555B77.png) `#555B77` Shade5
* ![#6B7394](https://placehold.co/16/6B7394/6B7394.png) `#6B7394` Shade6
* ![#2C303F](https://placehold.co/16/2C303F/2C303F.png) #2C303F50 Borders

## Override theme colors

You can override the theme UI and schemes colors by adding these theme-specific settings to your configuration. For advanced customisation please check the [relative section on the VS Code documentation](https://code.visualstudio.com/docs/getstarted/themes#_customizing-a-color-theme).

### Color Scheme override

**Basic example**
``` js
"editor.tokenColorCustomizations": {
    "[Moxer]": {
        "comments": "#229977"
    }
},
```

**Advanced example**

``` js
"editor.tokenColorCustomizations": {
    "[Moxer]": {
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
},

"workbench.colorCustomizations": {
    "[Moxer]": {
        "sideBar.background": "#ff0000",
    }
},
```

## Recommended settings for a better experience

``` js
{
    // Controls the font family. You need Operator Mono Font
    "editor.fontFamily": "Operator Mono Lig",
    // Controls the line height. Use 0 to compute the lineHeight from the fontSize.
    "editor.lineHeight": 30,
    // Enables font ligatures
    "editor.fontLigatures": true,
    // Controls if file decorations should use badges.
    "explorer.decorations.badges": true,
    "explorer.decorations.colors": false
}
```
