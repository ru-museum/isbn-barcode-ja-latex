# isbn-barcode-ja-latex
ISBN barcode Template for "Japan Book Code" with Latex.

- 日本図書コード（書籍 JAN コード）に対応した ISBN バーコードを Latex により PDF 上に生成します。

# 概要

### 日本図書コード
- 日本で出版する書籍に対しては 、 ISBN コード（国際標準図書番号）に準じ分類と価格表記を付加した日本独自の **日本図書コード**と、それを JAN コードに表現した**書籍 JAN コード**とがあります。

- 書籍 JAN コードは、所謂バーコード図像を含むもので国際標準の方式（**EAN-13**）によりエンコードされ２段組みとして表示されます。

### ISBN バーコード
-  latex 用各種バーコード作成ソフトには、EAN-13 に対応しているものの「日本仕様」に対応するものはありません。
- バーコードは TexLive(Linux) に同梱の [**pst-barcode**](https://github.com/bwipp/postscriptbarcode/blob/master/LICENSE) (GitHub) で作成しカスタマイズしています。

# 作業環境
- TexLive バージョン (2021.20220204-1) / Debian パッケージ
- LuaLatex（ Linux: Debian ）  
⇒ Debian での作業手順は [LuaLaTeX with Debian：環境構築と作業手順](https://github.com/ru-museum/isbn-barcode-ja-latex/blob/main/lualatex-with-debian.pdf) を参照して下さい。

# USAGE

- 詳しくは **isbn-barcode-ja-latex.pdf** の作業手順に従って下さい。 
- cron 或いは ZIP 解凍後、**isbn-barcode-ja-latex.tex** を開くと表示例の全てのソースを利用出来ます。
