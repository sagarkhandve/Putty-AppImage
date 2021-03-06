[![License](https://img.shields.io/badge/License-MIT-blue)](#license "Go to license section")

# Putty - AppImage

![Putty](https://user-images.githubusercontent.com/90393971/133889722-de4ee9af-5d8b-4272-b75b-d367669c5af9.png)

1. Clone this repository and `cd` into it.
   ```shell
   wget https://github.com/sagarkhandve/Putty/releases/download/v0.76/Putty_x86_64.AppImage
   cd Putty/
   chmod +x Putty_x86_64.AppImage
   ```
2. Run

   ```shell
   ./Putty_x86_64.AppImage
   ```
   
### A configuration for [pkg2appimage](https://github.com/AppImage/pkg2appimage) to build Putty in AppImage form.

## How to use it?

1. Clone this repository and `cd` into it.
    ```shell
    git clone https://github.com/sagarkhandve/Putty-AppImage.git
    cd Putty/
    ```
2. Download pkg2appimage tool and make it executable.
   ```shell
   wget https://github.com/AppImage/pkg2appimage/raw/master/pkg2appimage
   chmod +x pkg2appimage
   ```
3. Build it:

   ```shell
   ./pkg2appimage Putty.yml
   ```

4. After a short break you should get an executable inside `out/` directory.

