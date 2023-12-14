# wsl-installation
my personal guide for wsl (Ubuntu 20.04 LTS) instalation


Ativar itens windows

Baixar o ubuntu da Microsoft Store

Iniciar ubuntu

Instalar ZSH, OhMyZsh
    
    https://marcelosena.com/como-instalar-o-shell-zsh-oh-my-zsh-tema-e-plugins/

ZSH_THEME="jonathan"

plugins=(
  git
  zsh-history-substring-search
  zsh-syntax-highlighting
  zsh-autosuggestions
)


Instalar NODE
 Não usar no vscode
    
    https://docs.microsoft.com/en-us/windows/dev-environment/javascript/nodejs-on-wsl

Instalar MYSQL
 PASS LEVEL 0

    https://www.digitalocean.com/community/tutorials/how-to-install-mysql-on-ubuntu-20-04

GRANT ALL PRIVILEGES ON *.* TO 'username'@'localhost';


Update Python

    https://cloudbytes.dev/snippets/upgrade-python-to-latest-version-on-ubuntu-linux
    
Configurando GIT
  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"
  
  https://devblogs.microsoft.com/commandline/sharing-ssh-keys-between-windows-and-wsl-2/


Cisco AnyConnect
  https://dev.to/tiim/fix-network-connectivity-in-wsl2-with-cisco-anyconnect-vpn-4bhk

