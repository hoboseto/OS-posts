### deploy先

[https://hoboseto.github.io/OS-posts/index](https://hoboseto.github.io/OS-posts/index)


### 議事録の追加
OS-posts(このレポジトリのroot)真下にmarkdownファイルをおけば勝手にhtmlにレンダリングされるのでmdファイルで書くとよいです．あと，画像の挿入とかはimageフォルダに 入れて
`![画像の注釈]({{site.github.url}}/image/貼りたい画像)`とすればうまいこと表示されます．

#### スライド挿入時の注意

そのまま埋め込むとスライドのサイズがバグるので下記の形で挿入してください．
```html
<link rel="stylesheet" href="{{site.github.url}}/css/style.css" charset="utf-8">
<div class="g-slide">
<iframe src="挿入したいスライド"></iframe>
</div>
```
