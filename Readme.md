# Polybar

- Link to [polybar](https://github.com/polybar/polybar)
- Install: just clone the repo into ~/.config
  - It will create a ~/.config/polybar directory with the config
  
## A better way...

- We can install theme: https://github.com/adi1090x/polybar-themes
  - Just add `MONITOR="$m" bash ~/.config/polybar/launch.sh --blocks` at the end of [herbstluftwm](https://github.com/gthvn1/herbstluftwm)
- To be able to use multi monitors I modified the **monitor** variable in config.ini of the theme: `monitor = ${env:MONITOR:}` 
