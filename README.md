# Monitor brightness
Script to change monitor brightness from terminal

### Why I created this script
I adopted I3wm on my Arch and decided to create a script that controlled the screen brightness.

### How to use
Need the package: xorg-xrandr

I created a scripts folder in `$HOME/` put the scripts inside, then added it to `$PATH`, then went to `$HOME/.config/i3/config` and added the lines:

`bindsym XF86MonBrightnessUp exec lightup`

`bindsym XF86MonBrightnessUp exec lightdown`



# Brilho do monitor
Script para alterar o brilho do monitor do terminal

### Por que criei este script
Adotei o I3wm no meu Arch e resolvi criar um script que controlasse o brilho da tela.

### Como usar
Precisa do pacote: xorg-xrandr

Criei uma pasta de scripts em `$HOME/` coloquei os scripts dentro, depois adicionei em `$PATH`, depois fui em `$HOME/.config/i3/config` e adicionei as linhas:

`bindsym XF86MonBrightnessUp exec lightup`

`bindsym XF86MonBrightnessUp exec lightdown`
