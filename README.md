# Spicetify-Sidebar-Controls
![](preview.png)
Move the controls to the sidebar

#### Applying
##### Available on the marketplace
```bash
git clone https://github.com/LucyUwI/Spicetify-Sidebar-Controls
cd Spicetify-Sidebar-Controls
mv Sidebar-Controls ~/.config/spicetify/Themes
spicetify config current_theme Sidebar-Controls
spicetify apply
```
##### Windows
```powershell
git clone https://github.com/LucyUwI/Spicetify-Sidebar-Controls
cd Spicetify-Sidebar-Controls
Move-Item .\Sidebar-Controls\ ~\AppData\Local\spicetify\Themes\
spicetify config current_theme Sidebar-Controls
spicetify apply
```
### Volume Hover Extentiuon (Recomended)
![](/VHPreview.gif)
```bash
mv VolumeBeforeHover.js ~/.config/spicetify/Extensions
spicetify config extensions VolumeBeforeHover.js
spicetify apply
```
##### Windows
```powershell
Move-Item .\VolumeBeforeHover.js ~\AppData\Local\spicetify\Extensions\
spicetify config extensions VolumeBeforeHover.js
spicetify apply
```

