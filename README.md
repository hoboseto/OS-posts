### deploy先

[https://hoboseto.github.io/OS-posts/index](https://hoboseto.github.io/OS-posts/index)

### 更新
更新するもの

#### index.md
* 勉強会のナンバーと日付
* やったことの簡単な目次

#### [勉強会のナンバー]day_log.md
* タイトルのナンバーと日時と参加者([記録]を自分につける)
* やったこと
* 次回以降の日程と簡単な目次

### 議事録の追加方法
OS-posts(このレポジトリのroot)真下にmarkdownファイルをおけば勝手にhtmlにレンダリングされるのでmdファイルで書くとよいです．あと，画像の挿入とかはimageフォルダに 入れて
`![画像の注釈]({{site.github.url}}/image/貼りたい画像)`とすればうまいこと表示されます．

#### スライド挿入時の注意

そのまま埋め込むとスライドのサイズがバグるので下記の形で挿入してください．
スライドはgoogle slideに一旦上げてから公開を押してリンクを貼るのがいいかんじです．

```html
<link rel="stylesheet" href="{{site.github.url}}/css/style.css" charset="utf-8">
<div class="g-slide">
<iframe src="挿入したいスライド"></iframe>
</div>
```
