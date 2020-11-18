# apple-music-electron
![preview.png](https://raw.githubusercontent.com/17hoehbr/apple-music-electron/master/preview.png)
=======
A desktop client for Apple Music using Electron.

Initially created for Linux since iTunes is not available, but also compiled for Windows for those who find iTunes too bloated. Unlike iTunes this app should comply with Windows 10's Dark Mode.
# Install
Pre-compiled binaries available on the [release page](https://github.com/17hoehbr/apple-music-electron/releases).

Generic Linux:

  Use [AppImageLauncher](https://github.com/TheAssassin/AppImageLauncher) to install latest AppImage from [release page.](https://github.com/17hoehbr/apple-music-electron/releases)
  
  
Debian:

  Download latest deb [release](https://github.com/17hoehbr/apple-music-electron/releases)
  
  Navigate to download directory (ex. /home/USERNAME/Downloads)
  
  ```$ cd ~/Downloads```
  
  ```$ dpkg -i apple-music-electron_*.deb```
  
  
[Arch](https://aur.archlinux.org/packages/apple-music-electron/):

  ```$ yay -S apple-music-electron```
  
  
Windows:

  Download and run setup.exe
  
  
# Building from source
Requirements: YARN https://classic.yarnpkg.com/en/docs/install

1. Clone project

```$ git clone https://github.com/17hoehbr/apple-music-electron.git```

2. Navigate to folder 

```$ cd apple-music-electron```

3. Install dependencies

```$ yarn install```

4. Compile

```$ yarn dist```

Alternatively you can run the app directly from source using
```$ yarn start```

Additional outputs can be configured by modifying the target value in package.json. All options can be found here https://www.electron.build/configuration/linux

# Credits
Icon created by [Tristan Edwards](https://dribbble.com/tristanedwards) and used under the [CC Attribute license](https://creativecommons.org/licenses/by/3.0/). No modifications have been made.

DRM support is provided by a custom version of electron by [castlabs](https://github.com/castlabs/electron-releases/).

Used IsmaelMartinez' unofficial [teams-for-linux client](https://github.com/IsmaelMartinez/teams-for-linux) as a reference for package.json layout.
