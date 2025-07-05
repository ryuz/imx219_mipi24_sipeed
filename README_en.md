# IMX219 MIPI Adapter Board for Tang Mega 138K Pro Dock

[日本語版はこちら (README.md)](README.md)

## Overview

This is an adapter board that allows you to connect the camera module from the [Raspberry Pi Camera V2](https://raspberry-pi.ksyic.com/main/index/pdp.id/144/pdp.open/144) to the [Tang Mega 138K Pro Dock](https://wiki.sipeed.com/hardware/en/tang/tang-mega-138k/mega-138k-pro.html) by replacing the base board.

It enables the use of Sony's IMX219 sensor with a 24-pin MIPI connector, which appears to be Sipeed's proprietary specification.


## Board Images

The adapter board looks like this:

![3D view](images/3d_view.png)

Remove the camera module from the Raspberry Pi Camera V2 and attach it to this adapter board for use.

![3D view](images/pi_camera_v2.png)

The actual assembled board is shown below.

![3D view](images/imx219_mipi24_photo.jpg)


## Data

The schematic is as follows (PDF version is [here](imx219_mipi24/imx219_mipi24.pdf)):

![Schematic](imx219_mipi24/imx219_mipi24.svg)

Designed with [KiCAD](https://www.kicad.org/) version 9.0.0.

Impedance control is based on the manufacturing specifications for "FR4-Standard TG 135-140" 4-layer boards from [JLCPCB](https://jlcpcb.com/).

Prototyping was also done with JLCPCB's PCBA service. Some components, such as oscillators, may be discontinued parts because they were selected from those in stock at the time. If you manufacture this board yourself, please select alternative or compatible parts as needed.

The cables tested are [05-24-A-0030-A-4-06-4-T](https://www.digikey.jp/ja/products/detail/gct/05-24-D-0030-A-4-06-4-T/21266592) and [05-24-A-0152-A-4-06-4-T](https://www.digikey.jp/ja/products/detail/gct/05-24-A-0152-A-4-06-4-T/21266890).


## Disclaimer

This design data is intended for use in experimental prototypes for research and development. The author assumes no responsibility for any damages arising from its use.

## License

This design data is provided under the [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/).

You are free to use it for personal or research purposes as long as you do not sell or distribute the manufactured boards.
For commercial manufacturing and sales, please contact the author for a separate license agreement.


## Author

Ryuji Fuchikami
[Real-Time Computing Lab](https://rtc-lab.com/)
