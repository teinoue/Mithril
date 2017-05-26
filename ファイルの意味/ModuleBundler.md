## モジュールバンドラ(Module Bundler)
http://qiita.com/Sekky0905/items/c5130a85f67c04962e46  

複数に分割されたJavaScriptのファイル（Module）を結びつけて1つのJavaScriptファイルにするツール

### なぜモジュールバンドラ(Module Bundler)が必要か
+ 現在、最新のECMAScriptでは、1ファイル=1モジュールの考え方が考案され徐々に広まってきている
+ しかし、現存のほとんどのブラウザでは、それに対応しておらず、scriptタグに書かれたJavaScriptのみを実行するのが普通だ
+ モジュールバンドラ(Module Bundler)を使用すれば、複数のJavaScriptファイルをまとめ上げて1つのJavaScriptファイルに統合してくれる
+ また、HTMLにエントリポイントとなるJavaScriptファイルのみを貼っておいても、現在のブラウザではモジュール間の依存関係を解決して、他のモジュールまで利用するということはできない（複数のJavaScriptファイル間の依存関係を解決してくれない）
+ そこで、モジュールバンドラ(Module Bundler)は、複数に分割されたJavaScripファイル(モジュール)を1つのJavaScriptファイルにしてしまい、さらにその際に複数のJavaScriptファイル(Module)間の依存関係を解決してくれる

## webpack
1. 分割したJavaScriptファイルを1つにまとめ上げられる（1つのファイルにビルドできる）=>bundle.jsになる
1. JavaScript同士の依存関係も解決してくれる

参考にさせていただいたサイト  

https://webpack.js.org/  
https://ics.media/entry/12140  
http://qiita.com/ossan-engineer/items/8352bdeab9ce8c8c00ef  
http://qiita.com/chuck0523/items/caacbf4137642cb175ec  


さらにwebpackは複数のbundle.jsをアウトプットすることもできる  
=> 例えばテストには、テスト用のtest_bundle.jsを作ることができる  
=> テストにおいても、JavaScriptはモジュールの分割の依存関係を解消するために、バンドルする必要があるのでそれに役立つ  
複数の出力ファイルをバラバラに出力するのに参考にさせていただいたサイト  
  
http://webdesign-dackel.com/2015/09/10/webpack-multiple-output/  

### webpackで注意すべきこと  
webpackは循環依存は解決できない  
=> 例えば、エントリポイントであるA.jsとB.jsがお互いに依存しあっている場合、ループしてしまう  
=>index.js(エントリポイントとなるファイル)はimportできない