# 勉強会#3
- 日時:2021/01/09 22:00~
- 参加者:siva([@honamium](https://twitter.com/honamium/ "twitter"))，やっぴ([@yappippi90](https://twitter.com/yappippi90/ "twitter"))，KSK([@StalemateKSK](https://twitter.com/StalemateKSK/ "twitter"))，旅人([@boshoot05](https://twitter.com// "twitter"))，永井([@loyal_milktea](https://twitter.com/loyal_milktea/ "twitter"))，Enigamict([@Enigamict](https://twitter.com/Enigamict/ "twitter"))[記録]

## やったこと

### OS本4日目(前半)
#### 資料(KSK)
C言語からメモリに書き込みたい、しましま模様、ポインタに挑戦、応用編
<link rel="stylesheet" href="{{site.github.url}}/css/style.css" charset="utf-8">
<div class="g-slide">
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQAPmExOsj-5dmaVb-GzGCu4bMUPhg_ESV1nET-lDmB8NIMQRVI7dhsgVSUJlb48Fzj-F0iVyhDJ37m/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
</div>

* 画面を表示させようの会
* C言語でメモリに上手いことやってアセンブラを使い画面に変化を起こしたりして模様をつけて変化を楽しもう
* ここではC言語のポインタについて詳しく解説されている。本グループワークではそれぞれがポインタについて語り合い人類には早すぎるという結果になった（理解が深まったと思います）

### OS本4日目(後半)
#### 資料(やっぴ)
<link rel="stylesheet" href="{{site.github.url}}/css/style.css" charset="utf-8">
<div class="g-slide">
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vSE8wb9ZqFOQEzW2p5T7wCI4Gb4xsGtKJmJiygf89fc9qlxh5AQ7jJs80t06A1WVrvny2AJm-ST8Kz9/embed?start=false&loop=false&delayms=3000" frameborder="0" width="1280" height="749" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
</div>

* さらに模様の色を変えて変化を楽しもうの会
* 86ページの下にある16*3 = 48 ←*3ってなに…という点に注目した
* 84p下のコードと一緒に見てもらおう  
```
static unsigned table_rgb[16 * 3] = {  
    0x00 0x00 0x00,
    ...
```
* このコードの0x00が3byte(24bit)並んでいることで、何故3つ指定なのか本グループで話し合った所RGBで指定しているからなのではないかという説が出てきた。
* 確かにRGBは指定する際R(8bit)G(8bit)B(8bit)の合計24bitで指定していることもあり有力であることが分かった。

### OS本5日目
#### 資料(旅人)
<link rel="stylesheet" href="{{site.github.url}}/css/style.css" charset="utf-8">
<div class="g-slide">
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vSILZX_i848rMm_H--djypY9JPkujx_SHkt6rDjC01YsWsYLMmCjFCYvrHwQ5G1eyCsEplWF-TCXimr/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
</div>

* すごいOSに近づいてきたの会
* 構造体を使っていい感じのコードを書こう！
* 構造体がどういう動きをして目的を果たすのかを考え、文字を表示させてみよう
* めちゃくちゃ大変なことが理解できる、じゃあ改造して楽に表示させてみよう
* マウスカーソルも同じ要領で作り、座標を表示させてみよう
* 疑問点としてはGDTとIDTってなに…という点に注目し、本グループでは色々と話し合った。



## 次回
- 日時:2021/1/23 22:00~
- やること
  - OS本6日目(永井)
  - OS本7日目(Enigamict)


<!--[4回目](4day_log "議事録") -->

[Index](index)
