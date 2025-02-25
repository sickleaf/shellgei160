# シェル・ワンライナー160本ノックのリポジトリ

　技術評論社から出版された「[シェル・ワンライナー160本ノック](https://gihyo.jp/book/2021/978-4-297-12267-6)」のためのリポジトリです。書籍を購入した人は、とりあえず、

```
$ git clone https://github.com/shellgei/shellgei160.git
```

をお願いします。（できる人はforkでお願いします。）

## このリポジトリの役割

* 問題で利用するデータの提供
* 質問の受け付け（[issue](https://github.com/shellgei/shellgei160/issues)にて受け付けています。）
* 訂正の掲示
* 解答、別解のテキストデータの提供（`answer`ディレクトリにあります。）
    * さらなる別解のプルリクエスト大歓迎（[例](https://github.com/shellgei/shellgei160/pull/34)）


その他、シェル芸の一般的な情報は[シェル芸の情報を集めるサイト](https://shellgei.github.io/info/)にあります。

## お知らせ

* [問題23で記述に誤りがありました](https://github.com/shellgei/shellgei160/issues/6)。訂正を掲載しました。（20211004）
* 電子版の一部にスラッシュが抜ける誤りがあるようで、対応中です。（20211004）
    * 対応完了（20211007） 

## 訂正

### 第2刷まで

|ページ|場所|修正前|修正後|発見者・状況|コメント（主に上田）|
|-----|--------------------|-------------|----------------|----------|----------|
|p.105  |問題文4行目|このシェルの挙動もシグナルに関係しています。|これと同じような挙動はシグナルでも実現できます。| [issue6](https://github.com/shellgei/shellgei160/issues/6)|たぶん私が筆を入れたときに埋め込み -> みんなスルーという状況で発生したような気が・・・|
|p.106 |本文の3行目|Ctrl＋Qで発行されるシグナル|Ctrl＋Qと同じ働きをするシグナル|同上|同上|
|p.127 |問題文のコードの10行目|`\N`|`\d`|[issue8](https://github.com/shellgei/shellgei160/issues/8)|あれ・・・なんでだろう・・・|
|p.129 |1番目のコードボックスと本文1行目|`\N`|`\d`|同上|同上|
|p.130 |練習問題の問題文のコードの7行目|東から始まり|東京から始まり|[issue9](https://github.com/shellgei/shellgei160/issues/9)|不注意でした。|
|p.140 |脚注16のURL|https://docs.ruby-lang.org/ja/latest/docspec=2fregexp.html|https://docs.ruby-lang.org/ja/latest/doc/spec=2fregexp.html|[issue10](https://github.com/shellgei/shellgei160/issues/10)|すみません!|
|p.247 |リスト5.3 3行目|2020年1月1日|2020年8月1日|[issue23](https://github.com/shellgei/shellgei160/issues/23)|不注意でした。|
|p.248 |解答例のコードの1行目|`,$0`|削除|[issue23](https://github.com/shellgei/shellgei160/issues/23)|間違いですが残っていても動くのでスルーされたようです。|
|p.266| 2番目のコードブロック | `$ split -b 1000 -d image.bmp image.bmp.` | `$ split -b 1000 image.bmp image.bmp.` | [issue27](https://github.com/shellgei/shellgei160/issues/27) | `-d`を使った没案の一部消し忘れのようです。 |
|p.266| 2番目のコードブロックの直後の1行 | その番号から数字が開始するようになります。 | その引数の番号から数字が開始するようになります。 | [issue27](https://github.com/shellgei/shellgei160/issues/27) | 同上 |


## macでの挙動についての情報

* https://github.com/shellgei/shellgei160/issues?q=is%3Aissue+label%3Amac+

## issueに寄せられたコメント

* [正規表現の`{,n}`という指定について](https://github.com/shellgei/shellgei160/issues/7)
* [UTF-32BEについて](https://github.com/shellgei/shellgei160/issues/28)


## 参考のサイト

* 技術評論社の本書籍のページ: https://gihyo.jp/book/2021/978-4-297-12267-6
* シェル芸の情報を集めるサイト: https://shellgei.github.io/info/

## 連絡先

* [@ryuichiueda](https://twitter.com/ryuichiueda)（ひねりのない直球の愚痴・文句、外野からの意見の多い方を目にすると仕事の集中力が落ちるので、全く恨みはないんですけど機械的にブロックしている可能性があります。）
* 他の著者のTwitterアカウント
