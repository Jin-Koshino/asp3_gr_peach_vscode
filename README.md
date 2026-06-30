# asp3_gr_peach_vscode
TOPPERS/ASP3カーネルとアプリをVisual Studio Codeで開発可能にするための環境です．
本リポジトリは，[asp3_gr_peach_vscode](https://github.com/takasehideki/asp3_gr_peach_vscode)を Jin-Koshinoがforkしたものです．

下記リポジトリを大いに参考にしました．ここで深く感謝いたします．  
[Azure IoT Hub with TOPPERS/ASP3](https://github.com/h7ga40/azure_iot_hub_peach)

## ターゲット

* マイコンボード：[GR-PEACH](https://www.core.co.jp/product/m2m/gr-peach/index.html)
* [TOPPERS/ASP3カーネル ARM簡易パッケージ 3.7.2 (リリース日：2026-05-18)](http://toppers.jp/asp3-e-download.html)
* ホストPC環境
  * Windows 10 Home
* 開発ツール
  * IDE：[Visual Studio Code](https://code.visualstudio.com) (1.126.0)
  * クロスコンパイラ：[arm-none-eabi Version 9-2020-q2-update 9.3.1 20200408 (release)](https://developer.arm.com/downloads/-/gnu-rm#panel4a)
  * デバッガ（動作未確認）：[OpenOCD 0.10.0-12-20190422](https://github.com/gnu-mcu-eclipse/openocd/releases/tag/v0.10.0-12-20190422)

## オリジナルからの変更点

[TOPPERS/ASP3カーネル GR-PEACH簡易パッケージ](http://toppers.jp/asp3-e-download.html)からの変更点を列挙します
* [apps/sample1/Makefile](./apps/sample1/Makefile) 74行名: オブジェクトファイル名の拡張子を elf に変更（OBJEXT = elf）

## 使用方法

下記のQiita記事をご参照ください

* [VSCodeでTOPPERSアプリをビルド＆実行する](https://qiita.com/takasehideki/items/fa0a1a6567a22f469515)

## ライセンス等

[TOPPERSライセンス](http://toppers.jp/license.html)に従います．  
[オリジナルのREADME.txt](./asp3/README.txt)も参考にしてください．
