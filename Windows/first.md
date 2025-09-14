# Chocolatey Setup and Software Installation

Open **PowerShell as Administrator** and run the following commands!:

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force
```

```powerhsell
iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

# 2. Install software
```powershell
choco install googlechrome -y
```

```powershell
choco install nodejs-lts -y
```

```powershell
choco install git -y
choco install gh -y
```

```powershell
 choco install nuget.commandline -y
```

```powershell
choco install docker-desktop -y
```


