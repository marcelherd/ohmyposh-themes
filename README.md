# ohmyposh-themes

```powershell
Install-Module PSReadLine -Force

notepad $profile

oh-my-posh init pwsh --config "https://raw.githubusercontent.com/marcelherd/ohmyposh-themes/main/M365Princess-modified.omp.json" | Invoke-Expression
Set-PSReadLineOption -PredictionSource History
Set-PSReadLineOption -PredictionViewStyle ListView
```
