pwsh

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; iwr https://raw.githubusercontent.com/sbilikepy/mas/main/script.ps1 -OutFile script.ps1; .\script.ps1
```

cmd

```cmd
curl -L -o script.ps1 https://raw.githubusercontent.com/sbilikepy/mas/main/script.ps1 && powershell -ExecutionPolicy Bypass -File .\script.ps1
```
