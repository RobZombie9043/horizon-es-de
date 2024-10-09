# Horizon (ES-DE)
A clean and minimal theme for ES-DE

## **Preview**
| System View |
|----|
| ![Screenshot_20240929-231304](https://github.com/user-attachments/assets/949f24ac-f85b-4ed8-b23d-badf8fde5cdc) |


| Gamelist - List | Gamelist - Grid | Gamelist - Carousel |
|----|----|----|
| ![Screenshot_20240929-231327](https://github.com/user-attachments/assets/10bbdeab-a1e8-4fc2-be74-cc496ff38543) | ![Screenshot_20240929-231356](https://github.com/user-attachments/assets/e5e0bd77-99f6-4dd9-9c7a-18998d4b61a3) | ![Screenshot_20240929-231449](https://github.com/user-attachments/assets/643ad7c8-1995-461d-8e38-a5319d9e7510) |


## **Configuration Options**

- This theme has a simple set of options that can be changed directly from the UI Settings menu of ES-DE
  
- `Theme Variant` - sets the theme variant adjusting the gamelist view. Detailed variants include additional game description metadata.
   - `List: Detailed`
   - `List: Basic`
   - `Grid (Small): Detailed`
   - `Grid (Small): Basic`
   - `Grid (Medium): Detailed`
   - `Grid (Medium): Basic`
   - `Grid (Large): Detailed`
   - `Grid (Large): Basic`
   - `Carousel`
     
- `Font Size` - enables you to change the size of the fonts displayed in the theme.
   - `Medium`
   - `Large`
   - `Extra Large`
     
- `Theme Aspect Ratio` - sets the aspect ratio the theme will render at. If needed, this can be changed to match the aspect ratio of your screen (though it should happen automatically).
   - `16:9`
   - `16:10`
   - `3:2`
   - `4:3`
   - `5:4`
   - `19.5:9`
   - `21:9`
   - `32:9`
   - `1:1`
 
- `Color Scheme` - sets the color scheme for the theme which allows the use of custom artwork. Refer to the theme customization section for details on adding custom artwork.
   - `Default`
   - `Custom`
 
## **Configuration Options**

This theme allows customizations to the carousel artwork without the need to edit the source XML. This enables you to change the look of the theme and still retain any changes when the root theme is updated.

- Create a folder called `theme-customizations` in the main Horizon theme folder and then create a subfolder named `artwork` resulting in a folder structure `~ES-DE/themes/horizon-es-de/theme-customizations/artwork/`
- Copy your custom carousel images to that `artwork` folder
- They should be named `${system.theme}.jpg`, For example for `snes` you would create an image called `snes.jpg`
  - Note that custom images only need to be supplied for the systems to be customized and the default system image will be used for any other systems.
  - The carousel images use an aspect ratio of 0.65:1 so if images that are provided use a different aspect ratio to this they will be cropped which may cut off parts of the image and not look good.
- Change the theme color scheme to `Custom` and the artwork from the custom folder will be used.

- The original theme artwork can be found [here](https://www.mediafire.com/file/6zf85zqfydlhzge/theme-customizations.zip/file) and can be used by unzipping the included theme-customization folder to the theme folder.

## **Acknowledgements**

Includes system artwork from the neoretrō theme by [Valentin MEZIN](https://github.com/valsou), shinretro theme by [TigraTT-Driver](https://github.com/TigraTT-Driver) and Alekfull theme by [fagnerpc](https://github.com/fagnerpc)
Android apps artwork - (https://wallpaperswide.com/android_robot_listening_to_music-wallpapers.html)  
Arcadia artwork - (https://arcadia.fun/)  
Emulators artwork - (https://wallpapers.com)  
