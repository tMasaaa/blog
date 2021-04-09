# diaryです
- デザイン周りはまだ改修中です。
- 本体のmarkdownは`content/`以下にあります。

# 以下自分用メモ
## まだ改修中。 
- localhostではうまく行かないので、127.0.0.1:1313を使う必要がある。    
- https://gist.github.com/jeremybise/a6afea2d4c7f9044180ffeb663a617cf これそのうち役立ちそう  
- hogeフォルダの中に、いろいろ画像とかのリソースを入れておくとよさそう。  
- 記事の管理のため、`Date-Name`な感じにする。  
- listがうまく機能してない→empty cache and reloadで治った

## checklist
- `hugo new posts/hoge/index.md`でいける  
- 後ろスペース二個以上で改行っぽいのでreplaceを最後にかける  
- `cp -r public/* docs/`  
- CNAMEを忘れずに
- TOCははじめに対象を書いて、HTMLを見てそのidがXXXなら`[title](#XXX)`とすればOK

```
NODE_ENV=production hugo
rm -rf docs && mv public docs
```