# Linux

## VS Code
```powershell
sudo apt update
```

```powershell
sudo apt install wget gpg -y
```

```powershell
wget -qO- https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > packages.microsoft.gpg
```


```powershell
sudo install -o root -g root -m 644 packages.microsoft.gpg /usr/share/keyrings/
```

```powershell
sudo sh -c 'echo "deb [arch=amd64 signed-by=/usr/share/keyrings/packages.microsoft.gpg] \
https://packages.microsoft.com/repos/code stable main" > /etc/apt/sources.list.d/vscode.list'
```

```powershell
sudo apt update
```

```powershell
sudo apt install code
```

## Git
```powershell
sudo apt update
```

```powershell
sudo apt install git
```

```powershell
sudo apt install gh
```

```powershell
gh auth login
```


## Jetbrains tool app
```powershell
wget -c https://download.jetbrains.com/toolbox/jetbrains-toolbox-1.28.1.15219.tar.gz
```

```powershell
tar -xvzf jetbrains-toolbox-*.tar.gz
```

```powershell
cd jetbrains-toolbox-*/
./jetbrains-toolboxs
```

## Set image
```powershell
wget -O ~/Pictures/myimage.jpg "https://c4.wallpaperflare.com/wallpaper/586/603/742/minimalism-4k-for-mac-desktop-wallpaper-preview.jpg"
```

```powershell
gsettings set org.cinnamon.desktop.background picture-uri "file:///home/$(whoami)/Pictures/myimage.jpg"
```

## SFML/C+++ Tools
```powershell
sudo apt install libx11-dev libxrandr-dev libxi-dev libxext-dev libxinerama-dev libxcursor-dev
```

```powershell
sudo apt install cmake
```

```powershell
sudo apt install build-essential cmake libx11-dev libxext-dev libgl1-mesa-dev libglu1-mesa-dev
```

### Connect docker desktop ui with core

```powershell
sudo usermod -aG docker $USER
```

- start using only "docker"


sudo apt install libudev-dev
sudo apt install libopenal-dev
sudo apt update
sudo apt install build-essential cmake git \
libx11-dev libxext-dev libxrandr-dev libxinerama-dev libxcursor-dev \
libgl1-mesa-dev libglu1-mesa-dev \
libudev-dev libopenal-dev libvorbis-dev libflac-dev \
libfreetype6-dev




