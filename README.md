# I No longer use this config everything is moved to [drdixit/windows-dotfiles](https://github.com/drdixit/windows-dotfiles)
# Windows Alacritty Configuration
## run powershell as admin
```powershell
New-Item -ItemType SymbolicLink -Path "$env:APPDATA\alacritty" -Target "$env:USERPROFILE\.config\alacritty"
```
or
```powershell
New-Item -ItemType SymbolicLink -Path "C:\Users\mail\AppData\Roaming\alacritty" -Target "C:\Users\mail\.config\alacritty"
```
