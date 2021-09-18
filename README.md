# Putty - AppImage

![Putty](https://user-images.githubusercontent.com/90393971/133889722-de4ee9af-5d8b-4272-b75b-d367669c5af9.png)

1. Clone this repository and `cd` into it.
   ```shell
   git clone https://github.com/AppImage/sagarkhandve/Putty.git
   cd Putty/
   chmod +x Putty.AppImage
   ```
2. Run

   ```shell
   ./Putty.AppImage
   ```
   
### A configuration for [pkg2appimage](https://github.com/AppImage/pkg2appimage) to build Putty in AppImage form.

## How to use it?

1. Clone this repository and `cd` into it.
    ```shell
    git clone https://github.com/sagarkhandve/Putty.git
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

