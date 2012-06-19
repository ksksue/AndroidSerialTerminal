USB Serial Terminal for Android
=====

※最新バージョンは
[Android USB Serial Terminal Lite](https://github.com/ksksue/Android-USB-Serial-Monitor-Lite "Android USB Serial Monitor Lite")
で管理しています。

---
<b>！注意！Android 3.1以上であってもUSB Host APIを備えている機種でしか使用できません。</b><br>
例えば、docomo製のGalaxy Nexus(Android 4.x系)には6月のアップデートまでUSB Host APIが備わっていませんでした。<br>
<br>
<b>USB Host APIの確認の仕方</b><br>
お使いのAndroid端末がUSB Host APIに対応しているかどうかは<br>
このアプリでUSBデバイスが表示されるかをチェックしてください。<br>
[USB Host Viewer](https://play.google.com/store/apps/details?id=com.synchack.android.usbhostviewer "USB Host Viewer")<br>
Android端末とUSBデバイスを繋いだ時、このアプリでUSBデバイスがリストアップされない場合は<br>
USB Host APIに対応していない可能性があります。

---

特徴
---
- FTDI社製のUSBシリアル変換チップに対応
- Androidのルート権限を取る必要はなし
- ボーレート、データビット、パリティ、ストップビット、フロー制御の設定可
- 文字、16進数、10進数表示を切り替え
- 改行コード（CR ／ LF ／ CF＋LF）の選択可
- ADKのようにマイコン側に電源は必要なく、USBケーブルから電源供給
- Android のバージョンは3.1以上必須

[FTDriver](https://github.com/ksksue/FTDriver "FTDriver")が別途必要です。


接続例
----
<b>Arduino NanoとAndroidを繋げる場合</b><br>
USBポートを直接Android端末へ繋げます。<br>
![Android-Nano](https://lh3.googleusercontent.com/-CYv_iILw_wo/T-CxNRHlXKI/AAAAAAAACa4/_Cbbp1o0xZ8/s800/Android-Arduino%2520Nano.png "Android-Nano")<br>
別途Android端末と繋ぐためのUSBケーブルが必要です。<br>
<br>
<br>

<b>Arduino UNOとAndroidを繋げる場合</b><br>
Android端末とArduinoの間に5V USBシリアル変換モジュールを接続します。<br>
![Android-Uno](https://lh3.googleusercontent.com/-Ej5c8hTMOOI/T-C7zX-x_NI/AAAAAAAACbQ/okoq1uGWxRo/s800/Android-Arduino%2520UNO.png "Android-Uno")<br>
別途Android端末と繋ぐためのUSBケーブルが必要です。<br>
<br>
<b>5V USBシリアル変換モジュール</b>
- 秋月 [FT232RL USBシリアル変換モジュール](http://akizukidenshi.com/catalog/g/gK-01977/ "FT232RL USBシリアル変換モジュール") 5V,3.3V両方対応
- Sparkfun [FT232RL搭載小型USB-シリアルアダプタ 5V](http://www.switch-science.com/products/detail.php?product_id=342 "FT232RL搭載小型USB-シリアルアダプタ 5V") 5V対応

About me
---
![twitter](http://d.hatena.ne.jp/images/icon-twitter.png "twitter") [@ksksue](http://twitter.com/#!/ksksue "twitter @ksksue")  
![icon1](http://a1.twimg.com/profile_images/549237316/twt_bigger.jpg "icon")  
Web page : Geekle Board - [http://d.hatena.ne.jp/ksksue/](http://d.hatena.ne.jp/ksksue/ "Geekle Board")  

License
----------
Copyright &copy; 2012 @ksksue
Licensed under the [Apache License, Version 2.0][Apache]

[Apache]: http://www.apache.org/licenses/LICENSE-2.0

