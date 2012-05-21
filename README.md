USB Serial Terminal for Android
=====

※現在は別レポジトリで管理しています。
[Android USB Serial Terminal Lite](https://github.com/ksksue/Android-USB-Serial-Monitor-Lite "Android USB Serial Monitor Lite")

！注意！Android 3.1以上であってもUSB Host APIを備えている機種でしか使用できません。<br>
例えば、docomo製のGalaxy NexusにはUSB Host APIが備わっていません。


特徴
- FTDI社製のUSBシリアル変換チップに対応
- Androidのルート権限を取る必要はなし
- ボーレート、データビット、パリティ、ストップビット、フロー制御の設定可
- 文字、16進数、10進数表示を切り替え
- 改行コード（CR ／ LF ／ CF＋LF）の選択可
- ADKのようにマイコン側に電源は必要なく、USBケーブルから電源供給
- Android のバージョンは3.1以上必須

[FTDriver](https://github.com/ksksue/FTDriver "FTDriver")が別途必要です。

About me
---
![twitter](http://d.hatena.ne.jp/images/icon-twitter.png "twitter") [@ksksue](http://twitter.com/#!/ksksue "twitter @ksksue")  
![icon1](http://a1.twimg.com/profile_images/549237316/twt_bigger.jpg "icon")  
Web page : Geekle Board - [http://d.hatena.ne.jp/ksksue/](http://d.hatena.ne.jp/ksksue/ "Geekle Board")  

License
----------
Copyright &copy; 2011 @ksksue
Licensed under the [Apache License, Version 2.0][Apache]

[Apache]: http://www.apache.org/licenses/LICENSE-2.0

<script type="text/javascript">

  var _gaq = _gaq || [];
  _gaq.push(['_setAccount', 'UA-31926415-1']);
  _gaq.push(['_trackPageview']);

  (function() {
    var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
    ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
    var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
  })();

</script>

