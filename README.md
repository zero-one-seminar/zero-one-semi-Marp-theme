# zero-one-semi-Marp-theme
Marpのテーマです。ゼミ資料の作成等に使ってください。

# 使い方
## VSCodeの設定
### そのまま使いたい場合
設定の`markdown.marp.themes`に
```
https://raw.githubusercontent.com/zero-one-seminar/zero-one-semi-Marp-theme/main/01semiTheme.css
```
を追加します。

### 編集して使いたい場合
ローカルの絶対パスでは上手く読み込んでくれません。
設定の`markdown.marp.themes`に、ワークスペースで開いているディレクトリからの相対パスを追加します。

例えば、クローンした`zero-one-semi-Marp-theme/`をワークスペースに追加して、`markdown.marp.themes`に`.\01semiTheme.css"`を指定すれば使えるようになります。

テーマ名は`01semi`です。
タイトルページには`class: title`を、
本文のページには`class: slides`を指定するとデザインを適用できます。
