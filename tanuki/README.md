# たぬきの自己紹介サイト

外部依存なしの1ページサイトです。プロフィール・活動・作品・連絡先はダミーデータです。

## ローカル起動

このフォルダで以下を実行し、http://localhost:4173 を開いてください。

```sh
python3 -m http.server 4173 --directory dist
```

`dist/index.html` を直接ブラウザで開くこともできます。
文章・配色・作品の詳細はすべて `dist/index.html` 内で編集できます。

## GitHub Pages

公開URL: https://moai-okinawa.github.io/portfolio-tanuki/

`.github/workflows/deploy-pages.yml` が `tanuki/dist` を公開します。
`main` へのサイト・ワークフローの変更をpushすると自動で反映されます。
GitHub の Actions タブから `Deploy to GitHub Pages` を手動実行することもできます。
リポジトリの Settings → Pages → Source は GitHub Actions を使用します。
