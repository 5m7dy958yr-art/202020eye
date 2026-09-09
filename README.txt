# 20-20-20 タイマー（PWA）

## ファイル
- `index.html` …… 本体
- `manifest.json` …… ホーム画面追加用設定
- `sw.js` …… オフラインキャッシュ用
- `icon-192.png` / `icon-512.png` …… アプリアイコン

## GitHub Pagesで公開
1. GitHubで新しいRepositoryを作成。
2. このフォルダの5ファイルをすべてアップロード。
3. Repositoryの **Settings → Pages** を開く。
4. **Deploy from a branch** を選び、`main` / `/(root)` を指定してSave。
5. 数分後に表示されるURLをiPadのSafariで開く。
6. Safariの共有ボタン → **ホーム画面に追加** → 追加。

※ 通知・音声はiPadOS/Safariの制約を受けます。PWA化しても、バックグラウンド中の音声再生が常に保証されるわけではありません。
