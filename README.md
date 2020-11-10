# DOTFILES FEDORA

Configuraciones personales en Fedora 33

BSPwm con Polybar y Rofi menu.


<img src="https://raw.githubusercontent.com/mxhectorvega/dotfilesfedora/main/screenshot.png" />


**Configuracion**

Clonar y copiar los archivos de configuracion:

```
git clone https://github.com/mxhectorvega/dotfilesfedora

cp -R ~/dotfiles/.config/* ~/.config

cp ~/dotfiles/.config/.Xresources ~/.Xresources
```


Crear el archivo `.xinitrc` y agregarle la linea `exec bspwm`:

```
vim .xinitrc
```


Otorgar permisos de ejecucion a los archivos:

```
chmod +x .config/bspwm/bspwmrc
chmod +x .xinitrc
```


**Dependencias**

```
sudo dnf install xterm bspwm sxhkd mpd mpc ranger nvim pcmanfm feh pip37 python37 mntui intel_xbacklight 

pip install pywal
```

**Temas**

```
pkg install papirus-icon-theme materia-gtk-theme
```


**Grupo telegram:**

https://t.me/fedoralinuxes

**Canal de tips:**

https://t.me/fedora_tips

**Creditos:**

@mxhectorvega @DonatelloSanz 
