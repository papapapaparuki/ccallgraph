# ccallgraph

## ccallgraphについて

Linuxカーネルのソースコードなどを読むときに「手元にコールグラフがあったらなぁ」と思いませんか？
実際にそのようなソフトはいくつかあるのですが，いくつか以下のような問題点があります．

* 多くの場合，コンパイルの情報を使用しているため，ビルドが通ることを前提としている
** このため，Linuxカーネルのモジュールのグラフを生成するのが難しい
* グラフを見たときに，どの関数がどのファイルにあるのかわかりにくい

これらの問題点を解決したのがccallgraphです．

詳しくはWikiページをごらんください．

[Wikiページはこちら](https://github.com/yasuharu/ccallgraph/wiki)

## サンプル

### Linuxのintelfbモジュールのソース

![サンプル画像](https://github.com/yasuharu/ccallgraph/wiki/sample.png)

