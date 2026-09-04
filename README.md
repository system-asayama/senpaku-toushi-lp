# senpaku-toushi-lp

船舶投資（中古船舶・即時償却スキーム）のランディングページ。`public/index.html` 単一ファイル構成（HTML/CSS/JS インライン）。

- 節税シミュレーター（投資額・課税所得・実効税率・消費税方式で試算）
- お問い合わせフォームは mailto 方式。送信先は `public/index.html` 内の `TO` 定数を変更してください。

Docker + nginx 静的サイトのスタータテンプレート。

## 開発
```bash
docker build -t senpaku-toushi-lp .
docker run -p 8080:80 senpaku-toushi-lp
open http://localhost:8080
```

## デプロイ
このリポを本アプリの「環境別デプロイ設定」に追加し、
`main` ブランチに push すると自動デプロイされます。
