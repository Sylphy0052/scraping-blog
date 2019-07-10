# scraping-blog
## 何をするのか
- クライアント(Web)でキーワードを入力すると，そのキーワードに関連する記事を取得する
- 表示にはタイトル(URLリンク付き)と最初の何文字かだけを表示するシンプルな機能を想定
- ページ番号機能
- ページ番号選択遷移機能
- 取得対象ははてぶろ，Qiita

## あったらいいな
- お気に入り機能
- 要約機能
- 通知機能(新作があったら)→Batch処理

## 何を使うか
- Docker
- Flask(Python)
- Vue.js
- MySQL

## フロー
Client(Vue.js) → Controller(Json) → Logic → Json → Client(Vue.js)

## 参考
1. [Vue.jsとFlaskのDocker環境を構築してみた](https://qiita.com/kouchanne/items/417bad58633cc4262012)