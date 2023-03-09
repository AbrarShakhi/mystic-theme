<h1 align="center"><br>
    <img src="img/icon.png" alt="logo" width="200">
    <br><br> Mystic Theme
    <h5 align="center">A mysterious theme for proffesional.<h5><br>
    <h4 align="center">
    <a href="https://marketplace.visualstudio.com/items?itemName=AbrarShakhi.abrar-mystic-theme">Download for VScode</a>
    </h4><br></h1>
<br>


---------------------------
## Color

|scope       |hex-color |
|------------|----------|
|comment     |#91a193   |
|function    |#a2cf82   |
|keyword     |#9ECBFF   |
|constant    |#d0bf96   |
|variable    |#E06C75   |
|storage     |#C39AC9   |
|string      |#e49760   |
|foreground  |#91a193   |

<br>


---------------------------
## Theme Screenshot

![html/js/cpp](img/Snapshots/3in1ss.png)
> [Dracula wallpaper]

<br>


---------------------------
## Active theme

1. First `Install` the theme
2. Press `Ctrl+Shift+P` and search for `color theme` and hit `Enter`
3. look for `Mystic Theme` then hit `Enter`
4. ⭐⭐⭐⭐⭐ Rate five-stars 😃

<br>


---------------------------
## Tweaks & theming

Change color using `workbench.colorCustomizations ` to customize the theme. Example, Add this snippet in your `settings.json` file:

```json
"workbench.colorCustomizations": {
  "tab.activeBackground": "#f00",
    "activityBar.background": "#f00",
    "sideBar.background": "#f00",
}
```
> Replace `#f00` to your favorite hex color

or use the setting `editor.tokenColorCustomizations`

```json
   "editor.tokenColorCustomizations": {
     "[Theme]": {
       "textMateRules": [
         {
           "scope": [
             "comment"
          ],
          "settings": {
            "foreground": "#f00"
          }
        }
      ]
    }
  }
```

<br>


---------------------------
## Issues & Suggestions

For any issues or suggestions, please use [GitHub issues](https://github.com/AbrarShakhi/mystic-theme/issues).

<br>


---------------------------
### Suggest Editor Settings

```json
{
  "editor.fontFamily": "Cascadia Code Light",
    "editor.fontLigatures": "'calt', 'ss01'"
}
```