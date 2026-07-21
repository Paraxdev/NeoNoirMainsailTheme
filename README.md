# NEONOIR 

Neo-Brutalism on Mainsail!
Made to be personalized, compiled through SCSS!

![NEONOIR dashboard](screenshot.jpg)

### Setting Primary

Open **Settings > Interface** and set:

- **Primary Color** > `#7316fd`

This will be the primary used throughout the theme

---

### Making it your own
This theme was build from the ground up with customizability in mind
meaning changing colors is a breeze!

# shallow customization  
if you don't want to make deep changes you only should really touch [_token.scss](base/_tokens.scss)
there you can easily change colors, override a color or even change how the complementary color is set

# deep customization
every file with _ has a important bit of mainsail styling, if you for example want to change the console input to be more round,
you'd need to modify [_content.scss](base/_base.scss) and find "a.command, .console a.command, .consoleTableRow a.command" and
set border-radius to whatever you want.
you can write normal CSS or use more advanced SCSS features
SCSS Docs: https://sass-lang.com/guide/

## installing

```bash
git clone https://github.com/Paraxdev/NeoNoirMainsailTheme /home/$USER/printer_data/config/.theme
```
Hard-refresh Mainsail (control + shift + r)  if it doesn't update properly

## creating a new css for mainsail using node

you will need nodejs for the next part, so download using your package manager like apt (sudo apt install nodejs) or visit the nodejs website

```bash
# install packages via npm
npm install

# run command to create a new custom.css
npm run build
```

this regenerates `custom.css` in place, assuming this folder in in config/.theme



--- 

## Gallery

| | |
|---|---|
| ![Sidebar nav](screenshot1.jpg) **Sidebar** | ![Macros panel](screenshot2.jpg) **Macros**  |
| ![Console](screenshot3.jpg) **Console**  | ![Machine page](screenshot4.jpg) **Machine**  |
| ![Devices dialog](screenshot5.jpg) **Devices** | ![Settings dialog](screenshot7.jpg) **Settings** |
| ![Code editor](screenshot6.jpg) **Config editor**  | |


---


*Share and remix freely.*
