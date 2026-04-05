<p align="center">
  <img width="256" height="256" alt="RYN_logo_mid" src="https://github.com/user-attachments/assets/e5ed52cf-2dcb-4237-ae50-0766d04d560b" />
</p>

Ryn is a cross-platform rhythm game, inspired by [osu! mania](https://github.com/ppy/osu), [Etterna](https://github.com/etternagame/etterna), [Stepmania](https://github.com/stepmania/stepmania) and [Dance Dance Revolution](https://en.wikipedia.org/wiki/Dance_Dance_Revolution). It is aimed at keyboard players, although a mobile version is set to release sometime in the future. The developement of the game is still in progress.

# Status
This project is under developement, but an alpha version has been released. This project will continue to evolve until all set goals will be reached.

# Downloading Ryn
If you would like to try out my game, head to the [Latest release](https://github.com/zoLovro/Rizumu/releases/tag/Release-0.1) and download the file for your operating system.

## Additional instructions for Linux users
If you are using a Linux machine, you will have to download ffmpeg into your root folder (preferably using a package manager).

### Arch Linux / Manjaro

```bash
sudo pacman -S ffmpeg
```

### Fedora

```bash
sudo dnf install https://download1.rpmfusion.org/free/fedora/rpmfusion-free-release-$(rpm -E %fedora).noarch.rpm
sudo dnf install ffmpeg
```

### Ubuntu

```bash
sudo apt update
sudo apt install ffmpeg
```

### Mint

```bash
sudo apt update
sudo apt install ffmpeg
```
If your distro is not on the list, use the appropriate package manager.


# Map importing
1. Launch the application and press the Play button (this creates the Assets directory)
2. Head to the [osu! beatmaps website](https://osu.ppy.sh/beatmapsets) and download any **mania** map
3. Move the .osz file into **Assets/Songs** and extract it 
4. Remove the .osz file
5. Head back into the game and enjoy!

A more modern way is still under developement.

## Licence
The code and framework for Rizumu are lincenced under the [MIT licence](https://opensource.org/license/MIT).
