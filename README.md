# Source4GridPietGenerator
## 概要
[GridPietGenerator](https://github.com/Y-mos/GridPietGenerator)に入力する「処理フローファイル」のサンプルです。
## 内容物
[samples](samples)に、項目別にディレクトリ分けされています。
各ディレクトリの中には、つぎのファイルが格納されています。

- 処理フローファイル（拡張子 : .txt）
- ppm形式のPiet化された画像（拡張子 : .ppm）
- png形式のPiet化された画像（拡張子 : .png）
- [PietEmbedder](https://github.com/Y-mos/PietEmbedder)への入力ファイル（拡張子 : .piet）

ディレクトリによっては複数組のファイルが格納されている場合もあります。

## 手順

いずれも詳細は各リポジトリのREADME.mdを参照してください。

### 処理フローファイル

拡張子が.txtのファイルは、[GridPietGenerator](https://github.com/Y-mos/GridPietGenerator)の入力として使用できます。

例：
```
./GridPietGenerator samples/20210715_kuku/kuku.txt
```

### .pietファイル
拡張子が.pietのファイルは、[PietEmbedder](https://github.com/Y-mos/PietEmbedder)の入力として使用できます。

例：
```
./PietEmbedder samples/20210720_max_complete/max_complete.piet mt_fuji.png out.png
```

## プログラムの解説

[こちらのブログ](https://ymos-hobby-programing.hatenablog.com)の該当記事をご参照ください。

[samples](samples)以下のディレクトリの先頭8桁の数値は、

当該プログラムの解説が掲載された日付(YYYYMMDD)を示しています。

同日に複数の記事が書かれた場合は、

日付の直後に書かれた順に「-1」、「-2」、・・・と付記しています。

## ライセンス

BSD 3-Clause License ([LISENCE](LISENCE)参照)

## 問い合わせ / Contact

Y-mos

twitter:[Y-mos](https://twitter.com/ymos3327)

