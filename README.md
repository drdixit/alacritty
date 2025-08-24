# Windows Alacritty Configuration
## run powershell as admin
```
New-Item -ItemType SymbolicLink -Path "$env:USERPROFILE\.config\alacritty" -Target "$env:APPDATA\alacritty"
```
or
```
New-Item -ItemType SymbolicLink -Path "C:\Users\mail\.config\alacritty" -Target "C:\Users\mail\AppData\Roaming\alacritty"
```
