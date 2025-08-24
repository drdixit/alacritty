# Windows Alacritty Configuration
by default in windows it will look at `%APPDATA%\alacritty\alacritty.toml`<br>
but below command make it `~/.config/alacritty`
## 🛠️ Set Environment Variables Permanently (User Scope)
Open Command Prompt or PowerShell (no admin rights needed) and run:
```powershell
setx HOME "%USERPROFILE%"
setx XDG_CONFIG_HOME "%USERPROFILE%\.config"
```

## 🛡️ Set Environment Variables Permanently (System-Wide) (Not Recommended its just for my reference)
"**/M** set system wide"<br>
To apply variables for all users, run Command Prompt or PowerShell as Administrator and add the /M flag:
```
setx HOME "%USERPROFILE%" /M
setx XDG_CONFIG_HOME "%USERPROFILE%\.config" /M
```
