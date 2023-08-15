# PMW3360 breakout board

このリポジトリには、PIXART社製のPMW3360DM-T2QU光学式マウスセンサー用のBreakoutボードのデザインファイルが含まれています。

このキットは、トラックボール付きキーボード、マウス、トラックボールをDIYで自作するために使用できます。
レギュレーターが搭載されているので、5Vでも3.3Vでも使えます。

センサーチップはSENSOR側にあり、部品が実装されている側はLENS側です。センサーとピンヘッダはご自身でハンダ付けする必要があります。

基板サイズは28x32mm、M2ネジ用の取り付け穴はφ2.3mm、24x28mmです。
寸法図![](pmw3360dimension_ja.png)

Table 1. ピン番号
|1|2|3|4|5|6|7|8|
|-|-|-|-|-|-|-|-|
|CS|MISO|MOSI|SCLK|MOTION|N/C|VCC|GND|

### キットに含まれるもの
・PMW3360DM-T2QU　1個<br>
・LM19-LSI（LENS）1個<br>
・ブレイクアウトボード　1個<br>

### 別売ユニット
・トラックボール<br>
・ピンヘッダ<br>

### 設計データ
- [回路図](https://github.com/monkeypad/pmw3360-breakout/blob/main/pcb/pmw3360.pdf)

トラックボールキーボード、マウスを設計される際はクリアランスに注意してください。詳細はメーカーのDatasheetをご確認ください。
- [Datasheet](https://d3s5r33r268y59.cloudfront.net/datasheets/9604/2017-05-07-18-19-11/PMS0058-PMW3360DM-T2QU-DS-R1.50-26092016._20161202173741.pdf)

### 手順
1.SENSOR側の面にセンサーを搭載する
![](img/mount1.png)
2.LENS側の面をハンダづけする
![](img/mount2.png)
3.LENSのフィルムをピンセットで剥がす
![](img/mount3.png)
4.ピンヘッダをハンダづけして完了
![](img/mount4.png)
