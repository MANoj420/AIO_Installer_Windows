# AIO_Installer_Windows
This Repo for AIO Windows Pakages.

1. Open powershell.exe with admin rights

```
Set-ExecutionPolicy AllSigned
```
```
Set-ExecutionPolicy Bypass -Scope Process
```
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
2. Keep Choco up-to-date
```
choco upgrade chocolatey
````


```
choco install -y  vlc 7zip ccleaner googlechrome ublockorigin-chrome adobereader jre8 vcredist-all python dogtail.dotnet3.5sp1 notepadplusplus.install teamviewer nvidia-display-driver qbittorrent megatools
```
