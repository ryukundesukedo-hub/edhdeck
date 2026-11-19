# EDHデッキビルダー(iPhone用Webアプリ)

## 公開手順(GitHub Pages・PCで作業)
1. GitHub にログインし、右上「＋」→「New repository」。名前は `edh-deck`、**Public** を選んで作成
2. 「uploading an existing file」をクリックし、このフォルダの6ファイル(index.html / sw.js / manifest.webmanifest / icon-192.png / icon-512.png / apple-touch-icon.png)をドラッグして「Commit changes」
3. リポジトリの「Settings」→「Pages」→ Source を「Deploy from a branch」、Branch を `main` / `(root)` にして Save
4. 1〜2分後、`https://<ユーザー名>.github.io/edh-deck/` で開けるようになります

## iPhone に入れる
Safari で上の URL を開き、共有ボタン →「ホーム画面に追加」。

## PC のアプリと連携
- スマホ → PC:デッキ編集 →「書き出し」→「.dck ファイルを共有」→ AirDrop / iCloud Drive で PC へ。Forge のデッキフォルダ(commander)に置く
- PC → スマホ:.dck を iCloud Drive などに置き、デッキ一覧 →「インポート」→「ファイルを選ぶ」

## 更新するとき
ファイルを GitHub に上書きアップロードするだけ。アプリを開き直すと反映されます。
