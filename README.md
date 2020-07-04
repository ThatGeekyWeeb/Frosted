# Dribbblish

## Screenshots
[!screen1](https://media.discordapp.net/attachments/635625925748457482/728824094103175228/unknown.png?width=888&height=499)


## More
### How to install
Run these command:

#### Linux and MacOS:
In **Bash**:
```bash
cd "$HOME/.config/spicetify/Themes/GradientSquid"
cp dribbblish.js ../../Extensions
spicetify config extensions dribbblish.js
spicetify config current_theme Dribbblish color_scheme base
spicetify config inject_css 1 replace_colors 0 overwrite_assets 1
spicetify apply
```

#### Windows
In **Powershell**:
```powershell
cd "$(spicetify -c | Split-Path)\Themes\Dribbblish"
Copy-Item dribbblish.js ..\..\Extensions
spicetify config extensions dribbblish.js
spicetify config current_theme Dribbblish color_scheme base
spicetify config inject_css 1 replace_colors 0 overwrite_assets 1
spicetify apply
```

Windows user, please edit your Spotify shortcut and add flag `--transparent-window-controls` after the Spotify.exe
