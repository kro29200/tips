# tips
**ZSH / Oh My Zsh / Powerline Installation procedure** 

Install Zsh

`sudo apt-get install zsh`

Install Zsh

`sudo apt-get install powerline`

Install powerline fonts

`wget https://github.com/Lokaltog/powerline/raw/develop/font/PowerlineSymbols.otf https://github.com/Lokaltog/powerline/raw/develop/font/10-powerline-symbols.conf`

`mkdir -p ~/.fonts/ && mv PowerlineSymbols.otf ~/.fonts/`

`fc-cache -vf ~/.fonts`

`mkdir -p ~/.config/fontconfig/conf.d/ && mv 10-powerline-symbols.conf ~/.config/fontconfig/conf.d/`


**Terminix : Custom HeaderBar size**

Edit : `~/.config/gtk-3.0/gtk.css`


`.header-bar
 {
     padding-top: 1.5px;
     padding-bottom: 1.5px;
 }`

 `.header-bar .button
 {
     padding: 3px;
     padding-left: 7px;
     padding-right: 7px;
 }`

 `.header-bar .button.titlebutton
 {
     padding: 3px;
 }`