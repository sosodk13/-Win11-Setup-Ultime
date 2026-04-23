<h1 align="center">⚠️ EN CONSTRUCTION ⚠️</h1>
<h3 align="center">✨ Mon setup Windows 11 ✨</h3>

<p align="center">
Un guide complet pour ma custumisation windows 11 – de la YASB bar jusqu'a tout les petits tweaks qui font propre,  aesthetic, et productif
</p>


---

## 📑 Table of Contents

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
| Police                | [JetBrainsMono Nerd Font](https://github.com/ryanoasis/nerd-fonts/releases/latest/download/JetBrainsMono.zip) |


---

# ⚡ Détails


## 🦅 Windhawk

Windhawk vise a faire en sorte que la customisation des programmes Windows soit plus simple.

**⚙️ Installation:**  
tu peut suivre les étapes d'installation si dessous.
- Instale [**Windhawk**](https://windhawk.net/)   
- Copy the config file from [**here**](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/tree/main/Windhawk).
- Remove the codes from the advance section in **your** Windhawk mod and paste the one you just copied.
- Click **Save settings** for the changes to take effect.

---

## 🔍 Flow Launcher

Quick File Search & App Launcher for Windows

**⚙️ Installation:**  
tu peut suivre les étapes d'installation si dessous.
- Install [**Flow Launcher**](https://www.flowlauncher.com/).
- Download the theme file from [**here**](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/tree/main/Flow%20Launcher).
- Open Flow Launcher's Settings window, select **Appearance** on the sidebar, and click the "Open Theme Folder" button at the bottom.
- Move your theme file downloaded in Step 1 to this directory, and restart Flow Launcher.
- Again in Flow Launcher's Settings window, select **Appearance** on the sidebar, and select your Catppuccin flavor from the list of themes.
Installation guide was taken from [**here**](https://github.com/catppuccin/flow-launcher). Thanks :)

---

## 📁 ExplorerBlurMica
> [!NOTE] 
> A few people had said that they are getting bugs and crashes by using this, so I recommend to now use it and follow the windhawk method **here** (video will be added soon)

Add background Blur effect or Acrylic or Mica effect to explorer for win10 and win11

**⚙️ Installation:**  
tu peut suivre les étapes d'installation si dessous.
- Install [**ExplorerBlurMica**](https://github.com/Maplespe/ExplorerBlurMica/releases)   
- Copy the config file from [**here**](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/tree/main/File%20Explorer).
- For the next part, I'm using the default stuff so just follow the installation from [**here**](https://github.com/Maplespe/ExplorerBlurMica?tab=readme-ov-file#install) 

---

## 👾 Terminal + Fastfetch
> [!NOTE] 
> If you see **"execution of scripts is disabled on this system"**, don’t panic! Just open PowerShell as Administrator and run: 
> `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser -Force`
>
> Also if you notice that the ASCII art is not showing then try editing `"source": "C:/Users/%USERPROFILE%/.config/fastfetch/ascii.txt"` to `"source": "%USERPROFILE%/.config/fastfetch/ascii.txt"`. That should fix 
 
Fastfetch is a neofetch-like tool for fetching system information and displaying it in a visually appealing way. It is written mainly in C, with a focus on performance and customizability.

**⚙️ Installation:**  
Ytu peut suivre les étapes d'installation si dessous si tu veut que ton terminal ressemble 100% au mien.
- Install [**Fastfetch**](https://github.com/fastfetch-cli/fastfetch/releases) and I believe you already got the **Windows terminal** installed.
- Copy the config file for your Terminal [**here**](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/tree/main/Terminal), PowerShell profile from [**here**](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/tree/main/PowerShell) and Fastfetch config from [**here**](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/tree/main/Fastfetch)
- Remove the codes from the settings.json file in **your terminal** and paste the one you just copied from above. Do the same thing for your PowerShell profile.
- Create a **.config** *hidden* file in your C:\Users\%USERPROFILE% and create a folder called **fastfetch** inside. Copy the config and ascii code you just downloaded and paste it in that folder.
- Change the %USERPROFILE% from the config file in the fastfetch folder and the PowerShell profile with **your username**..
- Restart your terminal and your done. 

---

## 📝 VSCode
> [!NOTE] 
> This is just the base settings of my VSCode. Your(s) might look different than mine because I use many extensions along side that. I will try keeping my **Extensions** list up-to-date.

Visual Studio Code (VS Code) is a free, open-source code editor by Microsoft for building and debugging modern web and cloud applications.

**⚙️ Installation:**  
tu peut suivre les étapes d'installation si dessous.
- Install [**VSCode**](https://code.visualstudio.com/).
- Copy the config file:  
  `VSCode/Settings/settings.json → %APPDATA%\Code\User\settings.json`.  
- Restart **VSCode** for the changes to take effect.

**🔧 Extensions:**
- [Catppuccin pour VSCode](https://marketplace.visualstudio.com/items?itemName=Catppuccin.catppuccin-vsc) - 🦌 Soothing pastel theme for VSCode.
- [Catppuccin Icons pour VSCode](https://marketplace.visualstudio.com/items?itemName=Catppuccin.catppuccin-vsc-icons) - 🦊 Soothing pastel icon theme for VSCode.
- [VSCode Pets](https://marketplace.visualstudio.com/items?itemName=tonybaloney.vscode-pets) - Puts a pet in your code editor to boost productivity. 

---

## 🪟 AppName
> [!NOTE] 
> This setup is compatible with the latest version of **AppName**.

A short description about what the app/config does and why you’re using it.  
(Example: Minimal tiling window manager setup with custom keybindings and themes.)

**⚙️ Installation:**  
tu peut suivre les étapes d'installation si dessous.
- Install [**AppName**](https://appname-website.com/download)   
- Copy the config file:  
  `windots/.config/appname/config.file → %USERPROFILE%\.config\appname\config.file`  
- Restart **AppName** for the changes to take effect


---

### Extras
D'autre petits outils & tweaks que j'utilise.  
- [Wallpaper Engine](#)  
- [AutoHotKey Scripts](#)  
- [RoundedTB](#)  

---

