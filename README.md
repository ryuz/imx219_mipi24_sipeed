# Tang Mega 138K Pro Dock 用 IMX219 MIPI 変換基板

[English version is here (README_en.md)](README_en.md)

## 概要

[Raspberry Pi Camera V2](https://raspberry-pi.ksyic.com/main/index/pdp.id/144/pdp.open/144) のベース基板を入れ替えて、Sipeed さんの [Tang Mega 138K Pro Dock](https://wiki.sipeed.com/hardware/en/tang/tang-mega-138k/mega-138k-pro.html) に繋ぐための変換基板です。

おそらく Sipeed さんの独自仕様と思われる 24pin の MIPI コネクタで Sonyさんの IMX219 センサーを利用可能にします。


## 変換基板のイメージ

下記のような変換基板です。

![3Dイメージ](images/3d_view.png)

Raspberry Pi Camera V2 カメラから、カメラモジュール部分を取り外して、この変換基板に取り付けることで、利用します。

![3Dイメージ](images/pi_camera_v2.png)

実際に取り付けたのが下記の写真です。

![3Dイメージ](images/imx219_mipi24_photo.jpg)


## 各種データ

回路図は下記の通りです(pdf版は[こちら](imx219_mipi24/imx219_mipi24.pdf))です。

![3Dイメージ](imx219_mipi24/imx219_mipi24.svg)

[KiCAD](https://www.kicad.org/) version 9.0.0 で設計しております。

[JLCPCB](https://jlcpcb.com/) さんの４層基板で「FR4-Standard TG 135-140」の製造仕様に合わせてインピーダンスコントロールしております。

手元での試作も JLCPCBさんの PCBA で行っており、たまたま在庫表示のあった部品を選定したこともあり、一部不思議な部品選定があるのはそのためです。

ケーブルは[05-24-A-0030-A-4-06-4-T](https://www.marutsu.co.jp/pc/i/46064636/)を使っておりますが、これは間違って短いものを購入してしまい、いまのところこれでしか試せておりません。


## 免責事項

本設計データは、研究開発用の試作実験に用するものであり、利用に際して発生した如何なる損害も作者は補償いたしませんので予めご了承ください。

## ライセンス(License)

本設計データは、[クリエイティブ・コモンズ 表示-非営利 4.0 国際 ライセンス](https://creativecommons.org/licenses/by-nc/4.0/deed.ja)の下で提供されています。

製造した本基板の販売や配布を行わない限りは、趣味や研究開発用途でご自由にお使いいただく事が出来ます。
また、商用に製造販売を希望される場合は、別途ライセンス契約を作者までご相談ください。


## 作者情報

渕上 竜司(Ryuji Fuchikami)
r-fuchikami@rtc-lab.com
