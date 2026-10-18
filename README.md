# フーセンカート

スマホとPCのブラウザで遊べる、風船を割り合う3Dカートバトル。

## ファイル
- `index.html` … ゲーム本体
- `config.js` … Firebase（オンライン対戦の中継）の接続設定
- `art/` … キャラクター画像
- `database.rules.json` … Firebase Realtime Database のセキュリティルール

## 遊び方
- ひとり練習・走行テストは、ページを開けばすぐ遊べます
- オンライン対戦は `config.js` に Firebase の設定を入れると使えます。同じ合言葉を入れた人どうしで対戦します
