# isbn-barcode-ja-latex
ISBN barcode Template for "Japan Book Code" with Latex.

- 日本図書コード（書籍 JAN コード）に対応した ISBN バーコードを Latex により PDF 上に生成します。

### [ 注意 ]  
- 以下にも別途解説していますので参照して下さい(2025-07-24)。    
**OCRフォント**の使用法など一部記述を変更しています（**推奨**）。  
[jis-barcode-lualatex](https://github.com/ru-museum/jis-barcode-lualatex)　//github.com/ru-museum/jis-barcode-lualatex　

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

- 詳しくは [日本語書籍用 ISBN バーコードの作成](https://github.com/ru-museum/isbn-barcode-ja-latex/blob/main/isbn-barcode-ja-latex.pdf)（isbn-barcode-ja-latex.pdf）の作業手順に従って下さい。 
- 作例サンプル集として [書籍JANコード サンプル集](https://github.com/ru-museum/isbn-barcode-ja-latex/blob/main/samples-isbn-barcode-ja.pdf)（samples-isbn-barcode-ja.pdf）にまとめてあります。
- **samples-isbn-barcode-ja.tex** を開くと表示例の全てのサンプルコードを利用出来ます。
