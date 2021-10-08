# iot_kit

<html>
<head>

<meta charset="UTF-8">
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=EmulateIE10" />
<meta http-equiv="X-UA-Compatible" content="IE=edge">

<!--ここから上はお決まりの定型文です-->


<!--ここからが表現の書式などを決めるcssという部分-->

<style type="text/css">
 p {
color: #ffffff;
font-size: 1.5em;
 }
 

 .red {color:#ff0000;}
 .grey {color:#ffffff; background:#999999;}
 .snow {color:#fffafa;}
 .yellow {color:#ff0000; background:#ffff00;}
 .blue {color:#0000ff;}
 .white {color:#ffffff; blinking;}
 .waku {border:2px dotted #99cc66;
　　　　　　line-height: 200%;
　　　　　　padding: 10px;}

 
 main {
background-color: rgba(255, 255, 255, 0.5);
}

section {
background-color: rgba(0, 225, 0, 0.3);
}
 

/* 点滅 */
.blinking{
	-webkit-animation:blink 1.5s ease-in-out infinite alternate;
    -moz-animation:blink 1.5s ease-in-out infinite alternate;
    animation:blink 1.5s ease-in-out infinite alternate;
}
@-webkit-keyframes blink{
    0% {opacity:0;}
    100% {opacity:1;}
}
@-moz-keyframes blink{
    0% {opacity:0;}
    100% {opacity:1;}
}
@keyframes blink{
    0% {opacity:0;}
    100% {opacity:1;}
}

#wrap {background:none} /*PC用の背景はオフ 背景を指定する部分*/
body::before {
  content:"";
  display:block;
  position:fixed;
  top:0;
  left:0;
  z-index:-1;
  width:100%;
  height:100vh;
  background:url(20211006_000.jpg) center/cover no-repeat; /*fixedをトル！*/
  -webkit-background-size:cover;/*Android4*/
  }
  
a.p:hover {
    position: relative;
    text-decoration: none;
}
a.p span {
    display: none;
    position: relative;
    top: -0.5em;
    left: 2em;
}
a.p:hover span {
    border: none;
    display: block;
    width: 800px;
}   
 

@media	screen and (min-width: 540px),
	screen and (orientation: landscape) {
   p.note { display: none; }
}

</style>

<link href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/css/lightbox.css" rel="stylesheet">

</head>

<body>


<p class="note">
  モバイル端末をお使いの場合は、画面を横向きにすると
  より見やすくご覧頂けます。
</p>
    
<!--ここまでは定型文としてそのままコピペして再利用します—->

<!-—リンクの作り方、例
<a href="ここにリンク先のURLを入れる" target="_blank" rel="noopener noreferrer">新規タブで開く</a>-—>

<!-—ぱんくずリストの表示例-—>
<!--今回は未使用
<p><a href="https://torokoid.github.io/fts_home">Home</a>>同窓会</p>
—->

<!—-表題の表示、背景黄色、流れ文字の例-->
<h1><span class="yellow"><marquee behavior="alternate">!!! 2021年9月30日(木)に申し込んだ IoT 学習キットが、10月6日(水)に届きました !!!</marquee></span></h1>

<!--
<div style="background-color:rgb(255,255,255,0.3);”>
-->

<!--QRコードの表示例--><!--
<p align="left"> <img src="QR_mama.png" alt="アクセス用QRコード" width="100">アクセス用QRコード</p>-->

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<h3><span class="yellow">IoT学習キットの無償モニター募集です。<br>センサーの情報を特定省電力無線でラズパイに飛ばしてグラフ表示するというアイテム。<br>当たらないだろうな〜と思って申し込んだら、電話がかかって来て6日後には到着しました ！</span></h3>
<a href="20211006_009.png" data-lightbox="abc"><img src="20211006_009.png" alt="サンプル画像" width="900" /></a>
<h3><span class="yellow">届いたのはこんな部品。</span></h3>
<a href="20211006_001.jpg" data-lightbox="abc"><img src="20211006_001.jpg" alt="サンプル画像" width="900" /></a>
<a href="20211006_002.jpg" data-lightbox="abc"><img src="20211006_002.jpg" alt="サンプル画像" width="900" /></a>
<a href="20211006_003.jpg" data-lightbox="abc"><img src="20211006_003.jpg" alt="サンプル画像" width="900" /></a>
<h3><span class="yellow">取説はNetにもありましたが、紙で入ってました。</span></h3>
<a href="20211006_010.jpg" data-lightbox="abc"><img src="20211006_010.jpg" alt="サンプル画像" width="900" /></a>
<a href="20211006_011.jpg" data-lightbox="abc"><img src="20211006_011.jpg" alt="サンプル画像" width="900" /></a>
<a href="20211006_012.jpg" data-lightbox="abc"><img src="20211006_012.jpg" alt="サンプル画像" width="900" /></a>
<a href="20211006_013.jpg" data-lightbox="abc"><img src="20211006_013.jpg" alt="サンプル画像" width="900" /></a>
<!--
<a href="20211006_004.jpg" data-lightbox="abc"><img src="20211006_004.jpg" alt="サンプル画像" width="900" /></a>
-->
<h3><span class="yellow">ラズパイは自分で用意してとの事で、４Bの４GBを先行で入手<br>3Bか3B+しか作動保証しないと言われましたが、確信犯的に4Bです・・・。</span></h3>
<a href="20211006_005.jpg" data-lightbox="abc"><img src="20211006_005.jpg" alt="サンプル画像" width="900" /></a>

<h3><span class="yellow">組み上げるとこんな感じ、左がセンサーで、右がラズパイ。<br>USBに刺さった特定省電力無線の親機が目立ってます。</span></h3>
<a href="20211006_007.jpg" data-lightbox="abc"><img src="20211006_007.jpg" alt="サンプル画像" width="900" /></a>

<h3><span class="yellow">作動保証のないラズパイ４Bでも全く問題なく動きました。<br>最終的に、ラズパイに繋いだモニターにCO2濃度、温度、湿度のグラフが表示されています。</span></h3>
<a href="20211006_008.png" data-lightbox="abc"><img src="20211006_008.png" alt="サンプル画像" width="900" /></a>

<h3><span class="yellow">温度は水銀柱温度計と比べても、かなり正確でした。</span></h3>
<a href="20211006_006.jpg" data-lightbox="abc"><img src="20211006_006.jpg" alt="サンプル画像" width="900" /></a>
	
<p><a href="https://cmengineering.co.jp/"</a>最後に学習キットをいただいた会社のHPをリンクします。</p>

<!--
</div>
-->
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<h3><span class="yellow">今回は面白い、今風のアイテムを頂いて試してみたと言うお話でした。<br>ここまで観ていただきありがとう御座いました。</span></h3>



<!-- フッタ -->
 <footer>
 Copyright 2021/10/06 S.Hada
 </footer>

<!--HPにさまざまなJavaScriptを呼び込むための書式-->
<script src="https://code.jquery.com/jquery-1.12.4.min.js" type="text/javascript"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/js/lightbox.min.js" type="text/javascript"></script>

<script type='text/javascript' src='https://torokoid.github.io/shiba/jquery.js?ver=1.12.4'></script>
<script src="https://torokoid.github.io/shiba/jquery.goup.min.js"></script>
<script src="https://torokoid.github.io/shiba/my.js"></script>


</body>

</html>
