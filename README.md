# senpaku-toushi-lp

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
