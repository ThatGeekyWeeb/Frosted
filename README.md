# GradientSquid

## Screenshots
![screen1](https://cdn.discordapp.com/attachments/699685435198144553/736514785373454366/emoji-1.png)


## More
### How to install
Run these command:

#### Linux and MacOS:
In **Bash**:
```bash
cd "$HOME/.config/spicetify/Themes/GradientSquid"
cp dribbblish.js ../../Extensions
spicetify config extensions dribbblish.js
spicetify config current_theme GradientSquid
spicetify config inject_css 1 replace_colors 0 overwrite_assets 1
spicetify apply
```

#### Windows
In **Powershell**:
```powershell
cd "$(spicetify -c | Split-Path)\Themes\GradientSquid"
Copy-Item dribbblish.js ..\..\Extensions
spicetify config extensions dribbblish.js
spicetify config current_theme GradientSquid
spicetify config inject_css 1 replace_colors 0 overwrite_assets 1
spicetify apply
```

Windows user, please edit your Spotify shortcut and add flag `--transparent-window-controls` after the Spotify.exe
