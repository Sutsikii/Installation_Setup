# Installation Setup

Logiciel utilisés :   
-Visual Studio Code  
-Terminal (Windows)  
-Wampserver  


## Chemin des fichiers

Profil utilisateur powershell : .config/powershell/user_profil.ps1  
Mettre par défaut l'utilisateur powershell : code $PROFILE.CurrentUserCurrentHost | Si l'éditeur ne permet pas d'enregistrer par manque de droit : C:\users\users\Documents\Powershell 

## Installation du Terminal + Customisation

-Télécharger le Terminal sur le Microsoft Store
-Installer la font : Hack NF de Nerds Font
-Installation de Powershell téléchargeable sur le Microsoft Store
-Activer les affichages acryliques ( Fond écran + Tabs )

## Installation Logiciel

-Installation de Git : winget install -e --id Git.Git
-Installation de Scoop : iwr -useb get.scoop.sh | iex
                        scoop install curl sudo jq
-Installation de neovim : scoop install neovim gcc 

