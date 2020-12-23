# 勉強会#2
- 日時:2020/12/23 22:00~
- 参加者:siva([@honamium](https://twitter.com/honamium/ "twitter"))，やっぴ([@yappippi90](https://twitter.com/yappippi90/ "twitter"))，KSK([@StalemateKSK](https://twitter.com/StalemateKSK/ "twitter"))，Enigamict([@Enigamict](https://twitter.com/Enigamict/ "twitter"))，旅人([@boshoot05](https://twitter.com// "twitter"))，永井([@loyal_milktea](https://twitter.com/loyal_milktea/ "twitter"))[記録]

## やったこと

### OS本2日目
#### 資料(Enigamict)
アセンブラ学習とMakefile入門

<link rel="stylesheet" href="{{site.github.url}}/css/style.css" charset="utf-8">
<div class="g-slide">
<iframe src="https://hobosetouchi.slack.com/files/U01E2DQQX5L/F01HEPU9VD3/os2day.pdf?origin_team=T01E95P9V7C&origin_channel=C01GV00PL14"></iframe>
</div>

・makefileの作り方などが載っているが、本誌はwindows版を元に実装になっていたが、Linuxで実装した。
・Linuxのベースのディレクトリで開発を行う方は参考サイトを参照した方がいい！
・この参考サイト版は最初にブートセクタの簡単な解説もしているのでなんだったんだ・・・という方におすすめ
・本誌では新たに追加された命令について解説しているので、初学者でも完全に理解した状態になった。

### OS本3日目
#### 資料(siva)
本当のIPLを作ろう
<iframe src="https://hobosetouchi.slack.com/files/U01DUDASWP9/F01J7MR3PEC/30__________________os_____________3______.pptx?origin_team=T01E95P9V7C&origin_channel=C01GV00PL14"frameborder="0" width="1280" height="749" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
#### 得た知見とか
AH:ファンクションコードを指定
ファンクションコード→
今回使用したコード
0x02:読み込み
AL:処理するセクタ数
CH:シリンダ番号&0xff(各ヘッドに80ずつ)
CL:セクタ番号(1シリンダに1~18)
DH:ヘッド番号(表が0,裏が1）
DL:ドライブ番号

バッファアドレス
→セグメントレジスタ(ES)で拡張！


### OS本4日目前半
#### 資料(KSK)

#### 得た知見とか


## 次回
- 日時:2021/1/9 22:00~
- やること
  - OS本4日目後半(やっぴ)
  - OS本5日目(旅人)
  - (OS本6日目前半(永井))


<!-- [3回目](3day_log "議事録") -->

[Index](index)
