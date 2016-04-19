# Gnome Random Wallpaper
Basic script to randomly pick an image from a folder an set it as wallpaper.
Works on Gnome environment

Usage :
  `change_wallpaper FOLDER`

Crontab : 
  `* */6   *   *   * export DISPLAY=:0 && /usr/local/bin/change_wallpaper /home/tdy/Images/Wallpapers/ 3>&1 1>> /dev/null 2>&1`
