<h1 align="center">⚠️ EN CONSTRUCTION ⚠️</h1>
<h3 align="center">✨ Mon setup Windows 11 ✨</h3>

<p align="center">
Un guide complet pour ma custumisation windows 11 – de la YASB bar jusqu'a tout les petits tweaks qui font propre,  aesthetic, et productif
</p>


---

## 📑 Table de contenu

| 📚 Description      | ✨ App |
|---------------------|------------|
| Bar de satut        | [YASB](#yasb) |
| Manager Windows     | [GlazeWM](#glazewm) |
| App Launcher        | [Flow Launcher](#flowlauncher) |
| barre des taches    | [Windhawk](#windhawk) |
| Editeur de texte    | [VSCode](#vscode) |
| Terminal            | [Windows Terminal](#windows-terminal) |
| Navigatuer          | [Brave](#brave) |
| Fetch du sytème     | [Fastfetch](#Fastfetch) |   
| Prompt powershell   | [Oh My Posh](#ohmyposh) |
| visualiseur musique | [Cava](#cava) |
| Musique             | [Spotify](#spotify) | 
| enregistrement vids | [OBS Studio](#obsstudio) |
| Mod file explorer   | [ExplorerBlurMica](#ExplorerBlurMica) |

Autre

| 📚 Description | ✨ App |
|---------------------|------------|
| Couleur             | [Catppuccin Mocha](https://catppuccin.com) |
| Police              | [JetBrainsMono Nerd Font](https://github.com/ryanoasis/nerd-fonts/releases/latest/download/JetBrainsMono.zip) |


---

# ⚡ Détails


## 🦅 Windhawk

Windhawk facilite la personnalisation des programmes Windows.

**⚙️ Installation:**  
tu peut suivre les étapes d'installation si dessous.
- Téléchargee [**Windhawk**](https://windhawk.net/)   
- Lance **Windhawk** et cherche le mod que tu veut 
- Télécharge le
- Clique sur **Save settings** pour que les changements face effets 

## 📁 ExplorerBlurMica
> [!NOTE] 
> Plusieurs personnes ont signalé des bugs et des crashs en l'utilisant donc je recommande maintenant d'utiliser la méthode Windhawk **ici** (vidéo à venir).

Ajoute un effet Flou, Acrylique ou Mica à l'explorateur de fichiers pour Windows 10 et 11.

**⚙️ Installation:**  
tu peut suivre les étapes d'installation si dessous.
- Télécharge [**ExplorerBlurMica**](https://github.com/Maplespe/ExplorerBlurMica/releases) 
-Execute le fichier télécharge
- Pour la suite, j'utilise les paramètres par défaut donc suis simplement l'installation depuis [**Ici**](https://github.com/Maplespe/ExplorerBlurMica?tab=readme-ov-file#install) 

---

## 👾 Terminal + Fastfetch
> [!NOTE] 
> Si tu voit **"execution of scripts is disabled on this system"**, pas de panique ! Ouvre simplement PowerShell en tant qu'Administrateur et exécute : 
> `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser -Force`
>
> Si l'ASCII ne s'affiche pas, essaie de remplacer : `"source": "C:/Users/%USERPROFILE%/.config/fastfetch/ascii.txt"` par `"source": "%USERPROFILE%/.config/fastfetch/ascii.txt"`. Ça devrait régler le problème.


Fastfetch est un outil similaire à neofetch pour récupérer et afficher les informations système de manière visuelle. Il est principalement écrit en C, avec une importante fixation sur les performances et la personnalisabilité.
**⚙️ Installation:**  
tu peut suivre les étapes d'installation si dessous si tu veut que ton terminal ressemble 100% au mien.
- Télécharge [**Fastfetch**](https://github.com/fastfetch-cli/fastfetch/releases) le **Windows terminal** est normalement déjà installé.
- Copie le fichier de config du terminal [**Ici**](https://github.com/sosodk13/-Win11-Setup-Ultime/tree/main/Terminal)), le profil PowerShell [**Ici**](https://github.com/sosodk13/-Win11-Setup-Ultime/tree/main/PowerShell) et la config Fastfetch [**Ici**]((https://github.com/sosodk13/-Win11-Setup-Ultime/tree/main/Fastfetch))
- Supprime le contenu du fichier settings.json de **ton terminal** et colle celui que tu viens de copier. Fais pareil pour ton profil PowerShell.
- Crée un fichier **.config** *caché* dans C:\Users\%USERPROFILE% et crée un dossier **fastfetch** à l'intérieur. Colle la config et l'ASCII que tu viens de télécharger dans ce dossier.
-Remplace le **%USERPROFILE%** dans le fichier de config du dossier fastfetch et dans le profil PowerShell par ton **nom d'utilisateur**.
- Redémarre ton terminal et c'est bon. 

---

## 📝 VSCode
> [!NOTE] 
> Ce sont juste les paramètres de base de mon VSCode. Le tien pourrait être différent du mien car j'utilise de nombreuses extensions en plus. J'essaierai de garder ma liste d'**extensions** à jour.
Visual Studio Code (VS Code) est un éditeur de code gratuit et open-source par Microsoft pour créer et déboguer des applications web et cloud modernes.

**⚙️ Installation:**  
tu peut suivre les étapes d'installation si dessous.
- Télécharge [**VSCode**](https://code.visualstudio.com/).
- Copie le fichier de config:  
  `VSCode/Settings/settings.json → %APPDATA%\Code\User\settings.json`.  
- Redémare **VSCode** et c'est bon !
**🔧 Extensions:**
- [Catppuccin pour VSCode](https://marketplace.visualstudio.com/items?itemName=Catppuccin.catppuccin-vsc) - 🦌 Thème pastel propre pour VSCode.
- [Catppuccin Icons pour VSCode](https://marketplace.visualstudio.com/items?itemName=Catppuccin.catppuccin-vsc-icons) - 🦊 Thème d'icônes pastel propre pour VSCode.
- [VSCode Pets](https://marketplace.visualstudio.com/items?itemName=tonybaloney.vscode-pets) - Met un animal de compagnie dans ton éditeur pour booster la productivité.

---

## 🪟 AppName
> [!NOTE] 
> Ce setup est compatible avec la dernière version de **AppName**.

Une courte description de ce que fait l'app/config et pourquoi tu l'utilises.
(Example: Minimal tiling window manager setup with custom keybindings and themes.)

**⚙️ Installation:**  
tu peut suivre les étapes d'installation si dessous.
- Télécharge [**AppName**](https://appname-website.com/download)   
-  Copie le fichier de config:  
  `windots/.config/appname/config.file → %USERPROFILE%\.config\appname\config.file`  
- Redémare **AppName** et c'est bon !


---

### Extras
D'autre petits outils & tweaks que j'utilise.  
- [Wallpaper Engine](#)  
- [AutoHotKey Scripts](#)  
- [RoundedTB](#)  

---

