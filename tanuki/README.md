# たぬきの自己紹介サイト

外部依存なしの1ページサイトです。プロフィール・活動・作品・連絡先はダミーデータです。

## ローカル起動

このフォルダで以下を実行し、http://localhost:4173 を開いてください。

```sh
python3 -m http.server 4173 --directory dist
```

`dist/index.html` を直接ブラウザで開くこともできます。
文章・配色・作品の詳細はすべて `dist/index.html` 内で編集できます。
