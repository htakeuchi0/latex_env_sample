# LaTeX文書作成環境サンプル

## 概要
LaTeX文書作成環境のサンプルである．    
実行環境は以下のとおりである．
* OS: Linux (Ubuntu 18.04.3 LTS)
* コンパイラ: uplatex
* PDFビューア: evince
* DVI-PDF変換ツール: dvipdfmx

TeXLiveは以下のコマンドで導入できる．    
`texlive-science` はalgorithm系のパッケージが含まれる．
```
$ sudo apt install texlive-lang-japanese
$ sudo apt install texlive-fonts-recommended
$ sudo apt install texlive-fonts-extra
$ sudo apt install texlive-science
```

## コンパイルと実行
以下のコマンドでコンパイルとPDF表示ができる．
```
$ make
```

以下のコマンドでソースファイル以外を削除する．
```
$ make clean
```
