# .editorconfig
http://monsat.hatenablog.com/entry/2014/03/04/editorconfig  

## .editorconfig ファイルを記述
プロジェクトのrootフォルダ等に .editorconfig を作成し、そこにコーディングスタイルを記述しましょう。  
書き方はこちらを参照してください  
おもなものは以下のとおりです。  

### root
これは、プロジェクトのルートディレクトリの .editorconfig を示す記述方法です。  
  
```
root = true  
```
  
EditorConfig Pluginは、なんらかのファイルをひらいたとき、同じフォルダおよび上位階層にある .editorconfig を探します。  
その際 .editorconfig 内に以下の記述があると、それ以上上位のフォルダを検索しません。  

### indent_style, indent_size, tab_width
インデントの方式を指定します。

以下は半角空白2つの例です。
  
```
indent_style = space
indent_size = 2
```
  
indent_style は、 "tab" or "space" が指定可能です。  
tabの場合は以下のように指定します。 tab_widthの初期値はindent_sizeの値とのことで省略可能のようです。  
  
```
indent_style = tab
tab_width = 4
```
  
### end_of_line, charset, insert_final_newline, trim_trailing_whitespace
改行コード（"lf" or "cr" or "crlf"）、文字コード、ファイル末尾の空行の有無、行末の空白の削除  
  
```
[*]
end_of_line = lf  
charset = utf-8  
insert_final_newline = true  
trim_trailing_whitespace  = true  
```
  
### その他
ファイルの種類により別にする場合は下記のようになります。  
  
```
[*]
indent_style = space
indent_size = 4

[*.html]
indent_style = tab
```