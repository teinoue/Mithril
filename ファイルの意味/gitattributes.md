# .gitattributes
https://git-scm.com/book/ja/v2/Git-%E3%81%AE%E3%82%AB%E3%82%B9%E3%82%BF%E3%83%9E%E3%82%A4%E3%82%BA-Git-%E3%81%AE%E5%B1%9E%E6%80%A7
GITの属性ファイル
バイナリファイルとして扱う。  
```例
*.pbxproj binary
````
Mithrilの.gitattributesも上記のようにMithril.jsとMithril.min.jsがバイナリファイル扱いに設定されていた。  

```
* text=auto
/mithril.js binary
/mithril.min.js binary
```