Primeira coisa para voce melhorar o lauout do seu ubuntu.

Intalar o Gnome-tweak-tool

```DOS
    sudo apt-get install gnome-tweak-tool
```

Depois escolha um tema de sua escolha, estou utilizando este: 

[Sweet Dark](https://www.gnome-look.org/p/1253385/)

Escolher a opcao - Sweet-Dark.tarxz

Criar na home de usuario a pasta themes:

```DOS
    mkdir ~/.themes 
```

Incluir os arquivos do tema nas pastas ~/.themes

Ir nos ajustes e selecionar o tema

```DOS
    mkdir ~/.icons 
```

Escolha um tema de icones, estou utilizando este: 


[Papirus Dark](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme)

Para baixar este tema de icon:

Instale PPA:

```
    sudo add-apt-repository ppa:papirus/papirus
    sudo apt-get update
    sudo apt-get install papirus-icon-theme
```

Instalar o papirus:

```
    wget -qO- https://git.io/papirus-icon-theme-install | DESTDIR="$HOME/.icons" sh
```

Agora vamos instalar algumas coisas para mudar o visual:

Instale a extensao do gnome, informada no site de qualquer um dos pacotes abaixo.

Instalar:

- dash-to-dock

- dynamic-panel-transparency

- hide-activities-button

- openweather

- pixel-saver

- remove-app-menu

- remove-dropdown-arrows

- sound-output-device-chooser

- status-area-horizontal-spacing

- spotify-label

- user-themes

- caffeine

Dica: Procure o nome do pacode + gnome no google, primeiro link.

Dica de wallpaper que combina com o tema:

[https://wallpapercave.com/download/4k-pc-wallpapers-wp4676582]