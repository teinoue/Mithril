# .eslintignore

  
## eslintignoreでlintしたくないもの(無視するもの)を設定
http://qiita.com/inuscript/items/8610d3806a3f94d7d1d0  
lintしないファイルの指定。gitignoreとかと一緒の形式  
このあたりが鉄板か。testを含めるかどうかは趣味によるところかも  
bowerとか使わずDLしたファイルをどこから持ってきているような場合だとそいつらも含めるべきだろう。  
  
```
node_modules/
test/
```
  
## ESLintとは
http://tech.connehito.com/entry/2016/04/04/122802  
JavaScriptのコードの書き方をチェックするためのLinterです。  
主にインデントのズレ、未定義 or 未使用の変数がある、セミコロンが無い、などを検知して警告やエラーを出してくれます。  
  
https://techblog.yahoo.co.jp/javascript/how-to-create-eslint-rules/  
ESLintは、JavaScriptの静的検証ツールで、バグの原因になりそうな問題のあるコードを見つけたり、  
インデント数や括弧前後のスペースなどのコーディングスタイルを統一するのに役立ちます。  