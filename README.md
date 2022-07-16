# New BSPWM Rice

![Screenshot](https://github.com/Spaxly/BSPWM-rice/blob/main/assets/screenshot.png?raw=true)

File Manager: PCManFM
  <br><br>
    Terminal: Alacritty
  <br><br>
    Editor: Neovim(LunarVim)
  <br><br>
    Bar: Polybar
  <br><br>
    Notification Daemon: Dunst
  <br><br>
    Fetch: Bunnyfetch
  <br><br>
    App Launcher: Rofi
  <br><br>
    Shell: Fish
  <br><br>
    Compositor: Picom-Animations-Git
  <br><br>
    Widgets: EWW

# Install
Assuming you have yay as your AUR helper:
<br>
<code>yay -S git eww neovim pcmanfm bspwm sxhkd starship fish nerd-fonts-complete ttf-comic-mono-git sddm rofi polybar</code>
<br>
<br>
Installing the dotfiles:
<br>
<code>git clone https://github.com/Spaxly/bspwm-rice && cd bspwm-rice</code>
<br>
<code>cp -rf config/* ~/.config</code>
<br>
<code>cp -rf fonts/* ~/.fonts</code>

# Credits
Syndrizzle - for Spotify EWW widget
