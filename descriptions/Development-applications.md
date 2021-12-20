# Development applications
- Git
- Postman
- JRE
- Eclipse
- Tor
- Git Extensions
- Oracle Virtual Box
- VMWare Workstation Player
- NG Remote
- OpenVPN
- Cisco AnyConnect VPN Client
- MS Office
- WSL2
- ConEmu
  - Install Dracula theme
  - Set [Nerd Font Caskaydia Cove Nerd](https://www.nerdfonts.com/) font
  - Create <code>~/.config/git/git-prompt.sh</code> and copy from <code>FANCY BASH PROMPT SCRIPT</code> to <code>EOF</code> from <a href="https://github.com/LuckyRads/Linux-Configuration/blob/main/configs/.bashrc">.bashrc</a>
  - Search for <code>TRIANGLE</code> in <code>.bashrc</code> file
  - Change triangle unicode symbol code to pasted triangle symbol from Linux machine
- Visual Studio Code
  - Used extensions are listed in <a href="https://github.com/LuckyRads/Linux-Configuration/blob/main/scripts/configure-vscode.sh">Linux VSCode config script</a>
  - Copy configuration from <a href="https://github.com/LuckyRads/Linux-Configuration/blob/main/configs/VSCode_settings.json">VSCode settings file</a> (includes Vim settings and powerline symbol supporting font)
- Windows Terminal
  - Install Dracula theme (from the internet)
  - Install [Nerd Font Caskaydia Cove Nerd](https://www.nerdfonts.com/) with power glyphs
  - Set <code>CaskaydiaCove Nerd Font</code> font to all profiles
  - Split horizontally shortcut to <code>ctrl + shift + o</code>
  - Split vertically shortcut to <code>ctrl + shift + e</code>
  - Fancy powershell:
    - <code>Install-Module posh-git -Scope CurrentUser</code>
    - <code>Install-Module oh-my-posh -Scope CurrentUser</code>
    - <code>Install-Module -Name PSReadLine -AllowPrerelease -Scope CurrentUser -Force -SkipPublisherCheck</code>
    - <code>Install-Module -Name Terminal-Icons -Repository PSGallery</code>
    - Run <code>notepad $PROFILE</code> in PS
    - Add this to the file: 
    <p>Import-Module posh-git</p>
    <p>Import-Module oh-my-posh</p>
    <p>Set-PoshPrompt -Theme powerlevel10k_rainbow</p>
    <p>Import-Module -Name Terminal-Icons</p>
    <p>Set-PSReadlineKeyHandler -Key Tab -Function Complete</p>
- Powershell
  - Chocolatey package manager
    - Install gsudo (from administrator prompt)
    <code>choco install gsudo</code>
