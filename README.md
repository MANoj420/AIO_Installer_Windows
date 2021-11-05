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
