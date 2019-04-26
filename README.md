## UTILITY TO CLONE RASPBERRY PI SD CARD


#### WHY IS IT REQUIRED TO CLONE SD CARD?

Pretested image can be cloned and shared. This way we can run same pretested image on multiple Raspberry Pi devices.

##### INSTALLATION STEP

    1. git clone https://github.com/vikilabs/rpi_cloner.git
    2. cd rpi_cloner
    3. ./install.sh


##### UNINSTALLATION STEP

    1. ./uninstall.sh


##### USAGE GUIDE
    
    $rpi_clone <sd card device name> <new_image_name>.img

    Example:

    $rpi_clone /dev/sdb rpi_image.img


##### REFERENCE 

I am using PiShrink script as part of this utility. Thanks to Drewsif.

GitHub: https://github.com/Drewsif/PiShrink 
