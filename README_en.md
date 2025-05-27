# IMX219 MIPI Adapter Board for Tang Mega 138K Pro Dock

[日本語版はこちら (README.md)](README.md)

## Overview

This is an adapter board which allows you to connect the camera module from the [Raspberry Pi Camera V2](https://raspberry-pi.ksyic.com/main/index/pdp.id/144/pdp.open/144) to the [Tang Mega 138K Pro Dock](https://wiki.sipeed.com/hardware/en/tang/tang-mega-138k/mega-138k-pro.html) by replacing the base board.

It enables the use of Sony's IMX219 sensor with Sipeed's (apparently proprietary) 24-pin MIPI connector.

## Board Images

Here is the adaptor board:

![3D view](images/3d_view.png)

Remove the camera module from the Raspberry Pi Camera V2 board, and attach it to this adapter board for use.

![3D view](images/pi_camera_v2.png)

The final assembled board is shown below.

![3D view](images/imx219_mipi24_photo.jpg)


## Data

Here is the schematic. (The PDF version is [here](imx219_mipi24/imx219_mipi24.pdf)):

![Schematic](imx219_mipi24/imx219_mipi24.svg)

Designed with [KiCAD](https://www.kicad.org/) version 9.0.0.

Prototypes were manufactured by JLCPCB's PCBA service.  Impedance control is based on the manufacturing specifications for "FR4-Standard TG 135-140" 4-layer boards from [JLCPCB](https://jlcpcb.com/).

At the time of manufacture, not all of the desired parts were available in inventory, so some unusual parts were used.  This will be changed in the next production run. 

The cable used is [05-24-A-0030-A-4-06-4-T](https://www.marutsu.co.jp/pc/i/46064636/), but this was purchased by mistake and is shorter than intended, so it has only been tested with this cable so far.


## Disclaimer

This design data is intended for use in experimental prototypes for research and development. The author assumes no responsibility for any damages arising from its use.

## License

This design data is provided under the [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/).

You are free to use it for personal or research purposes as long as you do not sell or distribute the manufactured boards.
For commercial manufacturing and sales, please contact the author for a separate license agreement.


## Author

Ryuji Fuchikami
r-fuchikami@rtc-lab.com
